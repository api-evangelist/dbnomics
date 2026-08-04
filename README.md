# DBnomics (dbnomics)

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

DBnomics is the world's economic database - a free, open-source aggregator run by Cepremap that harvests macroeconomic time series from more than 90 national and international providers (IMF, ECB, Eurostat, World Bank, OECD, BLS, BEA, Banque de France, Federal Statistical Office Germany, and many more) into one standardized format. Hundreds of millions of series covering economic indicators, government statistics, prices, employment, trade, and finance are refreshed daily and served through a documented public REST API (`api.db.nomics.world/v22`) that requires **no API key or authentication**, plus official Python and R clients and community clients for Julia, Matlab, Stata, EViews, and Gretl. The entire platform - API, per-provider fetchers, and tooling - is open source on Cepremap's GitLab (git.nomics.world, mirrored at github.com/dbnomics) and is sustained as a digital public good with sponsorship from French public institutions. There are no paid tiers and no billing; access is free for everyone.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/dbnomics/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/dbnomics/refs/heads/main/apis.yml)

## Tags

- Economic Indicators
- Macroeconomics
- Open Data
- Statistics
- Time Series
- Government Data

## Timestamps

- **Created:** 2026-07-11
- **Modified:** 2026-07-11

## APIs

### DBnomics Providers API

List the 90+ statistical agencies, central banks, and international institutions aggregated by DBnomics, or retrieve a single provider with its full category tree of datasets. No authentication required.

- **Human URL:** [https://api.db.nomics.world/v22/apidocs](https://api.db.nomics.world/v22/apidocs)
- **Base URL:** `https://api.db.nomics.world/v22`

#### Tags

- Providers
- Data Sources
- Statistics

#### Properties

- [Documentation](https://docs.db.nomics.world/)
- [API Reference](https://api.db.nomics.world/v22/apidocs)
- [OpenAPI](openapi/dbnomics-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dbnomics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dbnomics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### DBnomics Datasets API

Retrieve dataset metadata for any provider - one dataset or the paginated list of a provider's datasets, including dimensions, series counts, and update timestamps - plus a last-updates feed of the most recently refreshed providers and datasets across the whole database.

- **Human URL:** [https://api.db.nomics.world/v22/apidocs](https://api.db.nomics.world/v22/apidocs)
- **Base URL:** `https://api.db.nomics.world/v22`

#### Tags

- Datasets
- Economic Indicators
- Government Reports

#### Properties

- [Documentation](https://docs.db.nomics.world/)
- [API Reference](https://api.db.nomics.world/v22/apidocs)
- [OpenAPI](openapi/dbnomics-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dbnomics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dbnomics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### DBnomics Series API

Fetch economic time series and their observations - by explicit series IDs across providers, by provider and dataset with dimension filters or series-code masks, or as a single series - with JSON or CSV output, period alignment, facets, and metadata options.

- **Human URL:** [https://api.db.nomics.world/v22/apidocs](https://api.db.nomics.world/v22/apidocs)
- **Base URL:** `https://api.db.nomics.world/v22`

#### Tags

- Time Series
- Observations
- Macroeconomics

#### Properties

- [Documentation](https://docs.db.nomics.world/)
- [API Reference](https://api.db.nomics.world/v22/apidocs)
- [OpenAPI](openapi/dbnomics-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dbnomics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dbnomics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### DBnomics Search API

Full-text search across every dataset aggregated by DBnomics - find economic indicators, government statistics, and macroeconomic series by keyword with simple limit/offset pagination.

- **Human URL:** [https://api.db.nomics.world/v22/apidocs](https://api.db.nomics.world/v22/apidocs)
- **Base URL:** `https://api.db.nomics.world/v22`

#### Tags

- Search
- Discovery
- Open Data

#### Properties

- [Documentation](https://docs.db.nomics.world/)
- [API Reference](https://api.db.nomics.world/v22/apidocs)
- [OpenAPI](openapi/dbnomics-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dbnomics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dbnomics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://db.nomics.world)
- [Documentation](https://docs.db.nomics.world)
- [GitHub Organization](https://github.com/dbnomics)
- [Plans](plans/dbnomics-plans-pricing.yml)
- [Rate Limits](rate-limits/dbnomics-rate-limits.yml)
- [Fin Ops](finops/dbnomics-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
