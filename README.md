# Privy (privy)

Privy is a wallet and authentication platform for Web3 apps offering embedded wallets, server wallets, and progressive authentication. Provides client SDKs (React, React Native, Swift, Android, Unity, Node, Go, Python) plus a public REST API for wallet, user, and transaction operations.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/privy/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/privy/refs/heads/main/apis.yml)

## Tags

- Web3
- Wallets
- Authentication
- Embedded Wallets
- MPC

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Privy REST API

REST API for managing users, wallets, sessions, transactions, and policies. Endpoints include /v1/users, /v1/wallets, wallet RPC, signing, and transaction sending across EVM and Solana.

- **Human URL:** [https://docs.privy.io/api-reference/introduction](https://docs.privy.io/api-reference/introduction)
- **Base URL:** `https://api.privy.io/v1`

#### Tags

- REST
- Wallets
- Users
- Auth

#### Properties

- [Documentation](https://docs.privy.io/api-reference/introduction)
- [Postman Collection](collections/privy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/privy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Privy Wallets RPC

JSON-RPC method passthrough for signing transactions and arbitrary RPC calls against Privy-managed wallets.

- **Human URL:** [https://docs.privy.io/api-reference/wallets/rpc](https://docs.privy.io/api-reference/wallets/rpc)
- **Base URL:** `https://api.privy.io/v1/wallets/{walletId}/rpc`

#### Tags

- JSON-RPC
- Wallet

#### Properties

- [Documentation](https://docs.privy.io/api-reference/wallets/rpc)
- [Postman Collection](collections/privy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/privy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Privy Webhooks

Webhook delivery of user, wallet, and transaction events. Subscriptions managed via the dashboard and REST API.

- **Human URL:** [https://docs.privy.io/recipes/webhooks](https://docs.privy.io/recipes/webhooks)
- **Base URL:** `https://api.privy.io/v1`

#### Tags

- Webhooks

#### Properties

- [Documentation](https://docs.privy.io/recipes/webhooks)
- [Postman Collection](collections/privy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/privy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/privy-io)
- [LinkedIn](https://www.linkedin.com/company/privyio)
- [Website](https://www.privy.io/)
- [Plans](plans/privy-plans-pricing.yml)
- [Rate Limits](rate-limits/privy-rate-limits.yml)
- [Fin Ops](finops/privy-finops.yml)
- [L L Ms Txt](https://docs.privy.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
