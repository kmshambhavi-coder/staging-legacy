# GitSync

## Integrations
|Name|Description|
|----|-----------|
|Azure Active Directory|Azure Active Directory (Azure AD) is Microsoft's cloud-based identity and access management service, which helps your employees sign in and access  both internal and external resources.|
|CSV|Integration designed around working with CSV files. CSV is a simple file format used to store tabular data, such as a spreadsheet or database.|
|CrowdStrike Falcon|CrowdStrike Falcon is the leader in next-generation endpoint protection, threat intelligence and incident response through cloud-based endpoint protection.|
|EmailUtilities|A set of utility actions to assist with working with emails.  Includes actions to parse EMLs and analyze email headers.|
|Google Chronicle|Google SecOps enables you to examine the aggregated security information for your enterprise going back for months or longer. Use Google SecOps to search across all of the domains accessed from within your enterprise. To enable the Google API client to communicate with the Backstory API you will need Google Developer Service Account Credential, https://developers.google.com/identity/protocols/OAuth2#serviceaccount.|
|Palo Alto Cortex XDR|Cortex XDR - XDR is the world’s first detection and response app that natively integrates network, endpoint and cloud data to stop sophisticated attacks.  Cortex XDR accurately detects threats with behavioral analytics and reveals the root cause to speed up investigations.|
|TemplateEngine|Template Engine integration provides the ability to render templates using Jinja2. Jinja2 provide fast and flexible ways to create rich templates. These templates can be used in entity insights, emails, ticketing systems, or any action that can take in a text string.Jinja2 documentation can be found at https://jinja.palletsprojects.com/en/2.11.x/|


## Connectors
|Name|Description|Has Mappings|
|----|-----------|------------|
|Crowdstrike - Alerts Connector|Pull alerts from Crowdstrike. Dynamic List works with the "display_name" parameter. Note: To fetch identity protection detections use "Identity Protection Detections Connector".|False|
|Crowdstrike - Identity Protection Detections Connector|Pull Identity Protection detections from Crowdstrike. Note: this connector requires an Identity Protection license. Dynamic List works with the “display_name” parameter.|False|


## Playbooks
|Name|Description|
|----|-----------|
|Censys - Entity Enrichment|This playbook automatically enriches IP addresses, domains, and certificate entities with Censys threat intelligence data during alert triage and investigation workflows. It retrieves comprehensive asset information including exposed services, ports, protocols, geolocation, ASN details, and associated infrastructure to provide immediate context for security analysts.|
|Crowdstrike Falcon Containment|This block performs containment on endpoints by targeting case-related IPs and hostnames to prevent further compromise. A boolean input controls manual or automatic execution. In automatic mode, the Upload IOCs and Isolate Endpoint flags determine which actions run. It returns true if successful, false on failure, or empty if no action is taken.|
|New Block|An embedded workflow that can receive inputs and return an output.|
|New Playbook|test|
|imported manual  Playbook||


## Visual Families
|Name|Description|
|----|-----------|
|Copy of manual-custom family001|manual-custom family001|
|manual-custom family001|manual-custom family001|


## Jobs
|Name|Description|
|----|-----------|
|Google Chronicle Alerts Creator Job - 1|This job will sync new SOAR alerts with Chronicle SIEM.Note: This job is only supported from Chronicle SOAR version 6.2.30 and higher.|
|Google Chronicle Alerts Creator Job|This job will sync new SOAR alerts with Chronicle SIEM.Note: This job is only supported from Chronicle SOAR version 6.2.30 and higher.|
|Google Chronicle Sync Job|This job will synchronize information about Chronicle SOAR Cases and Chronicle SOAR Alerts with Chronicle SIEM. Note: This job is only supported from Chronicle SOAR version 6.1.44 and higher.|
|Sync Alerts - 1|This job will synchronize Google SecOps Alerts and Crowdstrike alerts. The job synchronizes comments and status. Requires “Crowdstrike Alert” tag on the case. Note: If the alert didn’t originate from “Alerts Connector” or “Identity Protections Detection Connector” you will need to add an “Alert_ID” context value for the job to be able to find the correct information.|
|Sync Alerts|This job will synchronize Google SecOps Alerts and Crowdstrike alerts. The job synchronizes comments and status. Requires “Crowdstrike Alert” tag on the case. Note: If the alert didn’t originate from “Alerts Connector” or “Identity Protections Detection Connector” you will need to add an “Alert_ID” context value for the job to be able to find the correct information.|
|Sync Incidents|This job synchronizes Google SecOps Alerts and Palo Alto XDR Incidents. It ensures that comments and status are kept in sync between the two systems. For the job to identify the correct information, the Google SecOps case must have the "Palo Alto XDR Incident" tag. If the alert didn’t originate from "Palo Alto Cortex XDR Connector",  you will need to add an "Incident_ID" context value to the case for the job to be able to find the correct information.|
|createCSVfile||

