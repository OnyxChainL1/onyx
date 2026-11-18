# Changelog

All notable changes to ONYX are listed here. Versions follow [Semantic Versioning](https://semver.org).

## [Unreleased]

## [0.1.0] - 2026-11-18

First public release.

### Added

- **Chain.** ML-DSA-65 signed blocks and attestations on a 4-second slot, SHA3-256 hashing, `onx1` addresses derived from the public key, finality at the proposer plus two attesters.
- **Transactions.** ML-DSA-44 signatures made in the browser and verified by the node before the mempool.
- **Open validator set.** Stake, attest and earn from a single-file node or a validator that runs in a browser tab; offline proposers are skipped.
- **Wallet, explorer and faucet.**
- **Launchpad.** Native tokens on a bonding curve, with GitHub-verified tech launches.
- **QuantumDEX.** A constant-product pool with ML-DSA signed swaps and liquidity.
- **Quantum Vaults.** k-of-n multisig with ML-DSA-44 signers.
- **Lifeboat.** Bind a Solana wallet to an `onx1` address with one message signed by both keys.
- **Public JSON-RPC and SDK.** Fifteen `onyx_*` methods, open CORS, and a one-file SDK.
- **Forge, Scanner and Points.**

[Unreleased]: https://github.com/OnyxChainL1/onyx/compare/v0.1.0...HEAD
[0.1.0]: https://github.com/OnyxChainL1/onyx/releases/tag/v0.1.0
