## Analyzers (1)

### MSDefenderOffice365_SafeLinksDecoder.json `v1.0`
Decodes Office 365 ATP Safe Links to extract original URLs. Supports url observables containing safelinks.protection.outlook.com domains.

- **Author:** Louis HUSSON
- **License:** AGPL-V3
- **Data Types:** `url`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/MSDefenderOffice365/MSDefenderOffice365_SafeLinksDecoder.json)

---

## Responders (4)

### MSDefenderOffice365_allow `v1.0`
Add entries to the Tenant Allow/Block List in the Microsoft 365 Defender

- **Author:** Vito Piserchia
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/MSDefenderOffice365/MSDefenderOffice365_allow.json)

### MSDefenderOffice365_block `v1.0`
Add entries to the Tenant Allow/Block List in the Microsoft 365 Defender

- **Author:** Joe Lazaro
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/MSDefenderOffice365/MSDefenderOffice365_block.json)

### MSDefenderOffice365_unblock `v1.0`
Add entries to the Tenant Allow/Block List in the Microsoft 365 Defender

- **Author:** Joe Lazaro
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/MSDefenderOffice365/MSDefenderOffice365_unblock.json)

### MSDefenderOffice365_disallow `v1.0`
Add entries to the Tenant Allow/Block List in the Microsoft 365 Defender

- **Author:** Vito Piserchia
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/MSDefenderOffice365/MSDefenderOffice365_disallow.json)
