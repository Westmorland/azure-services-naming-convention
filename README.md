# Azure Services Naming Convention 

Defining and enforcing naming conventions for resources can help improve resource discovery, cost management, automation, and organisation of Azure resources.

## General

| Resource Type | Resource Namespace | Abbreviation | Length Restrictions |
| --- | --- | --- | --- |
| ManagedIdentity | `Microsoft.ManagedIdentity/userAssignedIdentities` | `id-` | 3 - 128 |
| Managementgroup | `Microsoft.Management/managementGroups` | `mg-` | ? |
| Policydefinition | `Microsoft.Authorization/policyDefinitions` | `policy-` | 1 - 64 |
| Resourcegroup | `Microsoft.Resources/resourceGroups` | `rg-` | 1 - 90 |

## Networking

| Resource Type | Resource Namespace | Abbreviation | Length Restrictions |
| --- | --- | --- | --- |
| Applicationgateway | `Microsoft.Network/applicationGateways` | `agw-` | 1 - 80 |
| Applicationsecuritygroup(ASG) | `Microsoft.Network/applicationSecurityGroups` | `asg-` | 1 - 80 |
| Bastion | `Microsoft.Network/bastionHosts` | `bas-` | 1 - 80 |
| CDNprofile | `Microsoft.Cdn/profiles` | `cdnp-` | 1 - 260 |
| CDNendpoint | `Microsoft.Cdn/profiles/endpoints` | `cdne-` | 1 - 50 |
| Connections | `Microsoft.Network/connections` | `con-` | 1 - 80 |
| DNS | `Microsoft.Network/dnsZones` | `dnsz-` | 1 - 63 |
| DNSzone | `Microsoft.Network/privateDnsZones` | `pdnsz-` | 1 - 63 |
| Firewall | `Microsoft.Network/azureFirewalls` | `afw-` | 1 - 80 |
| Firewallpolicy | `Microsoft.Network/firewallPolicies` | `afwp-` | 1 - 80 |
| ExpressRoutecircuit | `Microsoft.Network/expressRouteCircuits` | `erc-` | 1 - 80 |
| FrontDoorinstance | `Microsoft.Network/frontDoors` | `fd-` | 5 - 64 |
| FrontDoorfirewallpolicy | `Microsoft.Network/frontdoorWebApplicationFirewallPolicies` | `fdfp-` | 1 - 128 |
| Loadbalancer(internal) | `Microsoft.Network/loadBalancers` | `lbi-` | 1 - 80 |
| Loadbalancer(external) | `Microsoft.Network/loadBalancers` | `lbe-` | 1 - 80 |
| Loadbalancerrule | `Microsoft.Network/loadBalancers/inboundNatRules` | `rule-` | 1 - 80 |
| Localnetworkgateway | `Microsoft.Network/localNetworkGateways` | `lgw-` | 1 - 80 |
| NATgateway | `Microsoft.Network/natGateways` | `ng-` | 1 - 80 |
| Networkinterface(NIC) | `Microsoft.Network/networkInterfaces` | `nic-` | 1 - 80 |
| Networksecuritygroup(NSG) | `Microsoft.Network/networkSecurityGroups` | `nsg-` | 1 - 80 |
| Networksecuritygroup(NSG)securityrules | `Microsoft.Network/networkSecurityGroups/securityRules` | `nsgsr-` | 1 - 80 |
| NetworkWatcher | `Microsoft.Network/networkWatchers` | `nw-` | 1 - 80 |
| PrivateLink | `Microsoft.Network/privateLinkServices` | `pl-` | 1 - 80 |
| PublicIPaddress | `Microsoft.Network/publicIPAddresses` | `pip-` | 1- 80 |
| PublicIPaddressprefix | `Microsoft.Network/publicIPPrefixes` | `ippre-` | 1 - 80 |
| Routefilter | `Microsoft.Network/routeFilters` | `rf-` | 1 - 80 |
| Routetable | `Microsoft.Network/routeTables` | `rt-` | 1 - 80 |
| Serviceendpoint | `Microsoft.serviceEndPointPolicies` | `se-` | 1 - 80 |
| TrafficManagerprofile | `Microsoft.Network/trafficManagerProfiles` | `traf-` | 1 - 63 |
| Userdefinedroute(UDR) | `Microsoft.Network/routeTables/routes` | `udr-` | 1 - 80 |
| Virtualnetwork | `Microsoft.Network/virtualNetworks` | `vnet-` | 2 - 64 |
| Virtualnetworkpeering | `Microsoft.Network/virtualNetworks/virtualNetworkPeerings` | `peer-` | 1 - 80 |
| Virtualnetworksubnet | `Microsoft.Network/virtualNetworks/subnets` | `snet-` | 1 - 80 |
| VirtualWAN | `Microsoft.Network/virtualWans` | `vwan-` | 1 - 80 |
| VPNGateway | `Microsoft.Network/vpnGateways` | `vpng-` | 1 - 80 |
| VPNconnection | `Microsoft.Network/vpnGateways/vpnConnections` | `vcn-` | 1 - 80 |
| VPNsite | `Microsoft.Network/vpnGateways/vpnSites` | `vst-` | 1 - 80 |
| Virtualnetworkgateway | `Microsoft.Network/virtualNetworkGateways` | `vgw-` | 1 - 80 |
| WebApplicationFirewall(WAF)policy | `Microsoft.Network/firewallPolicies` | `waf` | 1 - 80 |
| WebApplicationFirewall(WAF)policyrulegroup | `Microsoft.Network/firewallPolicies/ruleGroups` | `wafrg` | 1 - 80 |

## Compute and Web

| Resource Type | Resource Namespace | Abbreviation | Length Restrictions |
| --- | --- | --- | --- |
| AppServiceenvironment | `Microsoft.Web/sites` | `ase-` | 2 - 60 |
| AppServiceplan | `Microsoft.Web/serverFarms` | `plan-` | 1 - 40 |
| Availabilityset | `Microsoft.Compute/availabilitySets` | `avail-` | 1 - 80 |
| AzureArcenabledserver | `Microsoft.HybridCompute/machines` | `arcs-` | 1 - 15 |
| AzureArcenabledKubernetescluster | `Microsoft.Kubernetes/connectedClusters` | `arck` | 1 - 15 |
| Cloudservice | `Microsoft.Compute/cloudServices` | `cld-` | 1 - 15 |
| Diskencryptionset | `Microsoft.Compute/diskEncryptionSets` | `des` | 1 - 80 |
| Functionapp | `Microsoft.Web/sites` | `func-` | 2 - 60 |
| Gallery | `Microsoft.Compute/galleries` | `gal` | 1 - 80 |
| Manageddisk(OS) | `Microsoft.Compute/disks` | `osdisk` | 1 - 80 |
| Manageddisk(data) | `Microsoft.Compute/disks` | `disk` | 1 - 80 |
| NotificationHubs | `Microsoft.NotificationHubs/namespaces/notificationHubs` | `ntf-` | 1 - 260 |
| NotificationHubsnamespace | `Microsoft.NotificationHubs/namespaces` | `ntfns-` | 1 - 260 |
| Snapshot | `Microsoft.Compute/snapshots` | `snap-` | 1 - 80 |
| Staticwebapp | `Microsoft.Web/staticSites` | `stapp-` | 2 - 60 |
| Virtualmachine | `Microsoft.Compute/virtualMachines` | `vm` | 1 - 64 |
| Virtualmachinescaleset | `Microsoft.Compute/virtualMachineScaleSets` | `vmss-` | 1 - 64 |
| VMstorageaccount | `Microsoft.Storage/storageAccounts` | `stvm` | 3 - 34 |
| Webapp | `Microsoft.Web/sites` | `app-` | 2 - 60 |

## Containers

| Resource Type | Resource Namespace | Abbreviation | Length Restrictions |
| --- | --- | --- | --- |
| AKScluster | `Microsoft.ContainerService/managedClusters` | `aks-` | 1 - 63 |
| Containerregistry | `Microsoft.ContainerRegistry/registries` | `cr` | 5 - 50 |
| Containerinstance | `Microsoft.ContainerInstance/containerGroups` | `ci` | 1 - 63 |
| ServiceFabriccluster | `Microsoft.ServiceFabric/clusters` | `sf-` | 4 - 23 |

## Databases

| Resource Type | Resource Namespace | Abbreviation | Length Restrictions |
| --- | --- | --- | --- |
| AzureCosmosDBdatabase | `Microsoft.DocumentDB/databaseAccounts/sqlDatabases` | `cosmos-` | 3 - 44 |
| AzureCacheforRedisinstance | `Microsoft.Cache/Redis` | `redis-` | 1 - 63 |
| AzureSQLDatabaseserver | `Microsoft.Sql/servers` | `sql-` | 1 - 128 |
| AzureSQLdatabase | `Microsoft.Sql/servers/databases` | `sqldb-` | 1 - 128 |
| AzureSynapseAnalytics | `Microsoft.Synapse/workspaces` | `syn` | 1 - 50 |
| AzureSynapseAnalyticsWorkspaces | `Microsoft.Synapse/workspaces` | `synw` | 1 - 50 |
| AzureSynapseAnalyticsSQLDedicatedPool | `Microsoft.Synapse/workspaces/sqlPools` | `syndp` | 1 - 60 |
| AzureSynapseAnalyticsSparkPool | `Microsoft.Synapse/workspaces/sqlPools` | `synsp` | 1- 60 |
| MySQLdatabase | `Microsoft.DBforMySQL/servers` | `mysql-` | 1 - 63 |
| PostgreSQLdatabase | `Microsoft.DBforPostgreSQL/servers` | `psql-` | 1 - 63 |
| SQLServerStretchDatabase | `Microsoft.Sql/servers/databases` | `sqlstrdb-` | 1 - 128 |
| SQLManagedInstance | `Microsoft.Sql/managedInstances` | `sqlmi-` | 1 - 63 |

## Storage

| Resource Type | Resource Namespace | Abbreviation | Length Restrictions |
| --- | --- | --- | --- |
| Storageaccount | `Microsoft.Storage/storageAccounts` | `st` | 3 - 24 |
| AzureStorSimple | `Microsoft.StorSimple/managers` | `ssimp` | 2 - 50 |

## AI and Machine Learning

| Resource Type | Resource Namespace | Abbreviation | Length Restrictions |
| --- | --- | --- | --- |
| AzureCognitiveSearch | `Microsoft.Search/searchServices` | `srch-` | 2 - 64 |
| AzureCognitiveServices | `Microsoft.CognitiveServices/accounts` | `cog-` | 2 - 64 |
| AzureMachineLearningworkspace | `Microsoft.MachineLearningServices/workspaces` | `mlw-` | 2 - 16 |

## Analytics and IoT

| Resource Type | Resource Namespace | Abbreviation | Length Restrictions |
| --- | --- | --- | --- |
| AzureAnalysisServicesserver | `Microsoft.AnalysisServices/servers` | `as` | 3 - 63 |
| AzureDatabricksworkspace | `Microsoft.Databricks/workspaces` | `dbw-` | 3 - 64 |
| AzureStreamAnalytics | `Microsoft.StreamAnalytics/cluster` | `asa-` | 3 - 63 |
| AzureDataExplorercluster | `Microsoft.Kusto/clusters` | `dec` | 4 - 22 |
| AzureDataExplorerclusterdatabase | `Microsoft.Kusto/clusters/databases` | `dedb` | 1 - 260 |
| AzureDataFactory | `Microsoft.DataFactory/factories` | `adf-` | 3 - 63 |
| DataLakeStoreaccount | `Microsoft.DataLakeStore/accounts` | `dls` | 3 - 24 |
| DataLakeAnalyticsaccount | `Microsoft.DataLakeAnalytics/accounts` | `dla` | 3 - 24 |
| EventHubsnamespace | `Microsoft.EventHub/namespaces` | `evhns-` | 6 - 50 |
| Eventhub | `Microsoft.EventHub/namespaces/eventHubs` | `evh-` | 6 - 50 |
| EventGriddomain | `Microsoft.EventGrid/domains` | `evgd-` | 3 - 50 |
| EventGridsubscriptions | `Microsoft.EventGrid/eventSubscriptions` | `evgs-` | 3 - 64 |
| EventGridtopic | `Microsoft.EventGrid/domains/topics` | `evgt-` | 3 - 50 |
| HDInsight-Hadoopcluster | `Microsoft.HDInsight/clusters` | `hadoop-` | 3 - 59 |
| HDInsight-HBasecluster | `Microsoft.HDInsight/clusters` | `hbase-` | 3 - 59 |
| HDInsight-Kafkacluster | `Microsoft.HDInsight/clusters` | `kafka-` | 3 - 59 |
| HDInsight-Sparkcluster | `Microsoft.HDInsight/clusters` | `spark-` | 3 - 59 |
| HDInsight-Stormcluster | `Microsoft.HDInsight/clusters` | `storm-` | 3 - 59 |
| HDInsight-MLServicescluster | `Microsoft.HDInsight/clusters` | `mls-` | 3 - 59 |
| IoThub | `Microsoft.Devices/IotHubs` | `iot-` | 3 - 50 |
| Provisioningservices | `Microsoft.Devices/provisioningServices` | `provs-` | 3 - 64 |
| Provisioningservicescertificate | `Microsoft.Devices/provisioningServices/certificates` | `pcert-` | 1 - 64 |
| PowerBIEmbedded | `Microsoft.PowerBIDedicated/capacities` | `pbi-` | 3 - 63 |
| TimeSeriesInsightsenvironment | `Microsoft.TimeSeriesInsights/environments` | `tsi-` | 1 -90 |

## Developer Tools

| Resource Type | Resource Namespace | Abbreviation | Length Restrictions |
| --- | --- | --- | --- |
| AppConfigurationstore | `Microsoft.AppConfiguration/configurationStores` | `appcs-` | 5 - 50 |
| SignalR | `Microsoft.SignalRService/SignalR` | `sigr` | 3 - 63 |

## Integration

| Resource Type | Resource Namespace | Abbreviation | Length Restrictions |
| --- | --- | --- | --- |
| Integrationaccount | `Microsoft.Logic/integrationAccounts` | `ia-` | 1 - 80 |
| Logicapps | `Microsoft.Logic/workflows` | `logic-` | 1 - 43 |
| ServiceBus | `Microsoft.ServiceBus/namespaces` | `sb-` | 6 - 50 |
| ServiceBusqueue | `Microsoft.ServiceBus/namespaces/queues` | `sbq-` | 1 - 260 |
| ServiceBustopic | `Microsoft.ServiceBus/namespaces/topics` | `sbt-` | 1 - 260 |

## Management and Governance

| Resource Type | Resource Namespace | Abbreviation | Length Restrictions |
| --- | --- | --- | --- |
| Automationaccount | `Microsoft.Automation/automationAccounts` | `aa-` | 6 - 50 |
| ApplicationInsights | `Microsoft.Insights/components` | `appi-` | 1 - 260 |
| AzureMonitoractiongroup | `Microsoft.Insights/actionGroups` | `ag-` | 1 - 260 |
| AzurePurviewinstance | `Microsoft.Purview/accounts` | `pview-` | 6 - 50 |
| Blueprint | `Microsoft.Blueprint/blueprints` | `bp-` | 1 - 90 |
| Blueprintassignment | `Microsoft.Blueprint/blueprints/artifacts` | `bpa-` | 1 - 90 |
| Keyvault | `Microsoft.KeyVault/vaults` | `kv-` | 3 - 24 |
| LogAnalyticsworkspace | `Microsoft.OperationalInsights/workspaces` | `log-` | 4 - 63 |

## Refrences  
[Microsoft Azure Resource Abbreviations](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/resource-abbreviations)

[Microsoft Azure Resource Name Rules](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/resource-name-rules)
