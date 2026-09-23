# Examples — provenance

generated: 2026-09-01
method: probed
source: Captured verbatim from live, anonymous, unauthenticated requests by API Evangelist on
2026-09-01. These are real response bodies, not fabricated samples, and none of them was
published as an example by the University of Lausanne.

| file | request |
|---|---|
| `university-of-lausanne-oai-identify-example.xml` | `GET https://api.unil.ch/iris/server/oai/request?verb=Identify` |
| `university-of-lausanne-oai-listsets-example.xml` | `GET https://api.unil.ch/iris/server/oai/request?verb=ListSets` |
| `university-of-lausanne-oai-listmetadataformats-example.xml` | `GET https://api.unil.ch/iris/server/oai/request?verb=ListMetadataFormats` |
| `university-of-lausanne-listCollections-example.json` | `GET https://api.unil.ch/iris/server/api/core/collections?size=2` |
| `university-of-lausanne-searchObjects-example.json` | `GET https://api.unil.ch/iris/server/api/discover/search/objects?size=1` |
| `university-of-lausanne-shibboleth-idp-metadata-example.xml` | `GET https://metadata.aai.switch.ch/entities/https%3A%2F%2Faai.unil.ch%2Fidp%2Fshibboleth` (SWITCHaai MDQ, carrying UNIL's own IdP EntityDescriptor) |
| `university-of-lausanne-datacite-client-example.json` | `GET https://api.datacite.org/clients/pwkb.pgdjam` (UNIL's DataCite repository registration; the contract is DataCite's, the membership is UNIL's) |
| `university-of-lausanne-listCommunities-example.json` | `GET https://api.unil.ch/iris/server/api/core/communities` (captured 2026-06-03) |
| `university-of-lausanne-queryProjects-example.json` | `GET https://spica.unil.ch/projects/query.json` (captured 2026-06-03) |
