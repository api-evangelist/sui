# Sui GraphQL API

The Sui GraphQL RPC is a generally available read/write interface for the Sui blockchain, backed by the Sui General-Purpose Indexer, Consistent Store, full nodes, and Archival Service. It exposes the full range of on-chain data through a typed schema covering addresses, objects, transactions, checkpoints, epochs, events, coin balances, Move packages, dynamic fields, and validator sets. The API supports both point lookups and paginated connection-style queries, and provides transaction submission and dry-run simulation via the `Mutation` type.

The GraphQL endpoint requires no authentication for read queries. Write operations (transaction execution and dry-run simulation) accept a Base64-encoded transaction payload and optional signatures. The service is publicly accessible and supports introspection, making it suitable for frontends, dashboards, analytics tools, and any use case that benefits from flexible, nested queries across multiple data types in a single request.

The mainnet endpoint is hosted by Mysten Labs. A testnet variant is available at the same path on the testnet host. The schema is maintained in the open-source MystenLabs/sui repository and versioned alongside the Sui protocol.

**Endpoint:** https://sui-mainnet.mystenlabs.com/graphql

**Documentation:** https://docs.sui.io/references/sui-graphql

**References:**
- Documentation: https://docs.sui.io/references/sui-graphql
- GettingStarted: https://docs.sui.io/guides/developer/getting-started
