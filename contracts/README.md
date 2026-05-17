# Gignex Soroban Smart Contracts

This repository contains the Rust-based smart contracts for the Gignex platform. These contracts handle the decentralized escrow logic, milestone funding, and conflict resolution on the Stellar Soroban network.

## 📜 Contract Structure
- **Gig Escrow (`gig_escrow`)**: The primary contract. It holds funds in escrow and releases them based on cryptographic signatures mapping to project milestones.

## 🛠 Prerequisites
- [Rust](https://www.rust-lang.org/tools/install)
- `wasm32-unknown-unknown` target installed (`rustup target add wasm32-unknown-unknown`)
- [Stellar CLI](https://developers.stellar.org/docs/build/smart-contracts/getting-started/setup)

## 🏗 Building the Contracts
Navigate to the `gig_escrow` directory and run:
```bash
cargo build --target wasm32-unknown-unknown --release
```
The compiled `.wasm` file will be located in `target/wasm32-unknown-unknown/release/`.

## 🧪 Testing
Run the Rust test suite:
```bash
cargo test
```

## 🚀 Deployment
Use the Stellar CLI to deploy the contract to the Testnet:
```bash
stellar contract deploy \
  --wasm target/wasm32-unknown-unknown/release/gig_escrow.wasm \
  --source-account <your-funding-account> \
  --network testnet
```

## 🤝 Contributing
Review the [CONTRIBUTING.md](CONTRIBUTING.md) file before proposing changes to the smart contract logic.

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
