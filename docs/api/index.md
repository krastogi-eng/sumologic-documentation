---
slug: /api
title: Sumo Logic APIs
sidebar_label: Getting Started
---

Use our Application Programming Interfaces (APIs) to interact with the Sumo Logic platform. To connect with other Sumo Logic users, post feedback, or ask a question, visit the [Sumo Logic Community Integrate APIs](https://support.sumologic.com/hc/en-us/community/topics/200263058-Applications-and-Integrations) Forum and [Sumo Dojo](http://slack.sumologic.com/).

This guide contains information about API authentication and the Sumo Logic endpoints to use for your API client.

## Documentation  

All of our APIs are developed with the [OpenAPI Specification](https://www.openapis.org/), unless otherwise stated. You can generate client libraries in many languages and explore automated testing.

The [Collector Management](https://help.sumologic.com/APIs/Collector-Management-API) and [Search Job APIs](https://help.sumologic.com/APIs/Search-Job-API) are not yet built with OpenAPI specifications. Therefore are not documented with the rest of the APIs. Instead, navigate to the respective API documentation for details.

<details><summary><strong>Sumo Logic Documentation URLs by topic (click to expand)</strong></summary>

#### Cloud SIEM

<table>
  <tr>
   <td>API
   </td>
   <td>Documentation URL
   </td>
  </tr>
  <tr>
   <td>Cloud SIEM Enterprise
   </td>
   <td><a href="https://api.sumologic.com/docs/sec">https://api.sumologic.com/docs/sec</a>
   </td>
  </tr>
</table>


#### Collectors and Sources

<table>
  <tr>
   <td>API
   </td>
   <td>Documentation URL
   </td>
  </tr>
  <tr>
   <td>Collector Management
   </td>
   <td><a href="https://help.sumologic.com/APIs/Collector-Management-API">https://help.sumologic.com/APIs/Coll...Management-API</a>
   </td>
  </tr>
</table>


#### Health Events

<table>
  <tr>
   <td>API
   </td>
   <td>Documentation URL
   </td>
  </tr>
  <tr>
   <td>Health Events
   </td>
   <td><a href="https://api.de.sumologic.com/docs/">https://api.sumologic.com/docs/#tag/healthEvents</a>
   </td>
  </tr>
</table>



#### Infrequent Data Tier

<table>
  <tr>
   <td>API
   </td>
   <td>Documentation URL
   </td>
  </tr>
  <tr>
   <td>Log Search Estimated Usage
   </td>
   <td><a href="https://api.sumologic.com/docs/#tag/logSearchesEstimatedUsage">https://api.sumologic.com/docs/#tag/...EstimatedUsage</a>
   </td>
  </tr>
</table>



#### Ingest Budgets

<table>
  <tr>
   <td>API
   </td>
   <td>Documentation URL
   </td>
  </tr>
  <tr>
   <td>Ingest Budgets
   </td>
   <td><a href="https://api.sumologic.com/docs/#tag/ingestBudgetManagementV1">https://api.sumologic.com/docs/#tag/...etManagementV1</a>
   </td>
  </tr>
  <tr>
   <td>Ingest Budgets V2
   </td>
   <td><a href="https://api.sumologic.com/docs/#tag/ingestBudgetManagementV2">https://api.sumologic.com/docs/#tag/...etManagementV2</a>
   </td>
  </tr>
</table>



#### Library

<table>
  <tr>
   <td>API
   </td>
   <td>Documentation URL
   </td>
  </tr>
  <tr>
   <td>Content
   </td>
   <td><a href="https://api.sumologic.com/docs/#tag/contentManagement">https://api.sumologic.com/docs/#tag/contentManagement</a>
   </td>
  </tr>
  <tr>
   <td>Dashboard (New)
   </td>
   <td><a href="https://api.sumologic.com/docs/#tag/dashboardManagement">https://api.sumologic.com/docs/#tag/...oardManagement</a>
   </td>
  </tr>
  <tr>
   <td>Folders
   </td>
   <td><a href="https://api.sumologic.com/docs/#tag/folderManagement">https://api.sumologic.com/docs/#tag/folderManagement</a>
   </td>
  </tr>
  <tr>
   <td>Lookup Table
   </td>
   <td><a href="https://api.sumologic.com/docs/#tag/lookupManagement">https://api.sumologic.com/docs/#tag/lookupManagement</a>
   </td>
  </tr>
  <tr>
   <td>Permissions
   </td>
   <td><a href="https://api.sumologic.com/docs/#tag/contentPermissions">https://api.sumologic.com/docs/#tag/...entPermissions</a>
   </td>
  </tr>
</table>


#### Log Search

<table>
  <tr>
   <td>API
   </td>
   <td>Documentation URL
   </td>
  </tr>
  <tr>
   <td>Search Job
   </td>
   <td><a href="https://api.de.sumologic.com/docs/">https://help.sumologic.com/APIs/Search-Job-API</a>
   </td>
  </tr>
</table>



#### Metrics

<table>
  <tr>
   <td>API
   </td>
   <td>Documentation URL
   </td>
  </tr>
  <tr>
   <td>Metrics Query
   </td>
   <td><a href="https://api.sumologic.com/docs/#tag/metricsQuery">https://api.sumologic.com/docs/#tag/metricsQuery</a>
   </td>
  </tr>
</table>



#### Monitors

<table>
  <tr>
   <td>API
   </td>
   <td>Documentation URL
   </td>
  </tr>
  <tr>
   <td>Monitors
   </td>
   <td><a href="https://api.de.sumologic.com/docs/">https://api.sumologic.com/docs/#tag/monitorsLibraryManagement</a>
   </td>
  </tr>
</table>



#### Security

<table>
  <tr>
   <td>API
   </td>
   <td>Documentation URL
   </td>
  </tr>
  <tr>
   <td>Access Keys
   </td>
   <td><a href="https://api.sumologic.com/docs/#tag/accessKeyManagement">https://api.sumologic.com/docs/#tag/...sKeyManagement</a>
   </td>
  </tr>
  <tr>
   <td>Account
   </td>
   <td><a href="https://api.sumologic.com/docs/#tag/accountManagement">https://api.sumologic.com/docs/#tag/accountManagement</a>
   </td>
  </tr>
  <tr>
   <td>Password Policy
   </td>
   <td><a href="https://api.sumologic.com/docs/#tag/passwordPolicy">https://api.sumologic.com/docs/#tag/passwordPolicy</a>
   </td>
  </tr>
  <tr>
   <td>Policies
   </td>
   <td><a href="https://api.sumologic.com/docs/#tag/policiesManagement">https://api.sumologic.com/docs/#tag/...ciesManagement</a>
   </td>
  </tr>
  <tr>
   <td>SAML
   </td>
   <td><a href="https://api.sumologic.com/docs/#tag/samlConfigurationManagement">https://api.sumologic.com/docs/#tag/...tionManagement</a>
   </td>
  </tr>
  <tr>
   <td>Service Allowlist
   </td>
   <td><a href="https://api.sumologic.com/docs/#tag/serviceAllowlistManagement">https://api.sumologic.com/docs/#tag/...listManagement</a>
   </td>
  </tr>
</table>


#### Settings

<table>
  <tr>
   <td>API
   </td>
   <td>Documentation URL
   </td>
  </tr>
  <tr>
   <td>Dynamic Parsing
   </td>
   <td><a href="https://api.de.sumologic.com/docs/">https://api.sumologic.com/docs/#tag/dynamicParsingRuleManagement</a>
   </td>
  </tr>
  <tr>
   <td>Fields
   </td>
   <td><a href="https://api.sumologic.com/docs/#tag/fieldManagementV1">https://api.sumologic.com/docs/#tag/fieldManagementV1</a>
   </td>
  </tr>
  <tr>
   <td>Field Extraction Rules
   </td>
   <td><a href="https://api.sumologic.com/docs/#tag/extractionRuleManagement">https://api.sumologic.com/docs/#tag/...RuleManagement</a>
   </td>
  </tr>
  <tr>
   <td>Partitions
   </td>
   <td><a href="https://api.sumologic.com/docs/#tag/partitionManagement">https://api.sumologic.com/docs/#tag/...tionManagement</a>
   </td>
  </tr>
  <tr>
   <td>Scheduled Views
   </td>
   <td><a href="https://api.sumologic.com/docs/#tag/scheduledViewManagement">https://api.sumologic.com/docs/#tag/...ViewManagement</a>
   </td>
  </tr>
  <tr>
   <td>Data Forwarding
   </td>
   <td><a href="https://api.sumologic.com/docs/#tag/logsDataForwardingManagement">https://api.sumologic.com/docs/#tag/...dingManagement</a>
   </td>
  </tr>
</table>



#### Tokens

<table>
  <tr>
   <td>API
   </td>
   <td>Documentation URL
   </td>
  </tr>
  <tr>
   <td>Tokens
   </td>
   <td><a href="https://api.sumologic.com/docs/#tag/tokensLibraryManagement">https://api.sumologic.com/docs/#tag/...raryManagement</a>
   </td>
  </tr>
</table>



#### Traces

<table>
  <tr>
   <td>API
   </td>
   <td>Documentation URL
   </td>
  </tr>
  <tr>
   <td>Traces
   </td>
   <td><a href="https://api.sumologic.com/docs/#tag/traces">https://api.sumologic.com/docs/#tag/traces</a>
   </td>
  </tr>
  <tr>
   <td>Span Analytics
   </td>
   <td><a href="https://api.sumologic.com/docs/#tag/spanAnalytics">https://api.sumologic.com/docs/#tag/spanAnalytics</a>
   </td>
  </tr>
  <tr>
   <td>Service Map
   </td>
   <td><a href="https://api.sumologic.com/docs/#tag/serviceMap">https://api.sumologic.com/docs/#tag/serviceMap</a>
   </td>
  </tr>
</table>



#### Users and Roles

<table>
  <tr>
   <td>API
   </td>
   <td>Documentation URL
   </td>
  </tr>
  <tr>
   <td>Roles
   </td>
   <td><a href="https://api.sumologic.com/docs/#tag/roleManagement">https://api.sumologic.com/docs/#tag/roleManagement</a>
   </td>
  </tr>
  <tr>
   <td>Users
   </td>
   <td><a href="https://api.sumologic.com/docs/#tag/userManagement">https://api.sumologic.com/docs/#tag/userManagement</a>
   </td>
  </tr>
</table>


#### Archive

<table>
  <tr>
   <td>API
   </td>
   <td>Documentation URL
   </td>
  </tr>
  <tr>
   <td>Archive Ingestion
   </td>
   <td><a href="https://api.sumologic.com/docs/#tag/archiveManagement">https://api.sumologic.com/docs/#tag/archiveManagement</a>
   </td>
  </tr>
</table>

</details>


## Authentication

Sumo Logic supports the following options for API authentication:
* Access ID and access key
* Base64 encoded access id and access key

See [Access Keys](/docs/manage/security/access-keys.md) to generate an access key. Make sure to copy the key you create, because it is displayed only once.

### Access ID and access key

When you have an `accessId` and `accessKey` you can execute requests such as the following:
```bash
curl -u "<accessId>:<accessKey>" -X GET <API Endpoint>
```

Where `<API Endpoint>` is the Sumo Logic API URL you're sending requests to. For more information, see [Sumo Logic Endpoints](#sumo-logic-endpoints-by-deployment-and-firewall-security).

### Basic access (Base64 encoded) authentication

If you prefer to use [basic access authentication](https://en.wikipedia.org/wiki/Basic_access_authentication), you can do a Base64 encoding of your `<accessId>:<accessKey>` to authenticate your HTTPS request. The following is an example request, replace the placeholder `<encoded>` with your encoded access id and access key string:

```bash
curl -H "Authorization: Basic <encoded>" -X GET <API Endpoint>
```

The spacing in the "Authorization" field is required.


#### Base64 example

In most Linux distributions you can use the 'base64' command. If the access id was `Aladdin` and your access key was `OpenSesame` then the command would be as follows:

```bash
echo -n "Aladdin:OpenSesame" | base64 --wrap 0
```

The `-n` ensures that an extra newline is not encoded.

This would yield a Base64 encoded string `QWxhZGRpbjpPcGVuU2VzYW1l` that is used like this:

```
"Authorization: Basic QWxhZGRpbjpPcGVuU2VzYW1l"
```


### Rate limiting

* A rate limit of four API requests per second (240 requests per minute) applies to all API calls from a user.
* A rate limit of 10 concurrent requests to any API endpoint applies to an access key.

If a rate is exceeded, a `rate limit exceeded 429` status code is returned.


## Sumo Logic Endpoints by Deployment and Firewall Security

Sumo Logic has several deployments that are assigned depending on the geographic location and the date an account is created.

Sumo Logic redirects your browser to the correct login URL and also redirects Collectors to the correct endpoint. However, if you're using an API you'll need to manually direct your API client to the correct Sumo Logic API URL.

<table><small>
  <tr>
   <td>Deployment
   </td>
   <td>Service Endpoint (login URL)
   </td>
   <td>API Endpoint
   </td>
   <td>Collection Endpoint
   </td>
   <td>Cloud Syslog Endpoint
   </td>
  </tr>
  <tr>
   <td>AU
   </td>
   <td>https://service.au.sumologic.com
   </td>
   <td>https://api.au.sumologic.com/api/
   </td>
   <td>https://collectors.au.sumologic.com
   </td>
   <td>syslog.collection.au.sumologic.com
   </td>
  </tr>
  <tr>
   <td>CA
   </td>
   <td>https://service.ca.sumologic.com
   </td>
   <td>https://api.ca.sumologic.com/api/
   </td>
   <td>https://collectors.ca.sumologic.com
   </td>
   <td>syslog.collection.ca.sumologic.com
   </td>
  </tr>
  <tr>
   <td>DE
   </td>
   <td>https://service.de.sumologic.com
   </td>
   <td>https://api.de.sumologic.com/api/
   </td>
   <td>https://collectors.de.sumologic.com
   </td>
   <td>syslog.collection.de.sumologic.com
   </td>
  </tr>
  <tr>
   <td>EU
   </td>
   <td>https://service.eu.sumologic.com</td>
   <td>https://api.eu.sumologic.com/api/</td>
   <td>https://collectors.eu.sumologic.com<br/>
   https://endpoint1.collection.eu.sumologic.com</td>
   <td>syslog.collection.eu.sumologic.com
   </td>
  </tr>
  <tr>
   <td>FED
   </td>
   <td>https://service.fed.sumologic.com
   </td>
   <td>https://api.fed.sumologic.com/api/
   </td>
   <td>https://collectors.fed.sumologic.com</td>
   <td>syslog.collection.fed.sumologic.com</td>
  </tr>
  <tr>
   <td>IN
   </td>
   <td>https://service.in.sumologic.com
   </td>
   <td>https://api.in.sumologic.com/api/
   </td>
   <td>https://collectors.in.sumologic.com
   </td>
   <td>syslog.collection.in.sumologic.com
   </td>
  </tr>
  <tr>
   <td>JP
   </td>
   <td>https://service.jp.sumologic.com
   </td>
   <td>https://api.jp.sumologic.com/api/
   </td>
   <td>https://collectors.jp.sumologic.com
   </td>
   <td>syslog.collection.jp.sumologic.com
   </td>
  </tr>
  <tr>
   <td>US1
   </td>
   <td>https://service.sumologic.com/
   </td>
   <td>https://api.sumologic.com/api/
   </td>
   <td>https://collectors.sumologic.com<br/>
   https://endpoint1.collection.sumologic.com<br/>
   https://endpoint2.collection.sumologic.com<br/>
   https://endpoint3.collection.sumologic.com<br/>
   https://endpoint4.collection.sumologic.com<br/>
   https://endpoint5.collection.sumologic.com</td>
   <td>syslog.collection.us1.sumologic.com
   </td>
  </tr>
  <tr>
   <td>US2
   </td>
   <td>https://service.us2.sumologic.com
   </td>
   <td>https://api.us2.sumologic.com/api/
   </td>
   <td>https://collectors.us2.sumologic.com<br/>
https://endpoint1.collection.us2.sumologic.com<br/>
https://endpoint2.collection.us2.sumologic.com<br/>
https://endpoint3.collection.us2.sumologic.com<br/>
https://endpoint4.collection.us2.sumologic.com<br/>
https://endpoint5.collection.us2.sumologic.com<br/>
https://endpoint6.collection.us2.sumologic.com<br/>
https://endpoint7.collection.us2.sumologic.com<br/>
https://endpoint8.collection.us2.sumologic.com<br/>
https://endpoint9.collection.us2.sumologic.com/</td>
   <td>syslog.collection.us2.sumologic.com</td>
  </tr></small>
</table>


### FedRAMP

Sumo Logic's FedRAMP deployment is similar to our other deployments, such as US2, except that FedRAMP is certified to comply with the United States Standards for Security Categorization of Federal Information and Information Systems ([FIPS-199](https://en.wikipedia.org/wiki/FIPS_199)). In this deployment, we adhere to specific security requirements that are required for handling, storing, and transmitting data classified in the "Moderate" impact level.


### How can I determine which endpoint I should use?

The easiest way to see which deployment pod your account uses is to look at the Sumo Logic URL you use. If you see "us2" that means you're running on the US2 pod. If you see "eu", "jp", "de", "in", "ca", or "au" you're on one of those pods. The US1 pod uses `service.sumologic.com`. The following image has an example URL from the US2 pod.

The specific collection endpoint will vary per account. The general format is:

```bash
endpoint[N].collection.[deploymentID].sumologic.com
```

You can also determine which deployment pod your account is using by creating an [HTTP Source](/docs/send-data/sources/hosted-collectors/http-logs-metrics-source/index.md) and looking at the provided URL.


### Securing access to Sumo Logic infrastructure via DNS name or IP address

See the [static IP addresses for Cloud-to-Cloud Integration](/docs/send-data/sources/hosted-collectors/cloud-to-cloud-integration-framework/index.md#Static-IP-addresses) Sources.

For collection to work, your firewall must allow outbound traffic to Sumo Logic. Refer to [Test Connectivity for Sumo Logic Collectors](/docs/send-data/installed-collectors/collector-installation-reference/test-connectivity-sumo-collectors.md) for instructions on allowing outbound traffic over port 443.

* If your firewall allows DNS entries, add the following to the allowlist in your firewall to allow outbound traffic to sumologic.com: `*.sumologic.com` By default, the Collector contacts `collectors.sumologic.com` before it is redirected to a deployment-specific endpoint such as `collectors.us2.sumologic.com` and `endpoint[N].collection.[deploymentID].[sumologic.com]`
* If your firewall doesn’t allow DNS entries, you must allowlist all of the IP addresses for your deployment region. The addresses to allowlist depend on your Sumo Logic deployment. To determine the IP addresses that require allowlisting, download the JSON object provided by Amazon Web Services (AWS). Amazon advises that this file will change several times a week. For details on how the file is updated, its usage, its syntax, and downloading the JSON file see [AWS IP Address Ranges](https://docs.aws.amazon.com/general/latest/gr/aws-ip-ranges.html).


#### AWS region by Sumo deployment

The following table describes the AWS regions used by each Sumo Logic deployment. See the [AWS page on regions and endpoints](http://docs.aws.amazon.com/general/latest/gr/rande.html) for more information.

<table>
  <tr>
   <td><strong>Sumo Logic Deployment</strong>
   </td>
   <td><strong>AWS region name</strong>
   </td>
   <td><strong>AWS Region</strong>
   </td>
  </tr>
  <tr>
   <td>AU
   </td>
   <td>Asia Pacific (Sydney)
   </td>
   <td>ap-southeast-2
   </td>
  </tr>
  <tr>
   <td>CA
   </td>
   <td>Canada (Central)
   </td>
   <td>ca-central-1
   </td>
  </tr>
  <tr>
   <td>DE
   </td>
   <td>EU (Frankfurt)
   </td>
   <td>eu-central-1
   </td>
  </tr>
  <tr>
   <td>EU
   </td>
   <td>EU (Ireland)
   </td>
   <td>eu-west-1
   </td>
  </tr>
  <tr>
   <td>FED
   </td>
   <td>US East (N. Virginia)
   </td>
   <td>us-east-1
   </td>
  </tr>
  <tr>
   <td>IN
   </td>
   <td>Asia Pacific (Mumbai)
   </td>
   <td>ap-south-1
   </td>
  </tr>
  <tr>
   <td>JP
   </td>
   <td>Asia Pacific (Tokyo)
   </td>
   <td>ap-northeast-1
   </td>
  </tr>
  <tr>
   <td>US1
   </td>
   <td>US East (N. Virginia)
   </td>
   <td>us-east-1
   </td>
  </tr>
  <tr>
   <td>US2
   </td>
   <td>US West (Oregon)
   </td>
   <td>us-west-2
   </td>
  </tr>
</table>


[This link](https://ip-ranges.amazonaws.com/ip-ranges.json) provides the complete current list of AWS IP ranges or subnets or prefixes. You can limit the number of entries in a firewall by using just the IP prefixes against the AWS region that your account's Sumo deployment uses, as shown in the table.

The list of IP ranges is shared infrastructure. It is not limited to Sumo Logic nodes and is subject to change over time.

You can run the following query against the downloaded file in Sumo Logic to determine the IP addresses for each deployment.

```sql
| parse regex "\s+\"ip_prefix\":\s+\"(?<ip_prefix>.*?)\",\n\s+\"region\":\s+\"(?<region>.*?)\",\n\s+\"service\":\s+\"(?<service>.*?)\"" multi | where service="AMAZON" and (region="us-west-2" or region="us-east-1" or region="eu-west-1" or region="ap-southeast-2") | if (region="us-west-2", "US2", region) as region | if (region="us-east-1", "PROD", region) as region | if (region="eu-west-1", "EU", region) as region | if (region="ap-southeast-2", "AU", region) as region | count by ip_prefix, region, service | fields - _count | sort by region, ip_prefix
```

After configuring the firewall, Collector, and Sources, confirm that the Collector and Sources are working by verifying that you can receive a given type of message (such as syslog messages) at the specified location.


### Versioning and Conflict Detection  

The Collector Management API uses optimistic locking to deal with versioning and conflict detection. Any response that returns a single entity will have an ETag header which identifies the version of that entity. Subsequent updates (`PUT `requests) to that entity must provide the value of the `ETag `header in an If-Match header; if the header is missing or no longer corresponds to the latest version of the entity, the request will fail (with `403 Forbidden` or `412 Precondition Failed`, respectively). Clients must be prepared to handle such failures if they anticipate concurrent updates to the entities. Additionally, the value of the `ETag `header may be provided in an `If-None-Match` header in future `GET `requests for caching purposes.


### Sumo Logic alerts from static IP addresses

Sumo Logic provides notifications through static IP addresses. You can allowlist those IP addresses to receive notifications directly from Sumo. For a list of our allowlist addresses, contact [Support](https://sumologic.com/).

The [**Test Connection feature for webhooks**](/docs/manage/connections-and-integrations/webhook-connections/set-up-webhook-connections.md#Testing-a-connection) does not use the same static IP addresses that send notifications, it uses different temporary IP addresses.


## Beta

Check out our [APIs in beta](/docs/api/beta).