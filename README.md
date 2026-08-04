# Zcash

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

Zcash is a privacy-preserving cryptocurrency that uses zero-knowledge proofs (zk-SNARKs) to enable shielded (private) transactions alongside transparent transactions. It provides JSON-RPC APIs via zcashd and zebrad for shielded transaction management, wallet operations, and blockchain data access.

## APIs

| API | Type | Description |
|-----|------|-------------|
| Zcash JSON-RPC API (zcashd) | JSON-RPC | Full node Bitcoin-compatible + Zcash extensions |
| Zcash Payment API (z_ methods) | JSON-RPC | Shielded address and private transaction management |
| Lightwalletd gRPC API | gRPC | Compact block streaming for lightweight clients |
| Zebra JSON-RPC API | JSON-RPC | Rust-based alternative full node (zcashd successor) |

## Key Features

- Privacy-preserving shielded transactions using zk-SNARKs (Sapling and Orchard pools)
- Encrypted memo fields on shielded transactions
- Bitcoin-compatible transparent transactions (t-addresses)
- Shielded addresses (z-addresses) for full privacy
- Asynchronous operation model for shielded transaction creation
- Compact block streaming via lightwalletd for mobile/web wallets
- Viewing keys for selective disclosure of transaction details

## Developer Resources

- [Zcash Documentation](https://zcash.readthedocs.io/)
- [Zcash RPC Reference](https://zcash.github.io/rpc/)
- [Payment API](https://github.com/zcash/zcash/blob/master/doc/payment-api.md)
- [Integration Guide](https://zcash.readthedocs.io/en/latest/rtd_pages/zig.html)
- [Lightwalletd](https://github.com/zcash/lightwalletd)
- [Zebra (Zcash Foundation node)](https://zebra.zfnd.org/)
- [Android SDK](https://github.com/zcash/zcash-android-wallet-sdk)
- [iOS SDK (ZcashLightClientKit)](https://github.com/zcash/ZcashLightClientKit)
- [Testnet Guide](https://zcash.readthedocs.io/en/latest/rtd_pages/testnet.html)

## Contact

- Integration support: ecosystem@z.cash
- Community: https://z.cash/community-hub/

## Maintainers

- [Electric Coin Company](https://electriccoin.co/)
- [Zcash Foundation](https://zfnd.org/)
