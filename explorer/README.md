# UCF Scan

UCF Scan is the planned blockchain explorer for UCF Network.

## Goal

Provide transparent access to blockchain activity.

## Planned Features

* blocks
* transactions
* addresses
* tokens
* smart contracts
* transfers
* gas information
* network statistics
* validator/node information

## Development Stages

### Prototype

Read-only blockchain explorer connected to the UCF testnet RPC.

### Public Testnet

Add:

* address pages
* transaction pages
* block pages
* token pages
* contract verification
* network statistics

### Mainnet

Production explorer for UCF Mainnet.

## Architecture

```text
UCF Node
   │
   ↓
RPC
   │
   ↓
Indexer
   │
   ↓
Database
   │
   ↓
UCF Scan API
   │
   ↓
UCF Scan Web Interface
```

