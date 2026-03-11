## Analyzers (1)

### Watcher_Check `v1.0`
Check if a domain is monitored in Watcher (Legitimate Domain and/or Website Monitoring modules) and retrieve all details.

- **Author:** THA-CERT // YNE
- **License:** AGPL-V3
- **Data Types:** `domain`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/Watcher/Watcher_Check.json)

---

## Responders (4)

### Watcher_Transfer `v1.1`
Transfer domain between Watcher modules. Required tag: watcher:module=LegitDomain|WebsiteMonitoring (DESTINATION module). Transfer TO LegitDomain: watcher:repurchased=Yes/No (required), watcher:contact=email (optional). Transfer TO WebsiteMonitoring: watcher:legitimacy=2-6 (required), watcher:takedown_request=Yes/No, watcher:legal_team=Yes/No, watcher:blocking_request=Yes/No

- **Author:** THA-CERT // YNE
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/Watcher/Watcher_Transfer.json)

### Watcher_Remove `v1.1`
Remove domain from Watcher. Required tag: watcher:module=LegitDomain|WebsiteMonitoring

- **Author:** THA-CERT // YNE
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/Watcher/Watcher_Remove.json)

### Watcher_Update `v1.1`
Update domain in Watcher. Required tags: watcher:module=LegitDomain|WebsiteMonitoring. For LegitDomain: watcher:repurchased=Yes/No, watcher:contact=email (optional). For WebsiteMonitoring: watcher:legitimacy=2-6, watcher:takedown_request=Yes/No, watcher:legal_team=Yes/No, watcher:blocking_request=Yes/No

- **Author:** THA-CERT // YNE
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/Watcher/Watcher_Update.json)

### Watcher_Add `v1.1`
Add domain to Watcher. Required tags: watcher:module=LegitDomain|WebsiteMonitoring. For LegitDomain: watcher:repurchased=Yes/No (required), watcher:contact=email (optional). For WebsiteMonitoring: watcher:legitimacy=2-6 (required), watcher:takedown_request=Yes/No, watcher:legal_team=Yes/No, watcher:blocking_request=Yes/No

- **Author:** THA-CERT // YNE
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/Watcher/Watcher_Add.json)
