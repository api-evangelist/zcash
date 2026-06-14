# Zcash

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
