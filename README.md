# University of Padua (university-of-padua)

The University of Padua (Università degli Studi di Padova) is a public research university in Padua, Italy, founded in 1222 and ranked #236 in the QS World University Rankings 2025. This repository catalogs its public developer/API footprint as an APIs.json provider profile. The university has no single official developer portal; its documented programmatic surfaces are concentrated in the University Library System (SBA) — PHAIDRA digital collections (REST/OpenAPI, IIIF, OAI-PMH) and the EPrints-based Padua@Research and Research Data Unipd repositories (OAI-PMH) — plus a Shibboleth/SAML Single Sign-On.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-padua/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-padua-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Open Data, Research Data, Library, Repository, Italy

## APIs

- **PHAIDRA Digital Collections REST API** — REST API (OpenAPI) for the library's digital objects and collections. Docs: https://phaidra.cab.unipd.it/api/openapi
- **PHAIDRA IIIF Image API** — IIIF image server for digital collections. Docs: https://phaidra.cab.unipd.it/api/openapi
- **PHAIDRA OAI-PMH** — Metadata harvesting endpoint. Docs: https://phaidra.cab.unipd.it/api/oai?verb=Identify
- **Padua@Research OAI-PMH** — EPrints institutional repository OAI-PMH 2.0. Docs: https://paduaresearch.cab.unipd.it/cgi/oai2?verb=Identify
- **Research Data Unipd OAI-PMH** — EPrints research-data archive OAI-PMH 2.0 (OpenAIRE provider). Docs: https://researchdata.cab.unipd.it/cgi/oai2?verb=Identify
- **Single Sign-On (Shibboleth/SAML)** — Federated identity via IDEM GARR / eduGAIN. Docs: https://asit.unipd.it/single-sign-informazioni-tecniche-service-provider

## Plans

- [plans/university-of-padua-plans-pricing.yml](plans/university-of-padua-plans-pricing.yml)

## Rate Limits

- [rate-limits/university-of-padua-rate-limits.yml](rate-limits/university-of-padua-rate-limits.yml)

## FinOps

- [finops/university-of-padua-finops.yml](finops/university-of-padua-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.unipd.it/en
- Library: https://biblio.unipd.it/en
- LinkedIn: https://it.linkedin.com/school/university-of-padova/
- Authentication: https://asit.unipd.it/single-sign-informazioni-tecniche-service-provider
- Plans, Rate Limits, FinOps, and Review pointers (see files above)

## Notes

- All API endpoints listed were probed live on 2026-06-03 and returned HTTP 200 (PHAIDRA REST/OpenAPI/IIIF/OAI, Padua@Research OAI-PMH, Research Data Unipd OAI-PMH). No endpoints were fabricated.
- The bare `https://phaidra.cab.unipd.it/api` path returns 404; the documented entry point is `/api/openapi` with named routes.
- There is no central official GitHub organization for the University of Padua as a whole. Public code is found only in individual lab/department/student orgs (e.g., SIGNET Lab, BioComputingUP), so GitHub is intentionally omitted from common properties.
- The Shibboleth/SAML SSO is federated institutional identity infrastructure, not a self-service public API.

## Maintainers

- Kin Lane — kin@apievangelist.com
