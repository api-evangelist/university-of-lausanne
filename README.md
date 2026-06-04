# University of Lausanne (university-of-lausanne)

The University of Lausanne (UNIL) is a public research university in Lausanne, Switzerland, ranked #224 in the QS World University Rankings 2025. This repository catalogs UNIL's public developer/API footprint as an APIs.json provider profile for the API Evangelist network.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-lausanne/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-lausanne-api-evangelist&utm_content=repo

## Type

Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Switzerland, Open Science, Research Data, Institutional Repository

## APIs

- **SPICA Atlas API** — Public JSON API for the SPICA single-cell / spatial atlas (list/filter/search projects, download archives). Docs: https://spica.unil.ch/home/api
- **IRIS Repository (DSpace REST API)** — Public DSpace 7 REST/HATEOAS API (v1.3.8) for UNIL's IRIS institutional repository. Base: https://api.unil.ch/iris/server/api — UI: https://iris.unil.ch

## Plans / Rate Limits / FinOps

- Plans: [plans/university-of-lausanne-plans-pricing.yml](plans/university-of-lausanne-plans-pricing.yml)
- Rate Limits: [rate-limits/university-of-lausanne-rate-limits.yml](rate-limits/university-of-lausanne-rate-limits.yml)
- FinOps: [finops/university-of-lausanne-finops.yml](finops/university-of-lausanne-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.unil.ch
- GitHub: https://github.com/openscienceunil
- LinkedIn: https://www.linkedin.com/school/university-of-lausanne/
- Authentication: https://my.unil.ch/

## Notes

All cataloged endpoints were probed live on 2026-06-03. SPICA and IRIS are public and documented; the IRIS items endpoint requires authentication and no OAI-PMH endpoint was found. Most institutional/student-information APIs sit behind the my.unil.ch authentication gateway and a Kong API gateway, with no public documentation. The `github.com/unil` org is unrelated to the university; `openscienceunil` is the relevant org but hosts coursework rather than API specifications. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
