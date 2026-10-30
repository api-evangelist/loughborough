# Loughborough University

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

Loughborough University is a public research university in Leicestershire, United Kingdom, a member of the Midlands Innovation group, established 1909 and best known for sport science, engineering and design. It publishes no central developer portal, no open-data portal and no first-party OpenAPI, and no such thing was generated for it here. Two surfaces are unambiguously the university's own and are recorded as such: a self-hosted Moodle ("Learn") on Loughborough's own address space running as a 1EdTech LTI 1.3 Advantage platform with a publicly readable JWKS, and a SimpleSAMLphp SAML 2.0 Identity Provider registered in the UK Access Management Federation. Five more carry Loughborough's data on someone else's platform and are recorded as tenancies: a Koha library system whose REST API serves a live Swagger 2.0 description and nineteen keyless /public endpoints — the single most usable programmable surface the institution has, and hosted by PTFS Europe; a VuFind discovery layer whose Search API is deployed but closed; the Loughborough Research Repository, a figshare tenancy; Talis Aspire reading lists; and Springshare LibCal. Loughborough is also a DataCite member in its own right. No contract is stored under this slug, because none of the contracts are Loughborough's to claim.

**Areas:** Education · Higher Education · University · United Kingdom · Library · Library Catalog · Identity Federation · LMS · Research Data · Open Access · Repository

## Loughborough University on APIs.io

Everything profiled for Loughborough University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/loughborough/](https://apis.io/providers/loughborough/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [Loughborough University Library Catalogue API (Koha)](https://apis.io/apis/loughborough/library-catalogue-api/) — The REST API of Loughborough University Library's Koha integrated library system, served from the university's own koha.lboro.ac.uk host. The live…
- [Loughborough Learn — LTI 1.3 Advantage Platform (Moodle)](https://apis.io/apis/loughborough/learn-lti-platform/) — Loughborough's virtual learning environment, "Learn", is a Moodle instance self-hosted at learn.lboro.ac.uk in the university's own 158.125.161.0/24 address…
- [Loughborough University SAML 2.0 Identity Provider](https://apis.io/apis/loughborough/identity-federation/) — Loughborough operates its own SAML 2.0 Identity Provider — SimpleSAMLphp, Loughborough-branded, at idp.lboro.ac.uk — and is registered in the UK Access…
- [Loughborough University Library Discovery (VuFind)](https://apis.io/apis/loughborough/vufind-discovery/) — VuFind discovery layer at vufind.lboro.ac.uk, the public search interface over the Koha catalogue, on managed hosting by PTFS Europe (CNAME…
- [Loughborough University Research Repository (figshare tenancy)](https://apis.io/apis/loughborough/research-repository/) — The Loughborough Research Repository is the university's institutional repository for all research outputs, and it is a figshare tenancy:…
- [Loughborough University Reading Lists (Talis Aspire tenancy)](https://apis.io/apis/loughborough/reading-lists/) — Loughborough's reading lists run on Talis Aspire at lboro.rl.talis.com. The tenancy exposes linked data: https://lboro.rl.talis.com/index.json returns 200…
- [Loughborough University Library Hours and Bookings (Springshare LibCal tenancy)](https://apis.io/apis/loughborough/libcal/) — Room booking, opening hours and library event data run on Springshare LibCal at libcal.lboro.ac.uk (CNAME region-eu.libcal.com). The legacy keyless widget…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Vocabulary (1)

The provider's domain terms, defined.

- [Loughborough Research Repository Vocabulary](https://apis.io/vocabularies/loughborough/loughborough-vocabulary/)

#### Examples (2)

Example requests and responses.

- [Loughborough Koha Public Libraries Example](https://apis.io/examples/loughborough/loughborough-koha-public-libraries-example/)
- [Loughborough Moodle Lti Jwks Example](https://apis.io/examples/loughborough/loughborough-moodle-lti-jwks-example/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Loughborough Domain Security](https://apis.io/security/loughborough/loughborough-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Loughborough Plans Pricing](https://apis.io/plans/loughborough/loughborough-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Loughborough Rate Limits](https://apis.io/rate-limits/loughborough/loughborough-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Loughborough Finops](https://apis.io/finops/loughborough/loughborough-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.lboro.ac.uk/)
- [Documentation](https://www.lboro.ac.uk/services/library/research-support/)
- [Support](https://www.lboro.ac.uk/services/it/)
- [Blog](https://www.lboro.ac.uk/news-events/rss/)
- [Terms of service](https://www.lboro.ac.uk/disclaimer/)
- [Privacy policy](https://www.lboro.ac.uk/privacy/)
- [GitHub](https://github.com/LoughboroughUniversity)

## API Evangelist rating

**Kin Score 19.3** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 4.4 |
| Contract governance | 0.0 |
| Operational transparency | 7.9 |
| Developer ergonomics | 23.8 |
| Access clarity | 26.3 |

**Agent readiness 0.6** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
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

**Regulatory alignment 18.6** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/loughborough/](https://apis.io/providers/loughborough/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Loughborough University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/loughborough/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
