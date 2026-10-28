# AbuseIPDB

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
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

**Areas:** Anti Malware · Blacklist · Cybersecurity · IP Reputation · Network Security · Public APIs · Threat Intelligence

## AbuseIPDB on APIs.io

Everything profiled for AbuseIPDB is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/abuseipdb/](https://apis.io/providers/abuseipdb/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [AbuseIPDB Blacklist API](https://apis.io/apis/abuseipdb/abuseipdb-blacklist-api/) — Endpoints for downloading the community blacklist.
- [AbuseIPDB Management API](https://apis.io/apis/abuseipdb/abuseipdb-management-api/) — Endpoints for managing your own reports.
- [AbuseIPDB Reports API](https://apis.io/apis/abuseipdb/abuseipdb-reports-api/) — Endpoints for submitting and retrieving abuse reports.
- [AbuseIPDB Reputation API](https://apis.io/apis/abuseipdb/abuseipdb-reputation-api/) — Endpoints for looking up the abuse data of an IP or CIDR network.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Arazzo workflows (7)

Multi-step workflows that chain operations into a business task.

- [AbuseIPDB Blacklist Triage](https://apis.io/arazzos/abuseipdb/abuseipdb-blacklist-triage-workflow/)
- [AbuseIPDB Block Scan And Check](https://apis.io/arazzos/abuseipdb/abuseipdb-block-scan-and-check-workflow/)
- [AbuseIPDB Bulk Report Then Verify](https://apis.io/arazzos/abuseipdb/abuseipdb-bulk-report-then-verify-workflow/)
- [AbuseIPDB Check Then Report](https://apis.io/arazzos/abuseipdb/abuseipdb-check-then-report-workflow/)
- [AbuseIPDB Clear False Positive](https://apis.io/arazzos/abuseipdb/abuseipdb-clear-false-positive-workflow/)
- [AbuseIPDB Investigate IP](https://apis.io/arazzos/abuseipdb/abuseipdb-investigate-ip-workflow/)
- [AbuseIPDB Report Then Verify](https://apis.io/arazzos/abuseipdb/abuseipdb-report-then-verify-workflow/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Abuseipdb Agentic Access](https://apis.io/agentic-access/abuseipdb/abuseipdb-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [AbuseIPDB Blacklist Entry](https://apis.io/schemas/abuseipdb/abuseipdb-blacklist-entry/)
- [AbuseIPDB Check Response](https://apis.io/schemas/abuseipdb/abuseipdb-check-response/)
- [AbuseIPDB Report](https://apis.io/schemas/abuseipdb/abuseipdb-report/)

#### JSON Structure (3)

Data models expressed in JSON Structure.

- [Abuseipdb Blacklist Entry Structure](https://apis.io/json-structure/abuseipdb/abuseipdb-blacklist-entry-structure/)
- [Abuseipdb Check Response Structure](https://apis.io/json-structure/abuseipdb/abuseipdb-check-response-structure/)
- [Abuseipdb Report Structure](https://apis.io/json-structure/abuseipdb/abuseipdb-report-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Abuseipdb Context](https://apis.io/jsonld/abuseipdb/abuseipdb-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Abuseipdb Vocabulary](https://apis.io/vocabularies/abuseipdb/abuseipdb-vocabulary/)

#### Examples (6)

Example requests and responses.

- [Abuseipdb Blacklist Example](https://apis.io/examples/abuseipdb/abuseipdb-blacklist-example/)
- [Abuseipdb Bulk Report Example](https://apis.io/examples/abuseipdb/abuseipdb-bulk-report-example/)
- [Abuseipdb Check Block Example](https://apis.io/examples/abuseipdb/abuseipdb-check-block-example/)
- [Abuseipdb Check Example](https://apis.io/examples/abuseipdb/abuseipdb-check-example/)
- [Abuseipdb Report Example](https://apis.io/examples/abuseipdb/abuseipdb-report-example/)
- [Abuseipdb Reports Example](https://apis.io/examples/abuseipdb/abuseipdb-reports-example/)

#### Collections (6)

Postman and Open Collection request collections.

- [AbuseIPDB APIv2](https://apis.io/collections/abuseipdb/open-abuseipdb-apiv2/)
- [AbuseIPDB APIv2 Blacklist API](https://apis.io/collections/abuseipdb/open-abuseipdb-blacklist-api/)
- [AbuseIPDB APIv2 Blacklist Management API](https://apis.io/collections/abuseipdb/open-abuseipdb-management-api/)
- [AbuseIPDB APIv2 Blacklist Reports API](https://apis.io/collections/abuseipdb/open-abuseipdb-reports-api/)
- [AbuseIPDB APIv2 Blacklist Reputation API](https://apis.io/collections/abuseipdb/open-abuseipdb-reputation-api/)
- [AbuseIPDB APIv2](https://apis.io/collections/abuseipdb/postman-abuseipdb-apiv2/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [AbuseIPDB — jsonschema rules](https://apis.io/rules/abuseipdb/abuseipdb-jsonschema-spectral-rules/)
- [AbuseIPDB API Rules](https://apis.io/rules/abuseipdb/abuseipdb-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Abuseipdb Authentication](https://apis.io/security/abuseipdb/abuseipdb-authentication/)
- [Abuseipdb Domain Security](https://apis.io/security/abuseipdb/abuseipdb-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Abuseipdb Plans Pricing](https://apis.io/plans/abuseipdb/abuseipdb-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Abuseipdb Rate Limits](https://apis.io/rate-limits/abuseipdb/abuseipdb-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Abuseipdb Finops](https://apis.io/finops/abuseipdb/abuseipdb-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.abuseipdb.com/)
- [Documentation](https://docs.abuseipdb.com/)
- [Pricing](https://www.abuseipdb.com/pricing)
- [Support](https://www.abuseipdb.com/contact)
- [Blog](https://www.abuseipdb.com/blog)
- [Terms of service](https://www.abuseipdb.com/terms-of-service)
- [Privacy policy](https://www.abuseipdb.com/privacy-policy)
- [GitHub](https://github.com/AbuseIPDB)

## API Evangelist rating

**Kin Score 43.2** — developing · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 66.0 |
| Contract governance | 27.3 |
| Operational transparency | 10.5 |
| Developer ergonomics | 51.2 |
| Access clarity | 25.0 |

**Agent readiness 26.4** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | verified |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/abuseipdb/](https://apis.io/providers/abuseipdb/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for AbuseIPDB: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/abuseipdb/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
