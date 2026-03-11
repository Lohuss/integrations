## Analyzers (3)

### SentinelOne_DNSReverseLookup `v1.0`
Query SentinelOne for DNS names that resolved to a given IP address. Returns the domains and the hosts that made the DNS queries. Supports both SDL (Security Data Lake) API and legacy Deep Visibility API.

- **Author:** Fabien Bloume, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `ip`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/SentinelOne/SentinelOne_DNSReverseLookup.json)

### SentinelOne_DeepVisibility_DNSQuery `v1.0`
Query Sentinel One Deep Visibility API v2.1 for hosts that have requested DNS lookups for a domain/URL/FQDN.

- **Author:** Joe Vasquez
- **License:** AGPL-V3
- **Data Types:** `url`, `domain`, `fqdn`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/SentinelOne/SentinelOne_DeepVisibility_DNSQuery.json)

### SentinelOne_DNSQuery `v2.0`
Query SentinelOne for hosts that have requested DNS lookups for a domain/URL/FQDN. Supports both new SDL (Security Data Lake) API and legacy Deep Visibility API v2.1.

- **Author:** Joe Vasquez; Fabien Bloume, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `url`, `domain`, `fqdn`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/SentinelOne/SentinelOne_DNSQuery.json)

---

## Responders (1)

### SentinelOne_Hash_Blacklister `v1.0`
Add SHA1 hash to SentinelOne Blacklist via API v2.1.

- **Author:** Joe Vasquez
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/SentinelOne/SentinelOne_HashBlacklister.json)
