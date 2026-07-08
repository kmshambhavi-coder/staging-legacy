# Playbooks
|Name|Folder|Description|
|----|------|-----------|
|Censys - Entity Enrichment|Content Hub Playbooks|This playbook automatically enriches IP addresses, domains, and certificate entities with Censys threat intelligence data during alert triage and investigation workflows. It retrieves comprehensive asset information including exposed services, ports, protocols, geolocation, ASN details, and associated infrastructure to provide immediate context for security analysts.|
|Crowdstrike Falcon Containment|Content Hub Playbooks|This block performs containment on endpoints by targeting case-related IPs and hostnames to prevent further compromise. A boolean input controls manual or automatic execution. In automatic mode, the Upload IOCs and Isolate Endpoint flags determine which actions run. It returns true if successful, false on failure, or empty if no action is taken.|
|New Block|Default|An embedded workflow that can receive inputs and return an output.|
|New Playbook|Default|test|
|imported manual  Playbook|Imported Playbooks||
