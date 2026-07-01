# Mobula (mobula)

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
