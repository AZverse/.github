# AZverse

**Compose All Finance** — an open financial network you can verify.

[Website](https://www.azverse.xyz) · [Docs](https://azverse.gitbook.io/azx-docs) · [X / Twitter](https://x.com/AZverse_Global)

---

AZverse is an **open financial network** — shared liquidity, matching, and settlement — for composing financial products. Teams become **Composers** and launch their own branded **Compositions** on the shared foundation; **AZX**, the flagship Composition, is a full spot-and-perpetuals trading venue. Everything settles on **AZ**, a purpose-built Layer 1 with cryptographically verifiable finality. The mission: **Compose All Finance**.

This organization hosts the open-source components of that network. **Everything here is meant to be read, run, and verified — not taken on trust.**

## What you can verify here

- **Consensus you can check offline.** [`az-bft`](https://github.com/AZverse/az-bft) is our BFT consensus engine — a weighted, two-chain HotStuff-family protocol with deterministic safety. It ships an **offline finality verifier**: given a run transcript, you can independently confirm the quorum signatures and linked commit certificates yourself, without trusting an AZverse endpoint.
- **Contracts on-chain.** [`asset-vault-contracts`](https://github.com/AZverse/asset-vault-contracts) holds the Solidity contracts behind AZ AssetVault — deployed, and open to read.
- **Open validation & relaying.** [`relayer-validator`](https://github.com/AZverse/relayer-validator) is the relayer / validator infrastructure of the network.
- **Open API.** [`api-docs`](https://github.com/AZverse/api-docs) plus language demos let anyone build against AZverse.

## Core repositories

| Repository | What it is |
|---|---|
| [**az-bft**](https://github.com/AZverse/az-bft) | BFT consensus engine for the AZ L1 — protocol spec, safety rules, cryptography, deterministic devnet, and an offline finality verifier. `Apache-2.0`. |
| [**asset-vault-contracts**](https://github.com/AZverse/asset-vault-contracts) | On-chain Solidity contracts for AZ AssetVault. |
| [**relayer-validator**](https://github.com/AZverse/relayer-validator) | Relayer and validator node infrastructure. |
| [**azx-cli**](https://github.com/AZverse/azx-cli) | Command-line tools for the AZverse network. `MIT`. |
| [**api-docs**](https://github.com/AZverse/api-docs) | Documentation for the AZverse open API. `MIT`. |

## Progressive decentralization

We are direct about where we are today.

AZ currently runs a **permissioned validator set** — stated plainly in [`az-bft`'s `STATUS.md`](https://github.com/AZverse/az-bft/blob/main/STATUS.md). What matters is that finality is **already independently verifiable**: the consensus core is open source under Apache-2.0, and commit certificates can be checked offline.

We are decentralizing in the open — progressively opening the validator set, oracle configuration, and asset onboarding. The direction and boundaries live in each repository's `ROADMAP.md` and `STATUS.md`, not in a marketing page.

## Stay in touch

- **Website** — https://www.azverse.xyz
- **Docs** — https://azverse.gitbook.io/azx-docs
- **X / Twitter** — [@AZverse_Global](https://x.com/AZverse_Global)

<sub>Organization verified by GitHub as controlling <code>www.azverse.xyz</code>.</sub>
