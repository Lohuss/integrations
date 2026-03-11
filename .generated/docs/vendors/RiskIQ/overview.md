## Analyzers (16)

### RiskIQ_Cookies `v1.0`
RiskIQ: cookies observed during crawls on a hostname.

- **Author:** RiskIQ
- **License:** AGPL-V3
- **Data Types:** `domain`, `fqdn`, `ip`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/RiskIQ/RiskIQ_Cookies.json)

### RiskIQ_Whois `v1.0`
RiskIQ Whois lookup for an indicator.

- **Author:** RiskIQ
- **License:** AGPL-V3
- **Data Types:** `domain`, `fqdn`, `ip`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/RiskIQ/RiskIQ_Whois.json)

### RiskIQ_Components `v1.0`
RiskIQ: web components observed during crawls on a hostname.

- **Author:** RiskIQ
- **License:** AGPL-V3
- **Data Types:** `domain`, `fqdn`, `ip`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/RiskIQ/RiskIQ_Components.json)

### RiskIQ_Malware `v1.0`
RiskIQ: malware hashes from various sources associated with an IOC.

- **Author:** RiskIQ
- **License:** AGPL-V3
- **Data Types:** `domain`, `fqdn`, `ip`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/RiskIQ/RiskIQ_Malware.json)

### RiskIQ_Reputation `v1.0`
RiskIQ Illuminate Reputation Score for an indicator.

- **Author:** RiskIQ
- **License:** AGPL-V3
- **Data Types:** `domain`, `fqdn`, `ip`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/RiskIQ/RiskIQ_Reputation.json)

### RiskIQ_Trackers `v1.0`
RiskIQ: trackers observed during a crawl on a host.

- **Author:** RiskIQ
- **License:** AGPL-V3
- **Data Types:** `domain`, `fqdn`, `ip`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/RiskIQ/RiskIQ_Trackers.json)

### RiskIQ_Subdomains `v1.0`
RiskIQ: subdomains observed historically in pDNS records.

- **Author:** RiskIQ
- **License:** AGPL-V3
- **Data Types:** `fqdn`, `domain`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/RiskIQ/RiskIQ_Subdomains.json)

### RiskIQ_Artifacts `v1.0`
RiskIQ: Illuminate / PassiveTotal project artifacts that match an indicator.

- **Author:** RiskIQ
- **License:** AGPL-V3
- **Data Types:** `domain`, `fqdn`, `ip`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/RiskIQ/RiskIQ_Artifacts.json)

### RiskIQ_Projects `v1.0`
RiskIQ: Illuminate / PassiveTotal projects that contain an artifact which matches an IOC.

- **Author:** RiskIQ
- **License:** AGPL-V3
- **Data Types:** `domain`, `fqdn`, `ip`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/RiskIQ/RiskIQ_Projects.json)

### RiskIQ_HostpairParents `v1.0`
RiskIQ: hosts with a parent web component relationship to an IOC.

- **Author:** RiskIQ
- **License:** AGPL-V3
- **Data Types:** `domain`, `fqdn`, `ip`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/RiskIQ/RiskIQ_HostpairParents.json)

### RiskIQ_HostpairChildren `v1.0`
RiskIQ: hosts with a child web component relationship to an IOC.

- **Author:** RiskIQ
- **License:** AGPL-V3
- **Data Types:** `domain`, `fqdn`, `ip`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/RiskIQ/RiskIQ_HostpairChildren.json)

### RiskIQ_Summary `v1.0`
RiskIQ Illuminate and PassiveTotal datasets with records for an indicator.

- **Author:** RiskIQ
- **License:** AGPL-V3
- **Data Types:** `domain`, `fqdn`, `ip`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/RiskIQ/RiskIQ_Summary.json)

### RiskIQ_Resolutions `v1.0`
RiskIQ: PDNS resolutions for an IOC.

- **Author:** RiskIQ
- **License:** AGPL-V3
- **Data Types:** `domain`, `fqdn`, `ip`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/RiskIQ/RiskIQ_Resolutions.json)

### RiskIQ_Services `v1.0`
RiskIQ: services observed on an IP address.

- **Author:** RiskIQ
- **License:** AGPL-V3
- **Data Types:** `ip`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/RiskIQ/RiskIQ_Services.json)

### RiskIQ_Articles `v1.0`
RiskIQ: OSINT articles that reference an indicator.

- **Author:** RiskIQ
- **License:** AGPL-V3
- **Data Types:** `domain`, `fqdn`, `ip`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/RiskIQ/RiskIQ_Articles.json)

### RiskIQ_Certificates `v1.0`
RiskIQ: SSL/TLS certificates associated with an indicator.

- **Author:** RiskIQ
- **License:** AGPL-V3
- **Data Types:** `domain`, `fqdn`, `ip`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/RiskIQ/RiskIQ_Certificates.json)

---

## Responders (1)

### RiskIQ_PushArtifactToProject `v1.0`
Push a case to a RiskIQ Illuminate project.

- **Author:** RiskIQ
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/RiskIQ/RiskIQ_PushArtifactToProject.json)
