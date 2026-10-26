# Tezos (tezos)

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
