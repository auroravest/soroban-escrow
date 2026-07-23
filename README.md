# Soroban Escrow

A trustless escrow smart contract for [Soroban](https://soroban.stellar.org/) on Stellar.

## Features

- **Milestone-based Releases**: Funds released upon milestone completion
- **Dispute Resolution**: Built-in arbitration mechanism
- **Multi-party Agreements**: Support for buyer, seller, and arbiter roles
- **Time-locked Refunds**: Automatic refund if milestones not met
- **Token Agnostic**: Works with any Soroban-compatible token

## Quick Start

```bash
soroban contract build
cargo test
```

## License

MIT
