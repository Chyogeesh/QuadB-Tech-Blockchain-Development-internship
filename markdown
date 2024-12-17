# ICP Token Wallet

## Setup and Installation

1. Install Rust: [Rust Installation Guide](https://www.rust-lang.org/tools/install)
2. Install DFINITY SDK: `sh -ci "$(curl -fsSL https://sdk.dfinity.org/install.sh)"`
3. Install dependencies: `cargo build --release`
4. Start the ICP local testnet: `dfx start --clean`
5. Deploy the smart contract: `dfx deploy`

## Testing

Run the unit tests:
```bash
cargo test
