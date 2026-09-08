# 2. Giant Mammoth Chain

## Overview
- **Type:** EVM-compatible public chain
- **Chain ID:** 8989 (0x231d)
- **Native coin:** GMMT
- **Base:** BAS (BNB Application Sidechain), go-ethereum (geth) fork
- **Consensus:** PoSA (Proof of Staked Authority)
- **Block time:** ~3 seconds
- **Validators:** managed validator set _(current count: confirm via explorer / node ops)_
- **Smart contracts:** supported (EVM)
- **Explorer:** scan.gmmtchain.io
- **Wallet:** GM Wallet (wallet.mammothlabs.io)

GMMT runs on its own mainnet — a geth-based BAS chain using PoSA with ~3s block time. Being EVM-compatible, existing Solidity contracts and tooling migrate with minimal changes.

## Modernization plan
RWA does not require replacing the base chain, but long-term competitiveness, security, and liquidity call for modernization across four tracks:

| Track | Scope | Priority |
| --- | --- | --- |
| A · Core chain | Node client / EVM version upgrade | Parallel, resourced |
| B · Dev environment | Standard tooling (Hardhat/Foundry), docs, RPC, faucet, testnet | **Immediate** |
| C · Oracle | Price feeds for RWA/DeFi (planned) | **Prerequisite** |
| D · Bridge & DEX | Bridge (operating) + own DEX; extend to major-chain DEX liquidity | **High impact** |

**Status notes:** a bridge is currently operating; an RWA/DeFi price oracle is planned. Exact node client/EVM versions, the current validator count, and the upgrade process are confirmed with node operations.
