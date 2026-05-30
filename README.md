# AbuseIPDB (abuseipdb)

AbuseIPDB is a community-driven project to help system administrators, webmasters, and security analysts check the reputation of IP addresses and report malicious activity. The free APIv2 surface lets developers query a single IP, check a CIDR block, retrieve paginated reports, download a curated blacklist, submit single or bulk abuse reports, and clear their own past reports for an address. AbuseIPDB underpins fail2ban, UFW, Cloudflare WAF, Wazuh, Splunk SOAR, and dozens of other firewall and SIEM integrations across the security community.

**URL:** [Visit APIs.json URL](https://docs.abuseipdb.com/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Anti Malware, Blacklist, Cyber Security, IP Reputation, Network Security, Public APIs, Threat Intelligence

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### AbuseIPDB APIv2

AbuseIPDB APIv2 is a REST API that exposes the AbuseIPDB community blacklist, IP report ingest, IP and CIDR reputation lookups, and self-service report cleanup. Authentication is via an API key delivered in a `Key:` HTTP header; responses are returned as JSON (or plaintext for the blacklist). The API is HTTPS only and enforces per-endpoint daily rate limits that scale by subscription tier.

**Human URL:** [https://docs.abuseipdb.com/](https://docs.abuseipdb.com/)

**Base URL:** `https://api.abuseipdb.com/api/v2/`

#### Tags:

 - Blacklist, IP Reputation, REST, Threat Intelligence

#### Properties

- [Documentation](https://docs.abuseipdb.com/)
- [CHECK Endpoint](https://docs.abuseipdb.com/#check-endpoint)
- [REPORTS Endpoint](https://docs.abuseipdb.com/#reports-endpoint)
- [BLACKLIST Endpoint](https://docs.abuseipdb.com/#blacklist-endpoint)
- [REPORT Endpoint](https://docs.abuseipdb.com/#report-endpoint)
- [BULK-REPORT Endpoint](https://docs.abuseipdb.com/#bulk-report-endpoint)
- [CHECK-BLOCK Endpoint](https://docs.abuseipdb.com/#check-block-endpoint)
- [CLEAR-ADDRESS Endpoint](https://docs.abuseipdb.com/#clear-address-endpoint)
- [Authentication](https://docs.abuseipdb.com/#authentication)
- [RateLimits](https://docs.abuseipdb.com/#rate-limit-headers)
- [Errors](https://docs.abuseipdb.com/#error-handling)
- [CodeExamples](https://docs.abuseipdb.com/#api-clients)
- [OpenAPI](openapi/abuseipdb-apiv2-openapi.yml)
- [JSON Schema — Check Response](json-schema/abuseipdb-check-response-schema.json)
- [JSON Schema — Report](json-schema/abuseipdb-report-schema.json)
- [JSON Schema — Blacklist Entry](json-schema/abuseipdb-blacklist-entry-schema.json)
- [JSON Structure — Check Response](json-structure/abuseipdb-check-response-structure.json)
- [JSON Structure — Report](json-structure/abuseipdb-report-structure.json)
- [JSON Structure — Blacklist Entry](json-structure/abuseipdb-blacklist-entry-structure.json)
- [JSON-LD Context](json-ld/abuseipdb-context.jsonld)
- [Example — Check](examples/abuseipdb-check-example.json)
- [Example — Report](examples/abuseipdb-report-example.json)
- [Example — Blacklist](examples/abuseipdb-blacklist-example.json)
- [Example — Check Block](examples/abuseipdb-check-block-example.json)
- [Example — Reports](examples/abuseipdb-reports-example.json)
- [Example — Bulk Report](examples/abuseipdb-bulk-report-example.json)

## Common Properties

- [Website](https://www.abuseipdb.com/)
- [Documentation](https://docs.abuseipdb.com/)
- [SignUp](https://www.abuseipdb.com/register)
- [Login](https://www.abuseipdb.com/login)
- [DeveloperPortal — API Key Dashboard](https://www.abuseipdb.com/account/api)
- [Pricing](https://www.abuseipdb.com/pricing)
- [Plans](plans/abuseipdb-plans-pricing.yml)
- [RateLimits](rate-limits/abuseipdb-rate-limits.yml)
- [SpectralRules](rules/abuseipdb-rules.yml)
- [Vocabulary](vocabulary/abuseipdb-vocabulary.yml)
- [FinOps](finops/abuseipdb-finops.yml)
- [Blog](https://www.abuseipdb.com/blog)
- [FAQ](https://www.abuseipdb.com/faq.html)
- [Support](https://www.abuseipdb.com/contact)
- [Contact](https://www.abuseipdb.com/contact)
- [TermsOfService](https://www.abuseipdb.com/terms-of-service)
- [PrivacyPolicy](https://www.abuseipdb.com/privacy-policy)
- [GitHubOrganization](https://github.com/AbuseIPDB)
- [SDK — AbuseIPDB Laravel Package](https://github.com/AbuseIPDB/laravel)
- [SDK — laravel-abuseipdb (community)](https://github.com/nickurt/laravel-abuseipdb)
- [SDK — abuseipdb-rb (Ruby gem)](https://github.com/falegk/abuseipdb-rb)
- [SDK — python-abuseipdb](https://github.com/meatyite/python-abuseipdb)
- [SDK — abuseipdb-wrapper (Python)](https://github.com/streanger/abuseipdb-wrapper)
- [CLI — abuseipdb-cli](https://github.com/kristuff/abuseipdb-cli)

## Features

| Name | Description |
|------|-------------|
| IP Reputation Lookups | Query any IPv4 or IPv6 address for its abuse confidence score, total reports, distinct reporters, and country/ISP metadata. |
| Community-Sourced Blacklist | Downloadable daily blacklist of high-confidence abusive IPs, with configurable confidence threshold, country filters, IP version, and result limit. |
| Abuse Reporting | Submit single or bulk abuse reports tagged with one or more standard category IDs (e.g. SSH Brute-Force, DDoS, Web App Attack). |
| CIDR Block Checking | Score whole subnets in one call via the CHECK-BLOCK endpoint, with subscriber tiers supporting up to /16 networks. |
| Categorised Abuse Taxonomy | 23 standard report categories (DNS Compromise, Open Proxy, Brute-Force, Phishing, etc.) for consistent classification. |
| Self-Service Report Clearing | Remove your own reports for a given IP via the CLEAR-ADDRESS endpoint if a report was made in error. |
| Standard Rate-Limit Headers | Every response carries X-RateLimit-Limit / Remaining / Reset and Retry-After, simplifying back-off in clients. |
| Whitelist Awareness | Responses include an `isWhitelisted` flag so consumers can avoid blocking known-good infrastructure. |

## Use Cases

| Name | Description |
|------|-------------|
| SSH / RDP Brute-Force Defence | Auto-block and report SSH/RDP brute-force sources via fail2ban, UFW, or endlessh integrations. |
| WAF Augmentation | Enrich Cloudflare / Nginx / custom WAF rulesets with the AbuseIPDB blacklist for IP-based pre-filtering. |
| SIEM / SOC Enrichment | Add AbuseIPDB context to Splunk SOAR, Wazuh, and TheHive alerts for analyst triage. |
| Bot and Crawler Filtering | Score request source IPs before serving e-commerce or login pages to block known-abusive infrastructure. |
| Threat Hunting and OSINT | Combine AbuseIPDB with VirusTotal, Shodan, GreyNoise and similar feeds (e.g. malwoverview) during incident response. |
| Bulk Reporting from Edge Logs | Convert nightly access logs into CSV bulk reports to feed the AbuseIPDB community blacklist. |

## Integrations

| Name | Description |
|------|-------------|
| Fail2Ban | Pre-packaged AbuseIPDB action ships with fail2ban; reports banned offenders directly to AbuseIPDB. |
| UFW (Uncomplicated Firewall) | Multiple community projects (sefinek/UFW-AbuseIPDB-Reporter, jseutens/ufw-abuseipdb) ingest UFW logs and report or ingest the AbuseIPDB blacklist. |
| Cloudflare WAF | sefinek/Cloudflare-WAF-To-AbuseIPDB streams Cloudflare WAF events into AbuseIPDB reports. |
| Splunk SOAR | Official splunk-soar-connectors/abuseipdb connector enriches Splunk SOAR playbooks with AbuseIPDB reputation. |
| Wazuh | marciuscosta/abuseipdb-wazuh-integration wires AbuseIPDB enrichment into Wazuh with a local cache and multi-key support. |
| CrowdSec | goremykin/crowdsec-abuseipdb-blocklist converts CrowdSec data into AbuseIPDB blocklists. |
| Endlessh | elhenro/endlessh-auto-report-abuseipdb auto-reports SSH tarpit visitors to AbuseIPDB. |
| Nginx | tmiland/abuseipdb-php-nginx-blacklist-create generates an Nginx-ready blocklist file from AbuseIPDB. |
| Zen Cart | CcMarc/AbuseIPDB plugs AbuseIPDB into the Zen Cart e-commerce platform. |
| TheHive | AbuseIPDB enrichment is used by SOAR/IR pipelines like malwarekid/SOAR-Flow alongside Wazuh and TheHive. |
| IPinfo | AbuseIPDB sources its IP geolocation, ISP, usage type, and domain data from IPinfo. |

## Solutions

| Name | Description |
|------|-------------|
| Individual (Free) | 1,000 checks/day, 100 block checks, 5 blacklist downloads. Aimed at hobby admins and home labs. |
| Basic | $25/mo. 10,000 checks/day, 1,000 block checks, 100 bulk reports, customisable blacklist up to 100,000 IPs. |
| Premium | $99/mo. 50,000 checks/day, 5,000 block checks, 500 bulk reports, customisable blacklist up to 500,000 IPs. |
| Enterprise | Custom-priced direct data access for ISPs and large security organisations. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [AbuseIPDB APIv2](openapi/abuseipdb-apiv2-openapi.yml)

### JSON Schema

- [Check Response Schema](json-schema/abuseipdb-check-response-schema.json)
- [Report Schema](json-schema/abuseipdb-report-schema.json)
- [Blacklist Entry Schema](json-schema/abuseipdb-blacklist-entry-schema.json)

### JSON Structure

- [Check Response Structure](json-structure/abuseipdb-check-response-structure.json)
- [Report Structure](json-structure/abuseipdb-report-structure.json)
- [Blacklist Entry Structure](json-structure/abuseipdb-blacklist-entry-structure.json)

### JSON-LD

- [AbuseIPDB JSON-LD Context](json-ld/abuseipdb-context.jsonld)

### Examples

- [Check Example](examples/abuseipdb-check-example.json)
- [Report Example](examples/abuseipdb-report-example.json)
- [Blacklist Example](examples/abuseipdb-blacklist-example.json)
- [Check Block Example](examples/abuseipdb-check-block-example.json)
- [Reports Example](examples/abuseipdb-reports-example.json)
- [Bulk Report Example](examples/abuseipdb-bulk-report-example.json)

## Capabilities

Naftiko capabilities organized as workflow-oriented compositions over the AbuseIPDB APIv2 surface.

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [IP Reputation Lookup](capabilities/ip-reputation-lookup.yaml) | AbuseIPDB APIv2 | 3 | Security analyst / WAF operator |
| [Abuse Reporting](capabilities/abuse-reporting.yaml) | AbuseIPDB APIv2 | 3 | Firewall / SIEM automation |
| [Blacklist Management](capabilities/blacklist-management.yaml) | AbuseIPDB APIv2 | 1 | Edge security engineer |

## Vocabulary

- [AbuseIPDB Vocabulary](vocabulary/abuseipdb-vocabulary.yml) — Unified taxonomy mapping 4 resources, 23 report categories, 3 capability surfaces, and 4 subscription tiers across operational (OpenAPI) and capability (Naftiko) dimensions.

## Rules

- [AbuseIPDB Spectral Ruleset](rules/abuseipdb-rules.yml) — 23 rules across info/metadata, OpenAPI version, servers, security, operations, responses, parameters, schemas, and tags categories enforcing AbuseIPDB API conventions.

## Plans

- [AbuseIPDB Plans & Pricing](plans/abuseipdb-plans-pricing.yml) — 4 tiers (Individual / Basic / Premium / Enterprise) modelled with API Commons Plans 0.1.

## Rate Limits

- [AbuseIPDB Rate Limits](rate-limits/abuseipdb-rate-limits.yml) — Per-endpoint daily quotas per tier modelled with API Commons Rate Limits 0.1.

## FinOps

- [AbuseIPDB FinOps](finops/abuseipdb-finops.yml) — FOCUS 1.3 aligned billing-surface mapping; tiered subscription, no overage billing.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
