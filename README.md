# AbuseIPDB (abuseipdb)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
