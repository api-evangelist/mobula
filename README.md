# Mobula (mobula)

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

Mobula is an onchain-native crypto and web3 market data provider. Its REST and WebSocket APIs serve real-time and historical token prices, asset and token metadata, trading pairs and OHLCV candles, and multichain wallet portfolio, net-worth history, and transaction data across EVM, Solana, TON, and other chains, all keyed off a single free API key.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/mobula/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/mobula/refs/heads/main/apis.yml)

## Tags

- Crypto
- Web3
- Market Data
- Blockchain
- Wallet
- Real Time

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### Mobula Market Data API

Real-time market data for any token by asset name, symbol, id, or contract address (with blockchain), returning price, market cap, diluted market cap, volume, liquidity, ATH/ATL, multi-timeframe price change, and contract details.

- **Human URL:** [https://docs.mobula.io/rest-api-reference/endpoint/market-data](https://docs.mobula.io/rest-api-reference/endpoint/market-data)
- **Base URL:** `https://api.mobula.io/api/1`

#### Tags

- Market Data
- Price
- Crypto

#### Properties

- [Documentation](https://docs.mobula.io/rest-api-reference/endpoint/market-data)
- [API Reference](https://docs.mobula.io/rest-api-reference/introduction)
- [OpenAPI](openapi/mobula-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mobula.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mobula.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mobula Multi-Data API

Batched market data for many assets in a single request via comma-separated asset names or contract addresses, returning the same market payload per asset for efficient multi-token dashboards.

- **Human URL:** [https://docs.mobula.io/rest-api-reference/introduction](https://docs.mobula.io/rest-api-reference/introduction)
- **Base URL:** `https://api.mobula.io/api/1`

#### Tags

- Market Data
- Batch
- Price

#### Properties

- [Documentation](https://docs.mobula.io/rest-api-reference/introduction)
- [OpenAPI](openapi/mobula-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mobula.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mobula.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mobula Market History API

Historical price time series for an asset over a from/to range at a chosen granularity, returning ordered [timestamp, price] points for charting and backtesting.

- **Human URL:** [https://docs.mobula.io/rest-api-reference/introduction](https://docs.mobula.io/rest-api-reference/introduction)
- **Base URL:** `https://api.mobula.io/api/1`

#### Tags

- History
- Time Series
- Price

#### Properties

- [Documentation](https://docs.mobula.io/rest-api-reference/introduction)
- [OpenAPI](openapi/mobula-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mobula.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mobula.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mobula Pairs and OHLCV API

Trading pairs for a token across DEXes plus OHLCV (open/high/low/close/volume) candle history per pair, keyed by asset or pair address, blockchain, and period.

- **Human URL:** [https://docs.mobula.io/rest-api-reference/introduction](https://docs.mobula.io/rest-api-reference/introduction)
- **Base URL:** `https://api.mobula.io/api/1`

#### Tags

- Pairs
- OHLCV
- Candles

#### Properties

- [Documentation](https://docs.mobula.io/rest-api-reference/introduction)
- [OpenAPI](openapi/mobula-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mobula.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mobula.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mobula Metadata API

On-chain asset and token metadata - name, symbol, logo, description, website and social links, categories, and multichain contract addresses with decimals.

- **Human URL:** [https://docs.mobula.io/rest-api-reference/introduction](https://docs.mobula.io/rest-api-reference/introduction)
- **Base URL:** `https://api.mobula.io/api/1`

#### Tags

- Metadata
- Assets
- Tokens

#### Properties

- [Documentation](https://docs.mobula.io/rest-api-reference/introduction)
- [OpenAPI](openapi/mobula-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mobula.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mobula.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mobula Wallet Portfolio API

Full multichain portfolio for one or more wallet addresses - total balance, per-asset token balances, USD estimates, allocations, cross-chain holdings, and optional realized/unrealized PnL.

- **Human URL:** [https://docs.mobula.io/rest-api-reference/endpoint/wallet-portfolio](https://docs.mobula.io/rest-api-reference/endpoint/wallet-portfolio)
- **Base URL:** `https://api.mobula.io/api/1`

#### Tags

- Wallet
- Portfolio
- Multichain

#### Properties

- [Documentation](https://docs.mobula.io/rest-api-reference/endpoint/wallet-portfolio)
- [OpenAPI](openapi/mobula-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mobula.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mobula.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mobula Wallet History and Transactions API

Historical net-worth time series for a wallet plus a normalized, decoded transaction and transfer feed across chains, filterable by blockchains and time range.

- **Human URL:** [https://docs.mobula.io/rest-api-reference/introduction](https://docs.mobula.io/rest-api-reference/introduction)
- **Base URL:** `https://api.mobula.io/api/1`

#### Tags

- Wallet
- History
- Transactions

#### Properties

- [Documentation](https://docs.mobula.io/rest-api-reference/introduction)
- [OpenAPI](openapi/mobula-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mobula.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mobula.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mobula Search and Query API

Universal search over tokens, assets, and wallets by name, symbol, or address, plus a filterable market query for screening assets by liquidity, volume, market cap, and other criteria.

- **Human URL:** [https://docs.mobula.io/rest-api-reference/introduction](https://docs.mobula.io/rest-api-reference/introduction)
- **Base URL:** `https://api.mobula.io/api/1`

#### Tags

- Search
- Query
- Discovery

#### Properties

- [Documentation](https://docs.mobula.io/rest-api-reference/introduction)
- [OpenAPI](openapi/mobula-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mobula.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mobula.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mobula Realtime Feed API

WebSocket streams for live price, volume, and market metrics across up to 100 assets, plus wallet-portfolio balance updates, pushed roughly every 5 seconds with no caching. Available on Growth and Enterprise plans.

- **Human URL:** [https://docs.mobula.io/indexing-stream/stream/websocket/wss-market-data](https://docs.mobula.io/indexing-stream/stream/websocket/wss-market-data)
- **Base URL:** `wss://api.mobula.io`

#### Tags

- Real Time
- WebSocket
- Streaming

#### Properties

- [Documentation](https://docs.mobula.io/indexing-stream/stream/websocket/wss-market-data)
- [OpenAPI](openapi/mobula-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [AsyncAPI](asyncapi/mobula-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

## Common Properties

- [GitHub Organization](https://github.com/mobula-io)
- [LinkedIn](https://www.linkedin.com/company/mobula)
- [Website](https://mobula.io/)
- [Documentation](https://docs.mobula.io)
- [Plans](plans/mobula-plans-pricing.yml)
- [Rate Limits](rate-limits/mobula-rate-limits.yml)
- [Fin Ops](finops/mobula-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
