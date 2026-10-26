# Flipside Crypto (flipside)

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
