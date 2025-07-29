# 🦀 bitcoin_rust

**A simplified, developer-friendly Bitcoin implementation in Rust**

This project provides a complete yet approachable implementation of the Bitcoin protocol written entirely in idiomatic, well-documented Rust. It includes core features like:

- 🧱 Block and transaction structures  
- 💸 Wallet generation and UTXO tracking  
- ⛏️ Proof-of-work mining  
- 🔗 In-memory blockchain  
- 📨 Minimal peer-to-peer networking  
- 📚 Fully documented, educational codebase  

## Getting Started

### Requirements

- Rust (1.70+ recommended)
- Cargo

### Build & Run

```bash
git clone https://github.com/yourname/bitcoin_rust.git
cd bitcoin_rust
cargo run --release
```

This will launch a standalone node that:
- Creates a new wallet
- Starts mining blocks to that wallet’s address
- Listens for peer connections at `127.0.0.1:8333`

## Project Structure

| Module       | Description |
|--------------|-------------|
| `block.rs`   | Block header, hashing, and mining |
| `transaction.rs` | Transaction structures and signing |
| `blockchain.rs`  | In-memory chain and UTXO management |
| `wallet.rs`  | Key generation and P2PKH address handling |
| `crypto.rs`  | Hashing, Base58Check, difficulty conversion |
| `merkle.rs`  | Merkle root calculation |
| `network.rs` | Async P2P networking over TCP |
| `miner.rs`   | Simple async miner task |
| `utils.rs`   | Byte utils and hex encoding |

## License

MIT © 2025 Anonymous

> Inspired by Satoshi. Built for learning. Powered by Rust. 🦀
