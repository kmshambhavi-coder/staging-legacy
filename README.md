# GitSync

## Integrations
|Name|Description|
|----|-----------|
|AbuseIPDB|Leverage the AbuseIPDB threat intelligence API with this integration.|
|Azure Active Directory|Azure Active Directory (Azure AD) is Microsoft's cloud-based identity and access management service, which helps your employees sign in and access  both internal and external resources.|
|CSV|Integration designed around working with CSV files. CSV is a simple file format used to store tabular data, such as a spreadsheet or database.|
|MISP|MISP is an open source software solution for collecting, storing, distributing and sharing cyber security indicators and threat about cyber security incidents|
|Palo Alto Cortex XDR|Cortex XDR - XDR is the world’s first detection and response app that natively integrates network, endpoint and cloud data to stop sophisticated attacks.  Cortex XDR accurately detects threats with behavioral analytics and reveals the root cause to speed up investigations.|
|RecordedFutureIntelligence|Recorded Future's unique technology collects and analyzes vast amounts of data to deliver relevant cyber threat insights in real-time. For support please contact support@recordedfuture.com|


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

