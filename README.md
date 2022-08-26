# Azure Services Naming Convention 

Defining and enforcing naming conventions for resources can help improve resource discovery, cost management, automation, and organisation of Azure resources.

| Category | Resource Type | Resource Namespace | Abbreviation | Length Restrictions |
| --- | --- | --- | --- | --- |
| General | ManagedIdentity | `Microsoft.ManagedIdentity/userAssignedIdentities` | `id-` | 3 - 128 |
| General | Managementgroup | `Microsoft.Management/managementGroups` | `mg-` | ? |
| General | Policydefinition | `Microsoft.Authorization/policyDefinitions` | `policy-` | 1 - 64 |
| General | Resourcegroup | `Microsoft.Resources/resourceGroups` | `rg-` | 1 - 90 |
| Networking | Applicationgateway | `Microsoft.Network/applicationGateways` | `agw-` | 1 - 80 |
| Networking | Applicationsecuritygroup(ASG) | `Microsoft.Network/applicationSecurityGroups` | `asg-` | 1 - 80 |
| Networking | Bastion | `Microsoft.Network/bastionHosts` | `bas-` | 1 - 80 |
| Networking | CDNprofile | `Microsoft.Cdn/profiles` | `cdnp-` | 1 - 260 |
| Networking | CDNendpoint | `Microsoft.Cdn/profiles/endpoints` | `cdne-` | 1 - 50 |
| Networking | Connections | `Microsoft.Network/connections` | `con-` | 1 - 80 |
| Networking | DNS | `Microsoft.Network/dnsZones` | `dnsz-` | 1 - 63 |
| Networking | DNSzone | `Microsoft.Network/privateDnsZones` | `pdnsz-` | 1 - 63 |
| Networking | Firewall | `Microsoft.Network/azureFirewalls` | `afw-` | 1 - 80 |
| Networking | Firewallpolicy | `Microsoft.Network/firewallPolicies` | `afwp-` | 1 - 80 |
| Networking | ExpressRoutecircuit | `Microsoft.Network/expressRouteCircuits` | `erc-` | 1 - 80 |
| Networking | FrontDoorinstance | `Microsoft.Network/frontDoors` | `fd-` | 5 - 64 |
| Networking | FrontDoorfirewallpolicy | `Microsoft.Network/frontdoorWebApplicationFirewallPolicies` | `fdfp-` | 1 - 128 |
| Networking | Loadbalancer(internal) | `Microsoft.Network/loadBalancers` | `lbi-` | 1 - 80 |
| Networking | Loadbalancer(external) | `Microsoft.Network/loadBalancers` | `lbe-` | 1 - 80 |
| Networking | Loadbalancerrule | `Microsoft.Network/loadBalancers/inboundNatRules` | `rule-` | 1 - 80 |
| Networking | Localnetworkgateway | `Microsoft.Network/localNetworkGateways` | `lgw-` | 1 - 80 |
| Networking | NATgateway | `Microsoft.Network/natGateways` | `ng-` | 1 - 80 |
| Networking | Networkinterface(NIC) | `Microsoft.Network/networkInterfaces` | `nic-` | 1 - 80 |
| Networking | Networksecuritygroup(NSG) | `Microsoft.Network/networkSecurityGroups` | `nsg-` | 1 - 80 |
| Networking | Networksecuritygroup(NSG)securityrules | `Microsoft.Network/networkSecurityGroups/securityRules` | `nsgsr-` | 1 - 80 |
| Networking | NetworkWatcher | `Microsoft.Network/networkWatchers` | `nw-` | 1 - 80 |
| Networking | PrivateLink | `Microsoft.Network/privateLinkServices` | `pl-` | 1 - 80 |
| Networking | PublicIPaddress | `Microsoft.Network/publicIPAddresses` | `pip-` | 1- 80 |
| Networking | PublicIPaddressprefix | `Microsoft.Network/publicIPPrefixes` | `ippre-` | 1 - 80 |
| Networking | Routefilter | `Microsoft.Network/routeFilters` | `rf-` | 1 - 80 |
| Networking | Routetable | `Microsoft.Network/routeTables` | `rt-` | 1 - 80 |
| Networking | Serviceendpoint | `Microsoft.serviceEndPointPolicies` | `se-` | 1 - 80 |
| Networking | TrafficManagerprofile | `Microsoft.Network/trafficManagerProfiles` | `traf-` | 1 - 63 |
| Networking | Userdefinedroute(UDR) | `Microsoft.Network/routeTables/routes` | `udr-` | 1 - 80 |
| Networking | Virtualnetwork | `Microsoft.Network/virtualNetworks` | `vnet-` | 2 - 64 |
| Networking | Virtualnetworkpeering | `Microsoft.Network/virtualNetworks/virtualNetworkPeerings` | `peer-` | 1 - 80 |
| Networking | Virtualnetworksubnet | `Microsoft.Network/virtualNetworks/subnets` | `snet-` | 1 - 80 |
| Networking | VirtualWAN | `Microsoft.Network/virtualWans` | `vwan-` | 1 - 80 |
| Networking | VPNGateway | `Microsoft.Network/vpnGateways` | `vpng-` | 1 - 80 |
| Networking | VPNconnection | `Microsoft.Network/vpnGateways/vpnConnections` | `vcn-` | 1 - 80 |
| Networking | VPNsite | `Microsoft.Network/vpnGateways/vpnSites` | `vst-` | 1 - 80 |
| Networking | Virtualnetworkgateway | `Microsoft.Network/virtualNetworkGateways` | `vgw-` | 1 - 80 |
| Networking | WebApplicationFirewall(WAF)policy | `Microsoft.Network/firewallPolicies` | `waf` | 1 - 80 |
| Networking | WebApplicationFirewall(WAF)policyrulegroup | `Microsoft.Network/firewallPolicies/ruleGroups` | `wafrg` | 1 - 80 |
| Compute and Web | AppServiceenvironment | `Microsoft.Web/sites` | `ase-` | 2 - 60 |
| Compute and Web | AppServiceplan | `Microsoft.Web/serverFarms` | `plan-` | 1 - 40 |
| Compute and Web | Availabilityset | `Microsoft.Compute/availabilitySets` | `avail-` | 1 - 80 |
| Compute and Web | AzureArcenabledserver | `Microsoft.HybridCompute/machines` | `arcs-` | 1 - 15 |
| Compute and Web | AzureArcenabledKubernetescluster | `Microsoft.Kubernetes/connectedClusters` | `arck` | 1 - 15 |
| Compute and Web | Cloudservice | `Microsoft.Compute/cloudServices` | `cld-` | 1 - 15 |
| Compute and Web | Diskencryptionset | `Microsoft.Compute/diskEncryptionSets` | `des` | 1 - 80 |
| Compute and Web | Functionapp | `Microsoft.Web/sites` | `func-` | 2 - 60 |
| Compute and Web | Gallery | `Microsoft.Compute/galleries` | `gal` | 1 - 80 |
| Compute and Web | Manageddisk(OS) | `Microsoft.Compute/disks` | `osdisk` | 1 - 80 |
| Compute and Web | Manageddisk(data) | `Microsoft.Compute/disks` | `disk` | 1 - 80 |
| Compute and Web | NotificationHubs | `Microsoft.NotificationHubs/namespaces/notificationHubs` | `ntf-` | 1 - 260 |
| Compute and Web | NotificationHubsnamespace | `Microsoft.NotificationHubs/namespaces` | `ntfns-` | 1 - 260 |
| Compute and Web | Snapshot | `Microsoft.Compute/snapshots` | `snap-` | 1 - 80 |
| Compute and Web | Staticwebapp | `Microsoft.Web/staticSites` | `stapp-` | 2 - 60 |
| Compute and Web | Virtualmachine | `Microsoft.Compute/virtualMachines` | `vm` | 1 - 64 |
| Compute and Web | Virtualmachinescaleset | `Microsoft.Compute/virtualMachineScaleSets` | `vmss-` | 1 - 64 |
| Compute and Web | VMstorageaccount | `Microsoft.Storage/storageAccounts` | `stvm` | 3 - 34 |
| Compute and Web | Webapp | `Microsoft.Web/sites` | `app-` | 2 - 60 |
| Containers | AKScluster | `Microsoft.ContainerService/managedClusters` | `aks-` | 1 - 63 |
| Containers | Containerregistry | `Microsoft.ContainerRegistry/registries` | `cr` | 5 - 50 |
| Containers | Containerinstance | `Microsoft.ContainerInstance/containerGroups` | `ci` | 1 - 63 |
| Containers | ServiceFabriccluster | `Microsoft.ServiceFabric/clusters` | `sf-` | 4 - 23 |
| Databases | AzureCosmosDBdatabase | `Microsoft.DocumentDB/databaseAccounts/sqlDatabases` | `cosmos-` | 3 - 44 |
| Databases | AzureCacheforRedisinstance | `Microsoft.Cache/Redis` | `redis-` | 1 - 63 |
| Databases | AzureSQLDatabaseserver | `Microsoft.Sql/servers` | `sql-` | 1 - 128 |
| Databases | AzureSQLdatabase | `Microsoft.Sql/servers/databases` | `sqldb-` | 1 - 128 |
| Databases | AzureSynapseAnalytics | `Microsoft.Synapse/workspaces` | `syn` | 1 - 50 |
| Databases | AzureSynapseAnalyticsWorkspaces | `Microsoft.Synapse/workspaces` | `synw` | 1 - 50 |
| Databases | AzureSynapseAnalyticsSQLDedicatedPool | `Microsoft.Synapse/workspaces/sqlPools` | `syndp` | 1 - 60 |
| Databases | AzureSynapseAnalyticsSparkPool | `Microsoft.Synapse/workspaces/sqlPools` | `synsp` | 1- 60 |
| Databases | MySQLdatabase | `Microsoft.DBforMySQL/servers` | `mysql-` | 1 - 63 |
| Databases | PostgreSQLdatabase | `Microsoft.DBforPostgreSQL/servers` | `psql-` | 1 - 63 |
| Databases | SQLServerStretchDatabase | `Microsoft.Sql/servers/databases` | `sqlstrdb-` | 1 - 128 |
| Databases | SQLManagedInstance | `Microsoft.Sql/managedInstances` | `sqlmi-` | 1 - 63 |
| Storage | Storageaccount | `Microsoft.Storage/storageAccounts` | `st` | 3 - 24 |
| Storage | AzureStorSimple | `Microsoft.StorSimple/managers` | `ssimp` | 2 - 50 |
| AI and Machine Learning | AzureCognitiveSearch | `Microsoft.Search/searchServices` | `srch-` | 2 - 64 |
| AI and Machine Learning | AzureCognitiveServices | `Microsoft.CognitiveServices/accounts` | `cog-` | 2 - 64 |
| AI and Machine Learning | AzureMachineLearningworkspace | `Microsoft.MachineLearningServices/workspaces` | `mlw-` | 2 - 16 |
| Analytics and IoT | AzureAnalysisServicesserver | `Microsoft.AnalysisServices/servers` | `as` | 3 - 63 |
| Analytics and IoT | AzureDatabricksworkspace | `Microsoft.Databricks/workspaces` | `dbw-` | 3 - 64 |
| Analytics and IoT | AzureStreamAnalytics | `Microsoft.StreamAnalytics/cluster` | `asa-` | 3 - 63 |
| Analytics and IoT | AzureDataExplorercluster | `Microsoft.Kusto/clusters` | `dec` | 4 - 22 |
| Analytics and IoT | AzureDataExplorerclusterdatabase | `Microsoft.Kusto/clusters/databases` | `dedb` | 1 - 260 |
| Analytics and IoT | AzureDataFactory | `Microsoft.DataFactory/factories` | `adf-` | 3 - 63 |
| Analytics and IoT | DataLakeStoreaccount | `Microsoft.DataLakeStore/accounts` | `dls` | 3 - 24 |
| Analytics and IoT | DataLakeAnalyticsaccount | `Microsoft.DataLakeAnalytics/accounts` | `dla` | 3 - 24 |
| Analytics and IoT | EventHubsnamespace | `Microsoft.EventHub/namespaces` | `evhns-` | 6 - 50 |
| Analytics and IoT | Eventhub | `Microsoft.EventHub/namespaces/eventHubs` | `evh-` | 6 - 50 |
| Analytics and IoT | EventGriddomain | `Microsoft.EventGrid/domains` | `evgd-` | 3 - 50 |
| Analytics and IoT | EventGridsubscriptions | `Microsoft.EventGrid/eventSubscriptions` | `evgs-` | 3 - 64 |
| Analytics and IoT | EventGridtopic | `Microsoft.EventGrid/domains/topics` | `evgt-` | 3 - 50 |
| Analytics and IoT | HDInsight-Hadoopcluster | `Microsoft.HDInsight/clusters` | `hadoop-` | 3 - 59 |
| Analytics and IoT | HDInsight-HBasecluster | `Microsoft.HDInsight/clusters` | `hbase-` | 3 - 59 |
| Analytics and IoT | HDInsight-Kafkacluster | `Microsoft.HDInsight/clusters` | `kafka-` | 3 - 59 |
| Analytics and IoT | HDInsight-Sparkcluster | `Microsoft.HDInsight/clusters` | `spark-` | 3 - 59 |
| Analytics and IoT | HDInsight-Stormcluster | `Microsoft.HDInsight/clusters` | `storm-` | 3 - 59 |
| Analytics and IoT | HDInsight-MLServicescluster | `Microsoft.HDInsight/clusters` | `mls-` | 3 - 59 |
| Analytics and IoT | IoThub | `Microsoft.Devices/IotHubs` | `iot-` | 3 - 50 |
| Analytics and IoT | Provisioningservices | `Microsoft.Devices/provisioningServices` | `provs-` | 3 - 64 |
| Analytics and IoT | Provisioningservicescertificate | `Microsoft.Devices/provisioningServices/certificates` | `pcert-` | 1 - 64 |
| Analytics and IoT | PowerBIEmbedded | `Microsoft.PowerBIDedicated/capacities` | `pbi-` | 3 - 63 |
| Analytics and IoT | TimeSeriesInsightsenvironment | `Microsoft.TimeSeriesInsights/environments` | `tsi-` | 1 -90 |
| Developer Tools | AppConfigurationstore | `Microsoft.AppConfiguration/configurationStores` | `appcs-` | 5 - 50 |
| Developer Tools | SignalR | `Microsoft.SignalRService/SignalR` | `sigr` | 3 - 63 |
| Integration | Integrationaccount | `Microsoft.Logic/integrationAccounts` | `ia-` | 1 - 80 |
| Integration | Logicapps | `Microsoft.Logic/workflows` | `logic-` | 1 - 43 |
| Integration | ServiceBus | `Microsoft.ServiceBus/namespaces` | `sb-` | 6 - 50 |
| Integration | ServiceBusqueue | `Microsoft.ServiceBus/namespaces/queues` | `sbq-` | 1 - 260 |
| Integration | ServiceBustopic | `Microsoft.ServiceBus/namespaces/topics` | `sbt-` | 1 - 260 |
| Management and Governance | Automationaccount | `Microsoft.Automation/automationAccounts` | `aa-` | 6 - 50 |
| Management and Governance | ApplicationInsights | `Microsoft.Insights/components` | `appi-` | 1 - 260 |
| Management and Governance | AzureMonitoractiongroup | `Microsoft.Insights/actionGroups` | `ag-` | 1 - 260 |
| Management and Governance | AzurePurviewinstance | `Microsoft.Purview/accounts` | `pview-` | 6 - 50 |
| Management and Governance | Blueprint | `Microsoft.Blueprint/blueprints` | `bp-` | 1 - 90 |
| Management and Governance | Blueprintassignment | `Microsoft.Blueprint/blueprints/artifacts` | `bpa-` | 1 - 90 |
| Management and Governance | Keyvault | `Microsoft.KeyVault/vaults` | `kv-` | 3 - 24 |
| Management and Governance | LogAnalyticsworkspace | `Microsoft.OperationalInsights/workspaces` | `log-` | 4 - 63 |

## Refrences  
[Microsoft Azure Resource Abbreviations](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/resource-abbreviations)

[Microsoft Azure Resource Name Rules](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/resource-name-rules)
