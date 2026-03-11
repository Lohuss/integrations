## Analyzers (1)

### AbuseIPDB `v1.1`
Checks an IP against AbuseIPDB for abuse score, categories, and recent reports.

- **Author:** Matteo Lodi; Fabien Bloume, StrangeBee
- **License:** AGPL-v3
- **Data Types:** `ip`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/AbuseIPDB/AbuseIPDB.json)

---

## Responders (1)

### AbuseIPDB_Report `v1.0`
Report an IP address to AbuseIPDB for abuse tracking and community sharing. Please, make sure to use the correct category in your Cortex responder configuration.

- **Author:** Fabien Bloume, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/AbuseIPDB/AbuseIPDB_Report.json)
