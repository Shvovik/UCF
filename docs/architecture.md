# UCF Blockchain Architecture

## Overview

UCF is developing blockchain infrastructure through multiple experimental tracks before selecting the final architecture for UCF Mainnet.

The current development model consists of:

```text
                UCF Ecosystem
                      │
          ┌───────────┴───────────┐
          │                       │
       Canopy                  EVM/Geth
      Testnet                  Testnet
          │                       │
          └───────────┬───────────┘
                      │
               Architecture
                Evaluation
                      │
                UCF Testnet
                      │
                UCF Mainnet
```

## Infrastructure Layers

### Layer 1 — Network

Responsible for:

* peer-to-peer communication
* block production
* consensus
* validators/nodes
* network discovery

### Layer 2 — Execution

Responsible for:

* transactions
* smart contracts
* EVM execution
* gas accounting
* state management

### Layer 3 — RPC

Provides interfaces for:

* wallets
* applications
* developers
* explorers
* monitoring systems

### Layer 4 — Applications

Includes:

* UCF DeFi
* staking
* NFT marketplace
* governance
* ecosystem applications

### Layer 5 — Infrastructure Applications

Includes:

* UCF Scan
* network explorer
* monitoring
* analytics
* developer tools

## Architecture Selection

The Canopy and EVM/Geth tracks are experimental development paths.

The final UCF Mainnet architecture will be selected after evaluating:

* decentralization
* performance
* security
* developer experience
* EVM compatibility
* node requirements
* validator economics
* interoperability
* operational complexity

