# AbuseIPDB (abuseipdb)

AbuseIPDB is a community-driven project to help system administrators, webmasters, and security analysts check the reputation of IP addresses and report malicious activity. The free APIv2 surface lets developers query a single IP, check a CIDR block, retrieve paginated reports, download a curated blacklist, submit single or bulk abuse reports, and clear their own past reports for an address. AbuseIPDB underpins fail2ban, UFW, Cloudflare WAF, Wazuh, Splunk SOAR, and dozens of other firewall and SIEM integrations across the security community.

**APIs.json:** [https://docs.abuseipdb.com/](https://docs.abuseipdb.com/)

## Scope

- **Type:** Index
- **Access:** 3rd-Party

## Tags

- Anti Malware
- Blacklist
- Cyber Security
- IP Reputation
- Network Security
- Public APIs
- Threat Intelligence

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### AbuseIPDB APIv2

AbuseIPDB APIv2 is a REST API that exposes the AbuseIPDB community blacklist, IP report ingest, IP and CIDR reputation lookups, and self-service report cleanup. Authentication is via an API key delivered in a `Key:` HTTP header; responses are returned as JSON (or plaintext for the blacklist). The API is HTTPS only and enforces per-endpoint daily rate limits that scale by subscription tier.

- **Human URL:** [https://docs.abuseipdb.com/](https://docs.abuseipdb.com/)
- **Base URL:** `https://api.abuseipdb.com/api/v2/`

#### Tags

- Blacklist
- IP Reputation
- REST
- Threat Intelligence

#### Properties

- [Documentation](https://docs.abuseipdb.com/)
- [API Reference](https://docs.abuseipdb.com/#check-endpoint)
- [API Reference](https://docs.abuseipdb.com/#reports-endpoint)
- [API Reference](https://docs.abuseipdb.com/#blacklist-endpoint)
- [API Reference](https://docs.abuseipdb.com/#report-endpoint)
- [API Reference](https://docs.abuseipdb.com/#bulk-report-endpoint)
- [API Reference](https://docs.abuseipdb.com/#check-block-endpoint)
- [API Reference](https://docs.abuseipdb.com/#clear-address-endpoint)
- [Authentication](https://docs.abuseipdb.com/#authentication)
- [Rate Limits](https://docs.abuseipdb.com/#rate-limit-headers)
- [Errors](https://docs.abuseipdb.com/#error-handling)
- [Code Examples](https://docs.abuseipdb.com/#api-clients)
- [OpenAPI](openapi/abuseipdb-apiv2-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/abuseipdb-apiv2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/abuseipdb-apiv2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/abuseipdb-check-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/abuseipdb-report-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/abuseipdb-blacklist-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/abuseipdb-check-response-structure.json)
- [JSON Structure](json-structure/abuseipdb-report-structure.json)
- [JSON Structure](json-structure/abuseipdb-blacklist-entry-structure.json)
- [JSON-LD](json-ld/abuseipdb-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/abuseipdb-check-example.json)
- [Example](examples/abuseipdb-report-example.json)
- [Example](examples/abuseipdb-blacklist-example.json)
- [Example](examples/abuseipdb-check-block-example.json)
- [Example](examples/abuseipdb-reports-example.json)
- [Example](examples/abuseipdb-bulk-report-example.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Website](https://www.abuseipdb.com/)
- [Documentation](https://docs.abuseipdb.com/)
- [Sign Up](https://www.abuseipdb.com/register)
- [Login](https://www.abuseipdb.com/login)
- [Developer Portal](https://www.abuseipdb.com/account/api)
- [Pricing](https://www.abuseipdb.com/pricing)
- [Plans](plans/abuseipdb-plans-pricing.yml)
- [Rate Limits](rate-limits/abuseipdb-rate-limits.yml)
- [Spectral Rules](rules/abuseipdb-rules.yml)
- [Vocabulary](vocabulary/abuseipdb-vocabulary.yml)
- [Fin Ops](finops/abuseipdb-finops.yml)
- [Plans](https://www.abuseipdb.com/account/plans)
- [Blog](https://www.abuseipdb.com/blog)
- [F A Q](https://www.abuseipdb.com/faq.html)
- [Support](https://www.abuseipdb.com/contact)
- [Contact](https://www.abuseipdb.com/contact)
- [Terms of Service](https://www.abuseipdb.com/terms-of-service)
- [Privacy Policy](https://www.abuseipdb.com/privacy-policy)
- [GitHub Organization](https://github.com/AbuseIPDB)
- [SDK](https://github.com/AbuseIPDB/laravel)
- [SDK](https://github.com/nickurt/laravel-abuseipdb)
- [SDK](https://github.com/falegk/abuseipdb-rb)
- [SDK](https://github.com/meatyite/python-abuseipdb)
- [SDK](https://github.com/streanger/abuseipdb-wrapper)
- [C L I](https://github.com/kristuff/abuseipdb-cli)
- [Integrations](undefined)
- [Features](undefined)
- [Use Cases](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
