# Sui

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

Sui is a next-generation Move-based blockchain developed by Mysten Labs, designed for high throughput, low latency, and an asset-oriented programming model. It provides gRPC, GraphQL, and legacy JSON-RPC interfaces for querying objects, transactions, checkpoints, events, and balances on the Sui network. The gRPC API is the current recommended interface, replacing the deprecated JSON-RPC, while GraphQL RPC offers flexible reads for frontends and dashboards.

**Areas:** Blockchain · Move · Web3 · Cryptocurrency · Smart Contracts · Sui

## Sui on APIs.io

Everything profiled for Sui is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/sui/](https://apis.io/providers/sui/)** — or go straight to one of the APIs or properties below.

### APIs (11)

- [Sui GraphQL RPC](https://apis.io/apis/sui/sui-graphql-rpc/) — A generally available RPC service for flexible reads, transaction submission, and simulation backed by the Sui General-Purpose Indexer, Consistent Store,…
- [Sui JSON-RPC API (Deprecated)](https://apis.io/apis/sui/sui-json-rpc-api-deprecated/) — The legacy JSON-RPC API for interacting with Sui full nodes, providing methods for querying objects, transactions, checkpoints, events, balances, and coin…
- [Sui Coin Query API](https://apis.io/apis/sui/sui-coin-query-api-api/) — The Coin Query API API from Sui — 6 operation(s) for coin query api.
- [Sui Extended API](https://apis.io/apis/sui/sui-extended-api-api/) — Extended query methods (suix_ prefix)
- [Sui Governance Read API](https://apis.io/apis/sui/sui-governance-read-api-api/) — The Governance Read API API from Sui — 6 operation(s) for governance read api.
- [Sui Move Utils API](https://apis.io/apis/sui/sui-move-utils-api/) — The Move Utils API from Sui — 5 operation(s) for move utils.
- [Sui PubSub API](https://apis.io/apis/sui/sui-pubsub-api/) — The PubSub API from Sui — 2 operation(s) for pubsub.
- [Sui Read API](https://apis.io/apis/sui/sui-read-api-api/) — Methods for reading blockchain state
- [Sui Transaction Builder API](https://apis.io/apis/sui/sui-transaction-builder-api-api/) — The Transaction Builder API API from Sui — 13 operation(s) for transaction builder api.
- [Sui Websocket API](https://apis.io/apis/sui/sui-websocket-api/) — The Websocket API from Sui — 2 operation(s) for websocket.
- [Sui Write API](https://apis.io/apis/sui/sui-write-api-api/) — Methods for submitting transactions

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### GraphQL (1)

GraphQL schemas.

- [Sui GraphQL API](https://apis.io/graphqls/sui/sui-graphql/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Sui Agentic Access](https://apis.io/agentic-access/sui/sui-agentic-access/)

#### JSON Schema (7)

The data models the API reads and writes.

- [Balance](https://apis.io/schemas/sui/Balance/)
- [Checkpoint](https://apis.io/schemas/sui/Checkpoint/)
- [Coin](https://apis.io/schemas/sui/Coin/)
- [CommitteeInfo](https://apis.io/schemas/sui/CommitteeInfo/)
- [DelegatedStake](https://apis.io/schemas/sui/DelegatedStake/)
- [TransactionBlockResponse](https://apis.io/schemas/sui/TransactionBlockResponse/)
- [Sui JSON-RPC Schemas](https://apis.io/schemas/sui/sui-schemas/)

#### Examples (8)

Example requests and responses.

- [All Methods](https://apis.io/examples/sui/all-methods/)
- [Checkpoints](https://apis.io/examples/sui/checkpoints/)
- [Coins](https://apis.io/examples/sui/coins/)
- [Events](https://apis.io/examples/sui/events/)
- [Move](https://apis.io/examples/sui/move/)
- [Objects](https://apis.io/examples/sui/objects/)
- [Staking](https://apis.io/examples/sui/staking/)
- [Transactions](https://apis.io/examples/sui/transactions/)

#### Collections (9)

Postman and Open Collection request collections.

- [Sui JSON-RPC Coin Query API API](https://apis.io/collections/sui/open-sui-coin-query-api-api/)
- [Sui JSON-RPC Coin Query API Extended API API](https://apis.io/collections/sui/open-sui-extended-api-api/)
- [Sui JSON-RPC Coin Query API Governance Read API API](https://apis.io/collections/sui/open-sui-governance-read-api-api/)
- [Sui JSON-RPC Coin Query API Move Utils API](https://apis.io/collections/sui/open-sui-move-utils-api/)
- [Sui JSON-RPC Coin Query API PubSub API](https://apis.io/collections/sui/open-sui-pubsub-api/)
- [Sui JSON-RPC Coin Query API Read API API](https://apis.io/collections/sui/open-sui-read-api-api/)
- [Sui JSON-RPC Coin Query API Transaction Builder API API](https://apis.io/collections/sui/open-sui-transaction-builder-api-api/)
- [Sui JSON-RPC Coin Query API Websocket API](https://apis.io/collections/sui/open-sui-websocket-api/)
- [Sui JSON-RPC Coin Query API Write API API](https://apis.io/collections/sui/open-sui-write-api-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Sui — jsonschema rules](https://apis.io/rules/sui/sui-jsonschema-spectral-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Sui Domain Security](https://apis.io/security/sui/sui-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Plans](https://apis.io/plans/sui/plans/)

#### Rate limits (1)

Published request limits.

- [Rate Limits](https://apis.io/rate-limits/sui/rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Finops](https://apis.io/finops/sui/finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://sui.io)
- [Documentation](https://docs.sui.io)
- [Changelog](https://docs.sui.io/references/sui-api/beta-graph-ql/)
- [Blog](https://blog.sui.io)
- [Terms of service](https://mystenlabs.com/legal/terms)
- [Privacy policy](https://mystenlabs.com/legal/privacy-policy)

## API Evangelist rating

**Kin Score 24.8** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 49.4 |
| Contract governance | 9.8 |
| Operational transparency | 10.5 |
| Developer ergonomics | 21.4 |
| Access clarity | 5.3 |

**Agent readiness 22.3** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 5.9** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/sui/](https://apis.io/providers/sui/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Sui: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/sui/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
