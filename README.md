# QuadB-Tech-Blockchain-Development-internship
It is a internship assignment
To develop a Secure Token Wallet on the Internet Computer Protocol (ICP) blockchain, you will need to write Rust-based smart contracts to manage token transactions (specifically IRCRC2 tokens) and deploy these contracts on a local ICP test network.

Overview of the Task:
Smart Contracts: Use Rust to write smart contracts for handling sending and receiving IRCRC2 tokens.
Security Features: Implement basic wallet security, such as authentication and transaction validation.
Token Management: Users should be able to send tokens to other addresses, receive tokens, and view their balance.
Testing: Unit tests to validate the smart contract functions.
Deployment: Deploy contracts to a local ICP test network.
Documentation: Provide detailed instructions for setup, deployment, and testing.
Tools and Frameworks Used:
Rust: Primary language for smart contract development.
IC (Internet Computer) SDK: For interacting with the ICP blockchain.
DFINITY SDK: For deploying and testing smart contracts on ICP.
Motoko: ICP's native language, though in this case, you will use Rust.
Key Components:
Smart Contract: A Rust-based contract that implements token sending, receiving, and balance querying.
Security: Basic measures to ensure safe transactions, such as checking user credentials and validating token transfers.
Testing: Use unit tests to verify the contract's behavior.
Deployment: Deploy the smart contract on a local ICP testnet for simulation.
Step-by-Step Guide to Building the Token Wallet on ICP
1. Setting Up Development Environment
Ensure you have the following installed:

Rust: For building and compiling the smart contract.
DFINITY SDK: For deploying to the ICP test network.
IC Framework: For interacting with the blockchain in the ICP context.
2. Write Smart Contract in Rust
You will need to create a new Rust project for the smart contract. Here's a simplified example of how you can set up the Rust code for a token wallet.
3. Deployment to ICP Testnet
To deploy this contract to a local ICP testnet, follow these steps:

Start a Local ICP Test Network using the DFINITY SDK.
Deploy the smart contract:

Build the project with cargo build --release.
Deploy the contract using 
Test the contract using the ICP framework's test environment.

4. Unit Testing
Write unit tests to validate the basic functionality of the smart contract. You can test token transfers, balance retrieval, and error handling (e.g., insufficient balance).

Here’s an example of how you might write a unit test for the get_balance function:
5. Security
While implementing this token wallet, basic security practices should be applied:

Authentication: Ensure only the rightful wallet owner can make transfers or query balances.
Validation: Always validate token transfers to prevent unauthorized actions.
6. Documentation
The project must include clear and comprehensive documentation with setup instructions, including how to:

Install necessary dependencies (Rust, DFINITY SDK).
Set up the local ICP testnet.
Deploy and interact with the wallet smart contract.
Run the unit tests and check the results.
Usage
To transfer tokens, use the transfer_tokens function.
To check balance, use the get_balance function.
