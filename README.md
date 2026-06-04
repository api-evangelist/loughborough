# Loughborough University (loughborough)

Loughborough University is a public research university in Leicestershire, United Kingdom, ranked #224 in the QS World University Rankings 2025. This repository catalogs its public developer and API footprint as an [APIs.json](http://apisjson.org/) provider profile. Loughborough does not operate a first-party developer portal; its confirmed programmatic surface is its figshare-powered research repository (REST + OAI-PMH) and a Shibboleth/SAML identity provider for federated single sign-on.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/loughborough/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=loughborough-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, United Kingdom, Research Data, Open Access, Repository, Identity

## APIs

- **Loughborough Research Repository (figshare REST API)** — figshare v2 REST API scoped to the Loughborough institution. Docs: https://docs.figshare.com/ — Base: `https://api.figshare.com/v2/articles?institution=2`
- **Loughborough Research Repository OAI-PMH** — figshare OAI-PMH metadata harvesting endpoint (set `portal_2`). Docs: https://docs.figshare.com/ — Base: `https://api.figshare.com/v2/oai?verb=Identify&set=portal_2`
- **Loughborough Shibboleth/SAML Identity Provider** — federated SSO (UK Access Management Federation); access-controlled, not general developer use. Docs: https://www.lboro.ac.uk/services/it/topics/student-account/

## Plans / Rate Limits / FinOps

- Plans & Pricing: [plans/loughborough-plans-pricing.yml](plans/loughborough-plans-pricing.yml)
- Rate Limits: [rate-limits/loughborough-rate-limits.yml](rate-limits/loughborough-rate-limits.yml)
- FinOps: [finops/loughborough-finops.yml](finops/loughborough-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.lboro.ac.uk/
- GitHub: https://github.com/LoughboroughUniversity
- LinkedIn: https://uk.linkedin.com/school/loughborough-university/
- Repository: https://repository.lboro.ac.uk/

## Notes

- No first-party developer portal or open-data API was found for Loughborough University.
- The research repository programmatic access is provided by figshare, a third party; endpoints above were verified to resolve (200) at review time.
- The official GitHub org exists but lists zero public repositories.
- The Shibboleth/SAML IdP metadata URL is referenced in university documentation but returned a 500 on probe and is federation-gated.
- No endpoints, docs, or properties were fabricated; only verifiable resources are listed.

## Maintainers

- Kin Lane — kin@apievangelist.com
