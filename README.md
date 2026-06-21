# Flipside Crypto (flipside)

Flipside Crypto is a blockchain analytics platform that lets analysts and developers run SQL queries against curated, Snowflake-backed on-chain datasets covering Ethereum, Solana, and 20+ other chains. The Data API exposes query execution and result retrieval over a JSON-RPC-style HTTP interface at api-v2.flipsidecrypto.xyz, authenticated with an x-api-key. In May 2026 Flipside sold its blockchain data business to SonarX and refocused on its edisyl enterprise AI platform; this catalog documents the Flipside Data API as published.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/flipside/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/flipside/refs/heads/main/apis.yml)

## Tags

- Blockchain
- Analytics
- SQL
- Web3
- Data

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Query Execution (SQL)

Submit Snowflake-compatible SQL against curated on-chain datasets, poll execution status, and cancel runs via the JSON-RPC methods createQuery, getQueryRun, and cancelQueryRun over HTTP, authenticated with an x-api-key header.

- **Human URL:** [https://docs.flipsidecrypto.xyz](https://docs.flipsidecrypto.xyz)
- **Base URL:** `https://api-v2.flipsidecrypto.xyz/json-rpc`

#### Tags

- SQL
- Query
- Execution

#### Properties

- [Documentation](https://docs.flipsidecrypto.xyz)
- [API Reference](https://docs.flipsidecrypto.xyz/data/data-products/api-sdk-developers/get-started/run-your-first-query)
- [OpenAPI](openapi/flipside-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flipside.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flipside.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Query Results

Retrieve paginated query results with column names, types, rows, and run metadata via the JSON-RPC getQueryRunResults method, with configurable page size, page number, and result format (CSV or JSON).

- **Human URL:** [https://docs.flipsidecrypto.xyz](https://docs.flipsidecrypto.xyz)
- **Base URL:** `https://api-v2.flipsidecrypto.xyz/json-rpc`

#### Tags

- Results
- Pagination
- Data

#### Properties

- [Documentation](https://docs.flipsidecrypto.xyz)
- [API Reference](https://docs.flipsidecrypto.xyz/data/data-products/api-sdk-developers/get-started/run-your-first-query)
- [OpenAPI](openapi/flipside-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flipside.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flipside.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datasets

Curated, Snowflake-backed blockchain datasets spanning Ethereum, Solana, Arbitrum, Polygon, and 20+ other chains, queried through the same JSON-RPC SQL interface using the snowflake-default data source and flipside data provider.

- **Human URL:** [https://docs.flipsidecrypto.xyz](https://docs.flipsidecrypto.xyz)
- **Base URL:** `https://api-v2.flipsidecrypto.xyz/json-rpc`

#### Tags

- Datasets
- Snowflake
- On-Chain

#### Properties

- [Documentation](https://docs.flipsidecrypto.xyz)
- [Documentation](https://flipsidecrypto.xyz/blockchain-data/)
- [OpenAPI](openapi/flipside-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flipside.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flipside.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/FlipsideCrypto)
- [LinkedIn](https://www.linkedin.com/company/flipside-crypto)
- [Website](https://flipsidecrypto.xyz)
- [Documentation](https://docs.flipsidecrypto.xyz)
- [Plans](plans/flipside-plans-pricing.yml)
- [Rate Limits](rate-limits/flipside-rate-limits.yml)
- [Fin Ops](finops/flipside-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
