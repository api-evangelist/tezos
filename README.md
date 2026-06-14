# Tezos (tezos)

Tezos is a self-amending blockchain platform that uses on-chain governance
to upgrade its protocol without hard forks. The primary developer API surface
is provided by TzKT, an open-source Tezos blockchain indexer built and
maintained by the Baking Bad team. TzKT exposes a comprehensive REST API
covering 100+ endpoints for querying blocks, accounts, operations, delegations,
smart contracts, big maps, tokens (FA1.2/FA2/NFTs), staking data, baking
rights, governance periods, and protocol metadata on the Tezos mainnet. The
API supports deep filtering, deep selection, deep sorting, CSV exports, and
historical data queries at specific block heights. A WebSocket API (SignalR)
provides real-time subscription streams for new blocks and operations.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tezos/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tezos/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** Public

## Tags

- Tezos
- Blockchain
- TzKT
- Baking Bad
- Cryptocurrency
- Smart Contracts
- NFT
- Tokens
- Delegations
- Staking
- Governance
- FA1.2
- FA2
- WebSocket

## APIs

| API | Description |
|-----|-------------|
| TzKT Accounts API | Profile, balance, and operation history for any Tezos address |
| TzKT Blocks API | Block-level data including baker, rewards, and chain tip |
| TzKT Operations API | All Tezos operation types with deep filtering and CSV export |
| TzKT Contracts API | Smart contract metadata, storage, entrypoints, views, and events |
| TzKT Big Maps API | Indexed big map key-value entries with historical tracking |
| TzKT Tokens API | FA1.2, FA2, and NFT balances, metadata, and transfers |
| TzKT Delegations and Staking API | Delegation assignments, staking balances, baking rights, rewards |
| TzKT Governance API | Voting periods, proposals, ballots, and protocol amendment history |
| TzKT Protocols API | Per-protocol constants, cycles, and amendment metadata |
| TzKT WebSocket API | Real-time SignalR push streams for blocks, operations, and balances |

## Authentication

No API key required for the free public tier. Rate limits are applied per IP
address: 50 requests/second and 3,000,000 requests/day. HTTP 429 is returned
when limits are exceeded. TzKT Pro is available for higher-volume use cases.

## Links

- **API Documentation:** https://api.tzkt.io/
- **GitHub Repository:** https://github.com/baking-bad/tzkt
- **Mainnet Explorer:** https://tzkt.io
- **Baking Bad:** https://bakingbad.dev/
