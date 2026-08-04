# Privy (privy)

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
