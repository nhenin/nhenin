# Nicolas Henin

**Hands-on CTO / Founding Technical Lead | Functional-programming blockchain systems | Haskell / Plutus / ZK | Research-to-production | Cardano @ IOG**

I am a hands-on technical leader: I frame hard problems, decide the architecture, lead small teams, and still write the Haskell that ships it.

For 4+ years at Input Output (IOG/IOHK), I have worked at the core of Cardano, where peer-reviewed cryptography meets production code and protocol governance. My edge is taking work from research paper to working system without losing rigor on either side.

I work mostly with Haskell, Plutus, Marlowe, TypeScript, Scala, Rust, Nix, protocol design, DSLs, smart contracts, consensus systems, event sourcing, and formal-methods-oriented engineering.

## Selected Work

### Protocol research and Cardano architecture

- [Dynamic Pricing](https://github.com/nhenin/dynamic-pricing) - Cardano fee-market and lane-pricing prototype, including ledger-rule experiments and per-lane pricing/admission logic.
- [Cavefish](https://github.com/input-output-hk/cavefish) - light-client and intent-oriented R&D prototype for private transaction submission on UTxO blockchains, combining Haskell transaction-level strategy with ZK/Circom work.
- [Ouroboros Phalanx](https://github.com/input-output-hk/ouroboros-phalanx-protocol) - protocol-level anti-grinding work around Ouroboros Praos, VDFs, and the economics of adversarial randomness manipulation.
- [CIP-0161](https://cips.cardano.org/cip/CIP-0161) / [CPS-0021](https://cips.cardano.org/cps/CPS-0021) - Cardano governance-facing protocol specifications around Ouroboros randomness manipulation and Phalanx.
- [SPO Incentives / The Holistic Reading](https://github.com/input-output-hk/spo-incentives) - diagnostic and redesign analysis of Cardano staking rewards, including mainnet reward-flow evidence, CIP evaluation, and SPO topology work.

### Financial contracts, smart contracts, and SDKs

- [Marlowe Cardano](https://github.com/marlowe-lang/marlowe-cardano) - Haskell implementation of Marlowe on Cardano, including runtime and smart-contract infrastructure.
- [Marlowe TypeScript SDK](https://github.com/marlowe-lang/marlowe-ts-sdk) - TypeScript SDK for building Marlowe/Cardano applications and contract workflows.
- [Marlowe Payouts prototype](https://github.com/marlowe-lang/marlowe-payouts) - generic payouts-withdrawal DApp prototype built on Marlowe technology and the TypeScript SDK.
- [Marlowe Token Plans prototype](https://github.com/marlowe-lang/marlowe-token-plans) - token vesting/plans DApp prototype built on Marlowe technology, including the vesting-contract flow exercised from the SDK examples.
- [Tokenomia](https://github.com/smart-chain-fr/tokenomia) - Haskell/Plutus tooling for Cardano native tokens, vesting, mint/burn flows, wallet operations, and Cardashift ICO mechanics; built for a EUR10M token sale, with about 6M ADA processed through this codebase.
- [World Mobile ENNFT ownership contract](https://resources.cryptocompare.com/asset-management/886/1701083365531.pdf) - first EarthNode Plutus contract for NFT ownership/claiming; the source repository (`worldmobilegroup/ennft-mgr`, commit `c26a089...`) is not public, but is identified in public Verichains and [Runtime Verification](https://github.com/runtimeverification/publications/blob/main/reports/smart-contracts/WorldMobileGroup.pdf) audit reports.
- [World Mobile EarthNode registration contract](https://github.com/nhenin/earthnode-registration-plutus-smart-contract/tree/nixified-project) - follow-up Plutus workstream for operator registration, ENOP NFT lifecycle properties, and registration/update/deregistration logic; see the upstream [World Mobile PR #8](https://github.com/worldmobilegroup/earthnode-registration-plutus-smart-contract/pull/8).

### Earlier systems and leadership

- [Dolla / GSD consensus](https://github.com/dolla-consortium/consensus) - CTO work on a consortium blockchain, including a Democratic Byzantine Fault Tolerant consensus built from scratch without PoW or PoS.
- [Consensus proposing](https://github.com/nhenin/consensus-proposing) - proposal staging and transaction flow work for the Dolla consensus system.
- OMsignal - first engineering hire at a wearable-tech startup, before moving deeper into functional systems and blockchain architecture.

## How To Read This Profile

Many repositories on this account are forks used for upstream work, experiments, or work branches. The best entry points are the selected projects above and the pinned repositories. They represent the work I would want a recruiter, founder, or engineering leader to inspect first.

I am most interested in hands-on CTO, founding engineer, principal engineer, and technical-lead roles in protocol engineering, programmable finance, applied cryptography, functional programming, or infrastructure-heavy startups.

## Links

- [LinkedIn](https://www.linkedin.com/in/nhenin/)
- [X / Twitter](https://twitter.com/nhenin)
- [GitHub](https://github.com/nhenin)
