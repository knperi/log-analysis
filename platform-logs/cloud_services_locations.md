---

copyright:
  years:  2018, 2022
lastupdated: "2022-06-01"

keywords: IBM, Log Analysis, logging, services

subcollection: log-analysis


---

{{site.data.keyword.attribute-definition-list}}


# Cloud services by location
{: #cloud_services_locations}

List of locations where {{site.data.keyword.cloud_notm}} services are enabled to send logs to {{site.data.keyword.la_full}}. You monitor these logs that you monitor through the {{site.data.keyword.la_short}} instance that is configured to receive platform services logs. [Learn more about enabling service platform logs](/docs/log-analysis?topic=log-analysis-config_svc_logs).
{: shortdesc}

## Cloud Foundry
{: #cs_locations_platform_cfapps}

The following table shows the locations where automatic collection of Cloud Foundry (CF) logs is enabled. You can monitor these logs through the {{site.data.keyword.la_full_notm}}  instance that is configured with the **service platform logs** in the same location where the CF resource is available.

| Service                                                       | `Dallas (us-south)` |
|---------------------------------------------------------------|--------------------|
| Cloud Foundry (CF)                                            | ![Checkmark icon](../images/checkmark-icon.svg)            |
{: caption="Table 1. Cloud Foundry in America" caption-side="top"}
{: #cs-cfapps-table-1}
{: tab-title="America"}
{: tab-group="cs_cfapps"}
{: class="simple-tab-table"}
{: row-headers}

| Service                                                       | `Tokyo (jp-tok)`                                  | `Sydney (au-syd)` |
|---------------------------------------------------------------|-------------------------------------------------|------------------|
| Cloud Foundry (CF)                                            | ![Checkmark icon](../images/checkmark-icon.svg) | ![Checkmark icon](../images/checkmark-icon.svg) |
{: caption="Table 1. Cloud Foundry in Asia Pacific" caption-side="top"}
{: #cs-cfapps-table-2}
{: tab-title="Asia Pacific"}
{: tab-group="cs_cfapps"}
{: class="simple-tab-table"}
{: row-headers}

| Service                                                       | `Frankfurt (eu-de)` | `London (eu-gb)` |
|---------------------------------------------------------------|-------------------|----------------|
| Cloud Foundry (CF)                                            | ![Checkmark icon](../images/checkmark-icon.svg) | ![Checkmark icon](../images/checkmark-icon.svg)|
{: caption="Table 1. Cloud Foundry in Europe" caption-side="top"}
{: #cs-cfapps-table-3}
{: tab-title="Europe"}
{: tab-group="cs_cfapps"}
{: class="simple-tab-table"}
{: row-headers}

## Compute serverless services
{: #cloud_services_locations_serverless}

| Service                                        | `Dallas (us-south)` | `Washington (us-east)`               |
|------------------------------------------------|---------------------|--------------------------------------|
| {{site.data.keyword.openwhisk_short}}          | ![Checkmark icon](../images/checkmark-icon.svg) | ![Checkmark icon](../images/checkmark-icon.svg) |   
| {{site.data.keyword.codeengineshort}}          | ![Checkmark icon](../images/checkmark-icon.svg) | |       
{: caption="Table 2. Compute serverless services integration in America locations" caption-side="top"}
{: #cs_comp-table-1}
{: tab-title="America"}
{: tab-group="cs_comp"}
{: class="simple-tab-table"}
{: row-headers}

| Service                                        | `Tokyo (jp-tok)` |`Sydney (au-syd)`           |
|------------------------------------------------|------------------|----------------------------|
| {{site.data.keyword.openwhisk_short}}          | ![Checkmark icon](../images/checkmark-icon.svg) |   |
| {{site.data.keyword.codeengineshort}}          | ![Checkmark icon](../images/checkmark-icon.svg) |   |
{: caption="Table 2. Compute serverless services integration in AP locations" caption-side="top"}
{: #cs_comp-table-2}
{: tab-title="Asia Pacific"}
{: tab-group="cs_comp"}
{: class="simple-tab-table"}
{: row-headers}

| Service                                                       |`Frankfurt (eu-de)`  | `London (eu-gb)` |
|---------------------------------------------------------------|---------------------|------------------|
| {{site.data.keyword.openwhisk_short}}          | ![Checkmark icon](../images/checkmark-icon.svg) | ![Checkmark icon](../images/checkmark-icon.svg) |
| {{site.data.keyword.codeengineshort}}          | ![Checkmark icon](../images/checkmark-icon.svg) | |
{: caption="Table 2. Compute serverless services integration in Europe locations" caption-side="top"}
{: #cs_comp-table-3}
{: tab-title="Europe"}
{: tab-group="cs_comp"}
{: class="simple-tab-table"}
{: row-headers}

## Container services
{: #cs_locations_container}

{{site.data.keyword.registrylong_notm}}
:   {{site.data.keyword.registrylong_notm}} generates platform services logs that are displayed in your logging instances. For informataion about the locations where the automatic collection of {{site.data.keyword.registryshort_notm}} service logs is enabled, see [Analyzing logs for {{site.data.keyword.registryshort_notm}}](/docs/Registry?topic=Registry-registry_logs#registry_logs_locations).

{{site.data.keyword.containerlong_notm}}
:   You can choose the logging instance where you want to collect {{site.data.keyword.containerlong_notm}} service logs.

{{site.data.keyword.satellitelong_notm}}
:   You can monitor {{site.data.keyword.satellitelong}} service logs through the logging instance that is configured with **service platform logs** in the same region that your {{site.data.keyword.satelliteshort}} location is managed from.

{{site.data.keyword.openshiftlong_notm}}
:   You can choose the logging instance where you want to collect {{site.data.keyword.openshiftlong}} service logs.

## Database services
{: #cs_locations_database}

The following tables list the locations where automatic collection of database service logs is enabled. You can monitor logs through the Log Analysis instance that is available in the same location as your database resources, if you enable 1 instance in this location to host service platform logs. For locations where you can provision a service instance but the {{site.data.keyword.la_full_notm}} service is not available, specific detail about the location where you can monitor those logs is provided in each case.

| Service                                                         | `Dallas (us-south)` | `Washington (us-east)`  |
|-----------------------------------------------------------------|-------------------|-------------------|
| {{site.data.keyword.cloudant_short_notm}}                       | ![Checkmark icon](../images/checkmark-icon.svg) | ![Checkmark icon](../images/checkmark-icon.svg)  |
| {{site.data.keyword.databases-for-enterprisedb_full_notm}}      | ![Checkmark icon](../images/checkmark-icon.svg) | ![Checkmark icon](../images/checkmark-icon.svg) |
| {{site.data.keyword.databases-for-cassandra_full_notm}}         | ![Checkmark icon](../images/checkmark-icon.svg) | ![Checkmark icon](../images/checkmark-icon.svg) |
| {{site.data.keyword.databases-for-elasticsearch_full_notm}}     | ![Checkmark icon](../images/checkmark-icon.svg) | ![Checkmark icon](../images/checkmark-icon.svg) |
| {{site.data.keyword.databases-for-etcd_full_notm}}              | ![Checkmark icon](../images/checkmark-icon.svg) | ![Checkmark icon](../images/checkmark-icon.svg) |
| {{site.data.keyword.databases-for-mongodb_full_notm}}           | ![Checkmark icon](../images/checkmark-icon.svg) | ![Checkmark icon](../images/checkmark-icon.svg) |
| {{site.data.keyword.databases-for-postgresql_full_notm}}        | ![Checkmark icon](../images/checkmark-icon.svg) | ![Checkmark icon](../images/checkmark-icon.svg) |
| {{site.data.keyword.messages-for-rabbitmq_full_notm}}           | ![Checkmark icon](../images/checkmark-icon.svg) | ![Checkmark icon](../images/checkmark-icon.svg) |
| {{site.data.keyword.databases-for-redis_full_notm}}             | ![Checkmark icon](../images/checkmark-icon.svg) | ![Checkmark icon](../images/checkmark-icon.svg) |
| {{site.data.keyword.cloud_notm}} {{site.data.keyword.ihsdbaas_mongodb_full}}     | ![Checkmark icon](../images/checkmark-icon.svg)             | ![Checkmark icon](../images/checkmark-icon.svg) |
| {{site.data.keyword.cloud_notm}} {{site.data.keyword.ihsdbaas_postgresql_full}}      | ![Checkmark icon](../images/checkmark-icon.svg)        | ![Checkmark icon](../images/checkmark-icon.svg) |
{: caption="Table 4. Database services" caption-side="top"}
{: #cs-dbs-table-1}
{: tab-title="America"}
{: tab-group="cs_dbs"}
{: class="simple-tab-table"}
{: row-headers}

| Service                                                         | `Tokyo (jp-tok)`   |`Sydney (au-syd)` | `Seoul 01 (seo01)`       | `Chennai 01 (che01)`     |`Seoul (kr-seo)` | 
|-----------------------------------------------------------------|--------------------|------------------|--------------------------|--------------------------|------------------|
| {{site.data.keyword.cloudant_short_notm}}                       | ![Checkmark icon](../images/checkmark-icon.svg) | ![Checkmark icon](../images/checkmark-icon.svg) |     | ![Checkmark icon](../images/checkmark-icon.svg) | ![Checkmark icon](../images/checkmark-icon.svg)  |
| {{site.data.keyword.databases-for-enterprisedb_full_notm}}      | ![Checkmark icon](../images/checkmark-icon.svg) |![Checkmark icon](../images/checkmark-icon.svg) | `Logs are available through the Tokyo instance` | ![Checkmark icon](../images/checkmark-icon.svg) |             | 
| {{site.data.keyword.databases-for-cassandra_full_notm}}         | ![Checkmark icon](../images/checkmark-icon.svg) |![Checkmark icon](../images/checkmark-icon.svg) | `Logs are available through the Tokyo instance` | ![Checkmark icon](../images/checkmark-icon.svg) |             |
| {{site.data.keyword.databases-for-elasticsearch_full_notm}}     | ![Checkmark icon](../images/checkmark-icon.svg) | ![Checkmark icon](../images/checkmark-icon.svg) | `Logs are available through the Log Analysis Tokyo instance` | ![Checkmark icon](../images/checkmark-icon.svg) |                      |
| {{site.data.keyword.databases-for-etcd_full_notm}}              | ![Checkmark icon](../images/checkmark-icon.svg) | ![Checkmark icon](../images/checkmark-icon.svg)| `Logs are available through the Log Analysis Tokyo instance` | ![Checkmark icon](../images/checkmark-icon.svg) |                      |
| {{site.data.keyword.databases-for-mongodb_full_notm}}           | ![Checkmark icon](../images/checkmark-icon.svg)  | ![Checkmark icon](../images/checkmark-icon.svg) | `Logs are available through the Log Analysis Tokyo instance` | ![Checkmark icon](../images/checkmark-icon.svg) |                      |
| {{site.data.keyword.databases-for-postgresql_full_notm}}        | ![Checkmark icon](../images/checkmark-icon.svg)  | ![Checkmark icon](../images/checkmark-icon.svg) | `Logs are available through the Log Analysis Tokyo instance` | ![Checkmark icon](../images/checkmark-icon.svg) |                      |
| {{site.data.keyword.messages-for-rabbitmq_full_notm}}           | ![Checkmark icon](../images/checkmark-icon.svg)  | ![Checkmark icon](../images/checkmark-icon.svg) | `Logs are available through the Log Analysis Tokyo instance` | ![Checkmark icon](../images/checkmark-icon.svg) |                      |
| {{site.data.keyword.databases-for-redis_full_notm}}             | ![Checkmark icon](../images/checkmark-icon.svg)  | ![Checkmark icon](../images/checkmark-icon.svg) | `Logs are available through the Log Analysis Tokyo instance` | ![Checkmark icon](../images/checkmark-icon.svg) |                      |
| {{site.data.keyword.cloud_notm}} {{site.data.keyword.ihsdbaas_mongodb_full}}             |    | `Logs are available through the Log Analysis Dallas instance`        |   |   |    |
| {{site.data.keyword.cloud_notm}} {{site.data.keyword.ihsdbaas_postgresql_full}}     |    | `Logs are available through the Log Analysis Dallas instance`        |   |   |   |
{: caption="Table 4. Database services" caption-side="top"}
{: #cs-dbs-table-2}
{: tab-title="Asia Pacific"}
{: tab-group="cs_dbs"}
{: class="simple-tab-table"}
{: row-headers}

| Service                                                       |`Frankfurt (eu-de)`  | `London (eu-gb)` | `Oslo 01 (osl01)`         |
|---------------------------------------------------------------|-------------------|----------------|--------------------------|
| {{site.data.keyword.cloudant_short_notm}}                     | ![Checkmark icon](../images/checkmark-icon.svg) | ![Checkmark icon](../images/checkmark-icon.svg) |                      |
| {{site.data.keyword.databases-for-elasticsearch_full_notm}}   | ![Checkmark icon](../images/checkmark-icon.svg)| ![Checkmark icon](../images/checkmark-icon.svg)          | `Logs are available through the Log Analysis London instance` |
| {{site.data.keyword.databases-for-etcd_full_notm}}            | ![Checkmark icon](../images/checkmark-icon.svg)| ![Checkmark icon](../images/checkmark-icon.svg)          | `Logs are available through the Log Analysis London instance` |
| {{site.data.keyword.databases-for-mongodb_full_notm}}         | ![Checkmark icon](../images/checkmark-icon.svg)| ![Checkmark icon](../images/checkmark-icon.svg)          | `Logs are available through the Log Analysis London instance` |
| {{site.data.keyword.databases-for-postgresql_full_notm}}      | ![Checkmark icon](../images/checkmark-icon.svg) | ![Checkmark icon](../images/checkmark-icon.svg)          | `Logs are available through the Log Analysis London instance` |
| {{site.data.keyword.messages-for-rabbitmq_full_notm}}         | ![Checkmark icon](../images/checkmark-icon.svg)| ![Checkmark icon](../images/checkmark-icon.svg)          | `Logs are available through the Log Analysis London instance` |
| {{site.data.keyword.databases-for-redis_full_notm}}           | ![Checkmark icon](../images/checkmark-icon.svg)| ![Checkmark icon](../images/checkmark-icon.svg)          | `Logs are available through the Log Analysis London instance` |
| {{site.data.keyword.cloud_notm}} {{site.data.keyword.ihsdbaas_mongodb_full}}           | ![Checkmark icon](../images/checkmark-icon.svg)              |           |        |
| {{site.data.keyword.cloud_notm}} {{site.data.keyword.ihsdbaas_postgresql_full}}           | ![Checkmark icon](../images/checkmark-icon.svg)              |           |        |
{: caption="Table 4. Database services" caption-side="top"}
{: #cs-dbs-table-3}
{: tab-title="Europe"}
{: tab-group="cs_dbs"}
{: class="simple-tab-table"}
{: row-headers}


## Developer tools
{: #cs_locations_developer_tools}

The following table shows the locations where automatic collection of developer tools logs are enabled. You can monitor these logs through the {{site.data.keyword.la_full_notm}} instance that is configured with the **developer tools logs** in the same location where the developer tools resource is available.

| Service                              | `Dallas (us-south)`                             |
|--------------------------------------|-------------------------------------------------|
| {{site.data.keyword.en_full}}        | ![Checkmark icon](../images/checkmark-icon.svg) |
{: caption="Table 4. Developer tools in America" caption-side="top"}
{: #cs-devtools-table-4}
{: tab-title="America"}
{: tab-group="cs_devtools"}
{: class="simple-tab-table"}
{: row-headers}

| Service                              | `Sydney (au-syd)`                               |
|--------------------------------------|-------------------------------------------------|
| {{site.data.keyword.en_full}}        | ![Checkmark icon](../images/checkmark-icon.svg) |
{: caption="Table 4. Developer tools in Asia Pacific" caption-side="top"}
{: #cs-devtools-table-5}
{: tab-title="Asia Pacific"}
{: tab-group="cs_devtools"}
{: class="simple-tab-table"}
{: row-headers}

| Service                               | `Frankfurt (eu-de)`                             | `London (eu-gb)`                                |
|---------------------------------------|-------------------------------------------------|-------------------------------------------------|
| {{site.data.keyword.en_full}}         | ![Checkmark icon](../images/checkmark-icon.svg) | ![Checkmark icon](../images/checkmark-icon.svg) |
{: caption="Table 4. Developer tools in Europe" caption-side="top"}
{: #cs-devtools-table-6}
{: tab-title="Europe"}
{: tab-group="cs_devtools"}
{: class="simple-tab-table"}
{: row-headers}ssss

## Integration services
{: #cs_locations_integration}

| Service                                         | `Dallas (us-south)`                          | `Washington (us-east)`            |
|-------------------------------------------------|----------------------------------------------|-----------------------------------|
| {{site.data.keyword.appconservicefull}}         | ![Checkmark icon](../images/checkmark-icon.svg) |                              |
| {{site.data.keyword.mq_short}}                  | ![Checkmark icon](../images/checkmark-icon.svg) | ![Checkmark icon](../images/checkmark-icon.svg) |            
{: caption="Table 5. Integration services" caption-side="top"}
{: #cs-int-table-10}
{: tab-title="America"}
{: tab-group="cs_int"}
{: class="simple-tab-table"}
{: row-headers}

| Service                                                         | `Tokyo (jp-tok)` |`Sydney (au-syd)`           |
|-----------------------------------------------------------------|----------------|---------------------------|
| {{site.data.keyword.appconservicefull}}                      |    | ![Checkmark icon](../images/checkmark-icon.svg)|
| {{site.data.keyword.mq_short}}                               |     | ![Checkmark icon](../images/checkmark-icon.svg)|
{: caption="Table 5. Integration services" caption-side="top"}
{: #cs-int-table-11}
{: tab-title="Asia Pacific"}
{: tab-group="cs_int"}
{: class="simple-tab-table"}
{: row-headers}

| Service                                                       |`Frankfurt (eu-de)`  | `London (eu-gb)` |
|---------------------------------------------------------------|-------------------|----------------|
| {{site.data.keyword.appconservicefull}}                    |               | ![Checkmark icon](../images/checkmark-icon.svg)|
| {{site.data.keyword.mq_short}}                  | ![Checkmark icon](../images/checkmark-icon.svg) | ![Checkmark icon](../images/checkmark-icon.svg) |
{: caption="Table 5. Integration services" caption-side="top"}
{: #cs-int-table-12}
{: tab-title="Europe"}
{: tab-group="cs_int"}
{: class="simple-tab-table"}
{: row-headers}



## Networking services
{: #cs_locations_networking}

| Service                                                | `Dallas (us-south)` | `Washington (us-east)`                   |
|--------------------------------------------------------|---------------------|--------------------------------------|
| {{site.data.keyword.loadbalancer_full}} `[1]`          | ![Checkmark icon](../images/checkmark-icon.svg)             |                                 |
| Dedicated host                                         | ![Checkmark icon](../images/checkmark-icon.svg) | ![Checkmark icon](../images/checkmark-icon.svg) |
| Flow Log Collector                                     | ![Checkmark icon](../images/checkmark-icon.svg) | ![Checkmark icon](../images/checkmark-icon.svg) |
| VPN                                                    | ![Checkmark icon](../images/checkmark-icon.svg) | `Logs are available through the logging US-South instance` |
{: caption="Table 6. Networking services" caption-side="top"}
{: #cs-net-table-13}
{: tab-title="America"}
{: tab-group="cs_net"}
{: class="simple-tab-table"}
{: row-headers}

| Service                                                         | `Tokyo (jp-tok)` |`Sydney (au-syd)`           |
|-----------------------------------------------------------------|----------------|---------------------------|
| {{site.data.keyword.loadbalancer_full}} `[1]`                  |    |  |
| Dedicated host                         | ![Checkmark icon](../images/checkmark-icon.svg) | ![Checkmark icon](../images/checkmark-icon.svg) |
| Flow Log Collector                     | ![Checkmark icon](../images/checkmark-icon.svg) | ![Checkmark icon](../images/checkmark-icon.svg) |
| VPN                                              | ![Checkmark icon](../images/checkmark-icon.svg)             | ![Checkmark icon](../images/checkmark-icon.svg) |
{: caption="Table 6. Networking services" caption-side="top"}
{: #cs-net-table-14}
{: tab-title="Asia Pacific"}
{: tab-group="cs_net"}
{: class="simple-tab-table"}
{: row-headers}

| Service                                                       |`Frankfurt (eu-de)`  | `London (eu-gb)` |
|---------------------------------------------------------------|-------------------|----------------|
| {{site.data.keyword.loadbalancer_full}} `[1]`               |               |  |
| Dedicated host                        | ![Checkmark icon](../images/checkmark-icon.svg) | ![Checkmark icon](../images/checkmark-icon.svg) |
| Flow Log Collector                     | ![Checkmark icon](../images/checkmark-icon.svg) | ![Checkmark icon](../images/checkmark-icon.svg) |
| VPN                                                           | ![Checkmark icon](../images/checkmark-icon.svg)  | ![Checkmark icon](../images/checkmark-icon.svg) |
{: caption="Table 6. Networking services" caption-side="top"}
{: #cs-net-table-15}
{: tab-title="Europe"}
{: tab-group="cs_net"}
{: class="simple-tab-table"}
{: row-headers}

`[1]` Data logs are only sent if your Softlayer and {{site.data.keyword.cloud}} accounts are linked.

## Security services
{: #cs_locations_security}

The following tables list the locations where automatic collection of security service logs is enabled. You can monitor logs through the Log Analysis instance that is available in the same location as your security resources, if you enable 1 instance in this location to host service platform logs. For locations where you can provision a service instance but the {{site.data.keyword.la_full_notm}} service is not available, specific detail about the location where you can monitor those logs is provided in each case.


| Service                                                         | `Dallas (us-south)` | `Washington (us-east)`                   |
|-----------------------------------------------------------------|---------------------|--------------------------------------|
| {{site.data.keyword.cloudcerts_full_notm}}                      | ![Checkmark icon](../images/checkmark-icon.svg)   |                                 |   
| {{site.data.keyword.secrets-manager_full}}  | ![Checkmark icon](../images/checkmark-icon.svg) |         
{: caption="Table 7. Security services" caption-side="top"}
{: #cs-sec-table-16}
{: tab-title="America"}
{: tab-group="cs_sec"}
{: class="simple-tab-table"}
{: row-headers}

| Service                                                         | `Tokyo (jp-tok)` |`Sydney (au-syd)`           |
|-----------------------------------------------------------------|----------------|---------------------------|
| {{site.data.keyword.cloudcerts_full_notm}}                      | ![Checkmark icon](../images/checkmark-icon.svg)          | ![Checkmark icon](../images/checkmark-icon.svg) |
| {{site.data.keyword.secrets-manager_full}}  | ![Checkmark icon](../images/checkmark-icon.svg)  | ![Checkmark icon](../images/checkmark-icon.svg) |
{: caption="Table 7. Security services" caption-side="top"}
{: #cs-sec-table-17}
{: tab-title="Asia Pacific"}
{: tab-group="cs_sec"}
{: class="simple-tab-table"}
{: row-headers}

| Service                                                       |`Frankfurt (eu-de)`  | `London (eu-gb)` |
|---------------------------------------------------------------|-------------------|----------------|
| {{site.data.keyword.cloudcerts_full_notm}}                    | ![Checkmark icon](../images/checkmark-icon.svg)             | ![Checkmark icon](../images/checkmark-icon.svg) |
| {{site.data.keyword.secrets-manager_full}}  | ![Checkmark icon](../images/checkmark-icon.svg)  | ![Checkmark icon](../images/checkmark-icon.svg) |
{: caption="Table 7. Security services" caption-side="top"}
{: #cs-sec-table-18}
{: tab-title="Europe"}
{: tab-group="cs_sec"}
{: class="simple-tab-table"}
{: row-headers}




## Watson AI
{: #cloud_services_locations_watson_ai}


| Service                                                         | `Dallas (us-south)` | `Washington (us-east)`                   |
|-----------------------------------------------------------------|---------------------|--------------------------------------|
| {{site.data.keyword.iva_full_notm}}                                  | ![Checkmark icon](../images/checkmark-icon.svg)             | `Logs are available through the Log Analysis Dallas instance` |
{: caption="Table 8. Watson AI in America's locations" caption-side="top"}
{: #cs-wat-table-22}
{: tab-title="America"}
{: tab-group="cs_watsonai"}
{: class="simple-tab-table"}
{: row-headers}

| Service                                                         | `Tokyo (jp-tok)` |`Sydney (au-syd)`           |
|-----------------------------------------------------------------|----------------|---------------------------|
| {{site.data.keyword.iva_full_notm}}                                                |            |   |
{: caption="Table 8. Watson AI in AP locations" caption-side="top"}
{: #cs-wat-table-23}
{: tab-title="Asia Pacific"}
{: tab-group="cs_watsonai"}
{: class="simple-tab-table"}
{: row-headers}

| Service                                                       |`Frankfurt (eu-de)`  | `London (eu-gb)` |
|---------------------------------------------------------------|-------------------|----------------|
| {{site.data.keyword.iva_full_notm}}                           |  |    |
{: caption="Table 8. Watson AI in Europe locations" caption-side="top"}
{: #cs-wat-table-24}
{: tab-title="Europe"}
{: tab-group="cs_watsonai"}
{: class="simple-tab-table"}
{: row-headers}




