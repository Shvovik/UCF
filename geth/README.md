# UCF EVM Testnet

This directory contains the experimental EVM-compatible blockchain infrastructure for UCF.

## Objective

The purpose of this track is to evaluate an independent EVM-compatible UCF network using the Ethereum execution stack.

## Development Goals

* custom genesis
* chain configuration
* EVM execution
* RPC
* peer-to-peer networking
* multi-node operation
* smart-contract deployment
* blockchain explorer integration

## Current Stage

This is a development/testnet environment.

It must not be connected to production funds.

## Important

Consensus architecture must be selected deliberately.

Older Geth private-network examples commonly used Clique Proof-of-Authority. However, Clique has been deprecated in modern Geth releases.

Therefore UCF will not hard-code a deprecated consensus mechanism into the architecture. The final consensus configuration will be selected during testnet research.

## Planned Structure

```text
geth/
├── genesis/
│   └── README.md
├── config/
│   └── README.md
├── testnet/
│   └── README.md
└── README.md
```

## Planned Testnet

The initial testnet should support:

* multiple nodes
* deterministic genesis
* custom Chain ID
* RPC endpoint
* peer discovery
* test accounts
* test native asset
* smart-contract deployment

## Security

Private keys and passwords must never be committed to GitHub.

Use isolated testnet wallets and infrastructure.
