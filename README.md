# University of Lausanne

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

The University of Lausanne (UNIL) is a public research university in Lausanne, Switzerland, founded in 1537, with roughly 17,000 students across seven faculties and ROR identifier https://ror.org/019whta54. UNIL publishes no developer portal, no API key programme, no API terms and no changelog, and no central catalogue of its own interfaces exists — but unlike most of this cohort its small programmable footprint is genuinely its own rather than a vendor's contract wearing its name. Three surfaces answer anonymously on UNIL's own registrable domain: the SPICA single-cell / spatial atlas JSON API at spica.unil.ch; the IRIS institutional research repository's DSpace-CRIS REST API at api.unil.ch/iris/server/api, behind a Kong gateway, with 253,799 indexed objects reachable through Discovery search while /core/items and /core/bitstreams answer 401; and two anonymous OAI-PMH 2.0 harvesting contexts on the same host, one of them declaring OpenAIRE Guidelines for CRIS Managers v1.1. Beyond the contracts, UNIL operates its own Shibboleth identity provider (entityID https://aai.unil.ch/idp/shibboleth, scope unil.ch) registered in SWITCHaai and exported to eduGAIN, and holds a DataCite repository registration minting DOIs under prefix 10.48657. Everything else — student information, timetables, course registration — sits behind the my.unil.ch SSO gateway and is not documented as an API anywhere. No OpenAPI, AsyncAPI or MCP server is published by UNIL itself; every contract in this repository was written by API Evangelist from live probes and is marked as such.

**Areas:** Education · Higher Education · University · Switzerland · Open Science · Research Data · Institutional Repository · Research Repository · Identity Federation · OAI-PMH · Course Catalog · Research Computing

## University of Lausanne on APIs.io

Everything profiled for University of Lausanne is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/university-of-lausanne/](https://apis.io/providers/university-of-lausanne/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [SPICA Atlas Projects.json API](https://apis.io/apis/university-of-lausanne/university-of-lausanne-projects-json-api/) — The SPICA single-cell / spatial atlas project listing, on UNIL's own host spica.unil.ch. Anonymous open read, confirmed 200 on 2026-09-01. SPICA is…
- [SPICA Atlas Projects API](https://apis.io/apis/university-of-lausanne/university-of-lausanne-projects-api/) — SPICA project query and archive download on UNIL's own host: filter by reference atlas (ref_id), free-text search across metadata and paginate.…
- [IRIS Repository Core API (DSpace REST)](https://apis.io/apis/university-of-lausanne/university-of-lausanne-core-api/) — Community and collection resources of IRIS, UNIL's institutional research information system and open-access repository, served from UNIL's own host…
- [IRIS Repository Discover API (DSpace Discovery)](https://apis.io/apis/university-of-lausanne/university-of-lausanne-discover-api/) — DSpace Discovery search across everything indexed in IRIS. Confirmed anonymous 200 on 2026-09-01, reporting a last page of 253,798 at size=1, i.e. 253,799…
- [IRIS Repository API root (DSpace REST)](https://apis.io/apis/university-of-lausanne/university-of-lausanne-iris-repository-dspace-rest-api-api/) — The IRIS DSpace REST root document, exposing version metadata and a HAL hypermedia catalogue of 92 link relations. On 2026-09-01 it reported irisVersion…
- [UNIL Shibboleth Identity Provider (SAML 2.0 metadata)](https://apis.io/apis/university-of-lausanne/unil-shibboleth-idp/) — UNIL's own Shibboleth identity provider, entityID https://aai.unil.ch/idp/shibboleth, carrying an IDPSSODescriptor with OrganizationName "unil.ch",…
- [DataCite repository registration (UNIL data service)](https://apis.io/apis/university-of-lausanne/datacite-repository-registration/) — UNIL's membership of the DataCite DOI registry, not DataCite's contract. api.datacite.org/clients?query=unil returns client PWKB.PGDJAM, name "Old DOIs…
- [ROR organisation registration](https://apis.io/apis/university-of-lausanne/ror-registration/) — UNIL's entry in the Research Organization Registry, https://ror.org/019whta54, established 1537, domain unil.ch, cross-walked to Fundref 501100006390, GRID…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [University Of Lausanne Agentic Access](https://apis.io/agentic-access/university-of-lausanne/university-of-lausanne-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [DSpace Community](https://apis.io/schemas/university-of-lausanne/university-of-lausanne-community/)
- [SPICA Project](https://apis.io/schemas/university-of-lausanne/university-of-lausanne-project/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [University Of Lausanne Community Structure](https://apis.io/json-structure/university-of-lausanne/university-of-lausanne-community-structure/)
- [University Of Lausanne Project Structure](https://apis.io/json-structure/university-of-lausanne/university-of-lausanne-project-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [University Of Lausanne Context](https://apis.io/jsonld/university-of-lausanne/university-of-lausanne-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [University of Lausanne API Vocabulary](https://apis.io/vocabularies/university-of-lausanne/university-of-lausanne-vocabulary/)

#### Examples (5)

Example requests and responses.

- [University Of Lausanne Datacite Client Example](https://apis.io/examples/university-of-lausanne/university-of-lausanne-datacite-client-example/)
- [University Of Lausanne Listcollections Example](https://apis.io/examples/university-of-lausanne/university-of-lausanne-listCollections-example/)
- [University Of Lausanne Listcommunities Example](https://apis.io/examples/university-of-lausanne/university-of-lausanne-listCommunities-example/)
- [University Of Lausanne Queryprojects Example](https://apis.io/examples/university-of-lausanne/university-of-lausanne-queryProjects-example/)
- [University Of Lausanne Searchobjects Example](https://apis.io/examples/university-of-lausanne/university-of-lausanne-searchObjects-example/)

#### Collections (4)

Postman and Open Collection request collections.

- [IRIS Repository (DSpace REST API) Core API](https://apis.io/collections/university-of-lausanne/open-university-of-lausanne-core-api/)
- [IRIS Repository (DSpace REST API) Core IRIS Repository (DSpace REST API) API](https://apis.io/collections/university-of-lausanne/open-university-of-lausanne-iris-repository-dspace-rest-api-api/)
- [IRIS Repository (DSpace REST API) Core Projects API](https://apis.io/collections/university-of-lausanne/open-university-of-lausanne-projects-api/)
- [IRIS Repository (DSpace REST API) Core Projects.json API](https://apis.io/collections/university-of-lausanne/open-university-of-lausanne-projects-json-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [University of Lausanne — jsonschema rules](https://apis.io/rules/university-of-lausanne/university-of-lausanne-jsonschema-spectral-rules/)
- [University of Lausanne API Rules](https://apis.io/rules/university-of-lausanne/university-of-lausanne-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [University Of Lausanne Authentication](https://apis.io/security/university-of-lausanne/university-of-lausanne-authentication/)
- [University Of Lausanne Domain Security](https://apis.io/security/university-of-lausanne/university-of-lausanne-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [University Of Lausanne Plans Pricing](https://apis.io/plans/university-of-lausanne/university-of-lausanne-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [University Of Lausanne Rate Limits](https://apis.io/rate-limits/university-of-lausanne/university-of-lausanne-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [University Of Lausanne Finops](https://apis.io/finops/university-of-lausanne/university-of-lausanne-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.unil.ch)
- [Documentation](https://spica.unil.ch/home/api)
- [API reference](https://api.unil.ch/iris/server/api)
- [Support](https://www.unil.ch/ci/en/home/menuinst/catalogue-de-services/support-et-formation/help-desk.html)
- [Blog](https://news.unil.ch/)
- [Terms of service](https://www.unil.ch/unil/en/home/termes/conditions/informations-legales.html)
- [Privacy policy](https://www.unil.ch/unil/en/home/termes/conditions/protection-des-donnees.html)
- [GitHub](https://github.com/openscienceunil)

## API Evangelist rating

**Kin Score 45.0** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 82.1 |
| Contract quality | 53.8 |
| Contract governance | 35.6 |
| Operational transparency | 18.4 |
| Developer ergonomics | 33.3 |
| Access clarity | 39.5 |

**Agent readiness 28.2** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |

**Regulatory alignment 32.4** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/university-of-lausanne/](https://apis.io/providers/university-of-lausanne/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for University of Lausanne: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/university-of-lausanne/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
