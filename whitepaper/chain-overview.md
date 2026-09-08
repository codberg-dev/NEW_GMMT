# 2. Giant Mammoth Chain

## Overview
- **Type:** EVM-compatible public chain
- **Chain ID:** 8989 (0x231d)
- **Native coin:** GMMT
- **Smart contracts:** supported (EVM)
- **Explorer:** scan.gmmtchain.io
- **Wallet:** GM Wallet (wallet.mammothlabs.io)

GMMT runs on its own mainnet, EVM-compatible so existing Solidity contracts and tooling migrate with minimal changes.

## Modernization plan
RWA does not require replacing the base chain, but long-term competitiveness, security, and liquidity call for modernization across four tracks:

| Track | Scope | Priority |
| --- | --- | --- |
| A · Core chain | Node client / EVM version upgrade | Parallel, resourced |
| B · Dev environment | Standard tooling (Hardhat/Foundry), docs, RPC, faucet, testnet | **Immediate** |
| C · Oracle | Price feeds for RWA/DeFi | **Prerequisite** |
| D · Bridge & DEX | Own DEX + bridge to major-chain DEX liquidity | **High impact** |

> **[Developer TBD]** current node client/version, EVM version, deployment tooling status, oracle & bridge feasibility, validator set & upgrade process.
