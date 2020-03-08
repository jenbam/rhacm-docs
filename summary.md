# Summary
 * [About](about/about.md)
   * [Architecture](about/architecture.md)
   * [Components](about/components.md)
 * [Release Notes](about/release_notes.md)
   * [What's new](about/whats_new.md)
   * [Known issues and limitations](about/known_issues.md)
   * [Considerations for GDPR readiness](about/gdpr_readiness.md)
   * [Considerations for FIPS readiness](about/fips_compliance.md)
 * [Installation](install/overview.md)
   * [Requirements and recommendations](install/requirements.md)
     * [Supported cloud providers](install/supported_clouds.md)
     * [Hardware requirements and recommendations](install/hardware_reqs.md)
     * [Components](install/components.md)
     * [Supported operating systems and platforms](install/supported_os.md)
     * [Supported browsers](install/supported_browsers.md)
     * [Supported environments](install/environments_overview.md)  
   * [Preparing for installation](install/prep.md)
     * [Accessing installation files](install/part_numbers.md)
     * [Sizing your hub cluster](install/plan_capacity.md)
     * [Endpoints](install/cluster_endpoints.md)
     * [Cluster configuration ConfigMap](install/configmap_cluster.md)
     * [Configuration options](install/config_install.md)
   * [Installing](install/installation.md)
 * [Console](console/console_intro.md)
   * [Observability from the console](console/console.md)
   * [Managing your cluster with the Visual Web Terminal](console/vwt_search.md)
   * [Configuring your logo](console/logo.md)
   * [Managing cluster labels](console/cluster_label.md)
 * [Governance and risk](compliance/compliance_intro.md)
   * [Certificates in (product name)](services/cert_manager/certificates.md)
   * [Policy overview](compliance/policy_overview.md)
   * [Policy controllers](compliance/policy_controllers.md)
     * [Configuration policy controller](manage_policies/config_policy_ctrl.md)
     * [Certificate policy controller](manage_policies/cert_policy_ctrl.md)
     * [IAM policy controller](manage_policies/iam_policy_ctrl.md) 
     * [CIS policy controller](manage_policies/cis_policy.md)
     * [Network policy controller](manage_policies/nw_policy_ctrl.md)
   * [Policy example](compliance/policy_example.md)
   * [Policy samples](manage_policies/policy_samples.md)
   * [Creating a policy](compliance/create_policy.md)
   * [Managing a security policy](manage_cluster/manage_grc_policy.md)
   * [Using a notary service for image signing](compliance/notary_server.md)
   * [Image signing support for image policies](compliance/image_policy_signing.md)
 * [Service discovery](services/working_serv_intro.md)
   * [Service discovery overview](services/serv_overview.md)
   * [Discover services](services/serv_prep.md)
   * [Enabling a Kubernetes service for discovery](services/serv_kube.md)
   * [Enabling a Kubernetes ingress for discovery](services/serv_ingress.md)
   * [Enabling an Istio service for discovery](services/serv_istio.md)
 * [Cluster management](manage_cluster/intro.md)
   * [Creating a cluster](manage_cluster/create.md)
     * [Creating an IBM Kubernetes Service cluster](manage_cluster/create_iks..md)
     * [Creating a Google Kubernetes Engine cluster](manage_cluster/create_gke.md)
     * [Creating an Azure Kubernetes Service cluster](manage_cluster/create_aks.md)
     * [Creating an Amazon Elastic Kubernetes Service cluster](manage_cluster/create_eks.md)
     * [Creating an OpenShift on Amazon Web Services cluster](manage_cluster/create_ocp_aws.md)
   * [Scaling your clusters](manage_cluster/scale_mcm.md)
   * [Importing a target managed cluster](manage_cluster/import.md)
     * [Importing a cluster with the console](manage_cluster/import_gui.md)
     * [Importing a cluster with the CLI](manage_cluster/import_cli.md)
     * [Importing a managed cluster in an air gapped environment](manage_cluster/offline_endpoint.md)
     * [Modifying the multicluster endpoint settings for your cluster](manage_cluster/modify_mc_end.md)
 * [Application management (Developer preview)](manage_applications/overview.md)
   * [Application lifecycle](manage_applications/app_lifecycle.md)
   * [Application resources](manage_applications/app_resources.md)
     * [Managing application resources](manage_applications/managing_apps.md)
       * [Managing deployables](manage_applications/managing_deployables.md)
       * [Managing channels](manage_applications/managing_channels.md)
       * [Managing subscriptions](manage_applications/managing_subscriptions.md)
       * [Managing placement rules](manage_applications/managing_placement_rules.md)
       * [Managing secrets](manage_applications/managing_secrets.md)
       * [Deploying an application resource](manage_applications/deployment_app.md)
       * [Deploying an application resource with a rolling update](manage_applications/deployment_rollout.md)
       * [Managing applications with the console](manage_applications/managing_apps_console.md)
       * [Migrating subscriptions](manage_applications/migrate_subscriptions.md)
 * [APIs](apis/cfc_api.md)
    * [{{site.data.keyword.mcm_notm}} APIs](apis/mcm_apis.md)
      * [Applications](apis/applications.json)
      * [Channels](apis/channels.json)
      * [Deployables](apis/deployables.json)
      * [Placement rules](apis/placementRules.json)
      * [Policies](apis/policies.json)
      * [Subscriptions](apis/subscriptions.json)
 