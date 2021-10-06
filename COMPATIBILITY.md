# Supported Capabilities

The following tables outline the functionality that the sumologic-go-sdk supports.

## Sumo Logic API

You can find further information about the Sumo Logic APIs in their [documentation](https://help.sumologic.com/APIs).

| API | Status | Notes |
| --- | --- | --- |
| Access Keys | :white_check_mark: | |
| Account | :white_check_mark: | |
| Apps (Beta) | :white_check_mark: | |
| Archive Ingestion | :white_check_mark: | |
| Connections (Beta) | :white_check_mark: | |
| Content | :white_check_mark: | |
| Collectors | :white_check_mark: | |
| Dashboards | :white_check_mark: | |
| Dynamic Parsing | :white_check_mark: | |
| Field Extraction Rules | :white_check_mark: | |
| Field Management | :white_check_mark: | |
| Folders | :white_check_mark: | |
| Health Events | :white_check_mark: | |
| Ingest Budgets | :white_check_mark: | |
| Ingest Budgets v2 | :white_check_mark: | |
| Log Search Estimated Usage | :white_check_mark: | |
| Lookup Tables | :white_check_mark: | | 
| Metrics Searches (Beta) | :white_check_mark: | |
| Metrics Query | :white_check_mark: | |
| Monitors | :white_check_mark: | |
| Organizations (Beta) | :white_check_mark: | |
| Partitions | :white_check_mark: | |
| Password Policy | :white_check_mark: | |
| Permissions | :white_check_mark: | |
| Policies | :white_check_mark: | |
| Roles | :white_check_mark: | |
| SAML Configuration | :white_check_mark: | |
| Scheduled Views | :white_check_mark: | |
| Service Allowlist | :white_check_mark: | |
| Sources | :white_check_mark: | |
| Tokens | :white_check_mark: | |
| Transformation Rules (Beta) | :white_check_mark: | |
| Users | :white_check_mark: | |

## Sumo Logic Sources Support

You can find further information about supported Sumo Logic sources in their [documentation](https://help.sumologic.com/03Send-Data/Sources/03Use-JSON-to-Configure-Sources)

### Log Sources for Installed Collectors

| Source | Status | Notes |
| --- | --- | --- |
| Local File Source | | |
| Remote File Source | | |
| Local Windows Event Log Source | | |
| Remote Windows Event Log Source | | |
| Local Windows Performance Source | | |
| Remote Windows Performance Source | | |
| Windows Active Directory Source | | |
| Syslog Source | | |
| Script Source | | |
| Docker Log Source | | |
| Docker Stats Source | | |

### Metric Sources for Installed Collectors

| Source | Status | Notes |
| --- | --- | --- |
| Host Metrics Source | |
| Streaming Metrics Source | |

### Log Sources for Hosted Collectors

| Source | Status | Notes |
| --- | --- | --- |
| Akamai SIEM API Source | | |
| Amazon S3 Source | | |
| AWS S3 Archive Source | :white_check_mark: | |
| AWS Elastic Load Balancing Source | | |
| AWS CloudFront Source | | |
| AWS CloudTrail Source | | |
| AWS S3 Audit Source | | |
| AWS Metadata (Tag) Source | | |
| Azure Event Hubs Source | :white_check_mark: | |
| Carbon Black Cloud Source | | |
| Cloud Syslog Source | | |
| Cisco AMP Source | | |
| Crowdstrike FDR Source | | |
| Crowdstrike Source | | |
| CSE AWS EC2 Inventory Source | | |
| Duo Source | | |
| HTTP Source | | Sending data to HTTP sources is supported using the SendMessage function |
| Microsoft Graph Security API Source | | |
| Mimecast Source | | |
| Netskope Source | | |
| Okta Source | | |
| Proofpoint TAP Source | | |
| Salesforce Source | | |
| Sophos Central Source | | |
| Tenable Source | | |

### Metrics Sources for Hosted Collectors

| Source | Status | Notes |
| --- | --- | --- |
| AWS CloudWatch Source | | |
