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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Sui is a next-generation Move-based blockchain developed by Mysten Labs, designed for high throughput, low latency, and an asset-oriented programming model. The network provides multiple API interfaces for querying objects, transactions, checkpoints, events, and balances.

## APIs

### gRPC API (Recommended)
The current recommended interface, replacing the deprecated JSON-RPC. Type-safe, low-latency, and supports streaming subscriptions.
- Mainnet: `https://fullnode.mainnet.sui.io:443`
- Testnet: `https://fullnode.testnet.sui.io:443`
- Reference: https://docs.sui.io/references/fullnode-protocol

### GraphQL RPC
Flexible read interface backed by the General-Purpose Indexer. Best for frontends and dashboards.
- Mainnet: `https://sui-mainnet.mystenlabs.com/graphql`
- Testnet: `https://sui-testnet.mystenlabs.com/graphql`
- Reference: https://docs.sui.io/references/sui-graphql

### JSON-RPC (Deprecated)
The legacy JSON-RPC interface. Will be decommissioned July 31, 2026. Migrate to gRPC or GraphQL.
- Reference: https://docs.sui.io/sui-api-ref

## Resources

- Website: https://sui.io
- Documentation: https://docs.sui.io
- GitHub: https://github.com/MystenLabs/sui
- SDK: https://sdk.mystenlabs.com/sui/clients
- Discord: https://discord.gg/sui
- Forum: https://forums.sui.io
- Blog: https://blog.sui.io
