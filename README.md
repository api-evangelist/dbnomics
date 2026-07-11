# DBnomics (dbnomics)

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
