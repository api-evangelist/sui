# Sui

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
