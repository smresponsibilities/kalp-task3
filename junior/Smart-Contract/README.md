# 🚀 Developing a Token Airdrop Smart Contract on Kalp Blockchain

## Challenge Overview

This challenge focuses on creating a smart contract for a token airdrop system using the Kalp blockchain. You'll develop a Go-based smart contract that manages fungible token distribution, allowing users to claim tokens through an airdrop mechanism.

## Learning Objectives

By completing this challenge, you will:

- Gain hands-on experience with Go programming for blockchain.
- Implement fungible tokens similar to ERC-20 standards.
- Learn to deploy and interact with smart contracts on Kalp blockchain.
- Enhance your blockchain development skills.
- Master concepts like token minting, balance management, and transfers.

## Understanding Token Airdrops

Token airdrops are a method of distributing free tokens to users' wallets, often used to promote blockchain projects and engage communities. This challenge simulates this process through a smart contract.

## Project Setup

### Prerequisites

- Go (version >=1.19 but <1.20)

### Installation Steps

1. Clone the repository:
   ```
   git clone https://github.com/Build-Hackathon/junior.git
   ```

2. Navigate to the smart contract directory:
   ```
   cd junior/airdrop-vending-machine/smart-contract
   ```

3. Install dependencies:
   ```
   go mod tidy
   ```

## Smart Contract Structure

The smart contract (`krc.go`) contains several key functions:

1. `Initialize`: Sets up the token contract with name, symbol, and decimals.
2. `Claim`: Allows minting of new tokens to a specified address.
3. `BalanceOf`: Checks the token balance of an account.
4. `TotalSupply`: Returns the total number of tokens in circulation.
5. `TransferFrom`: Enables token transfers between accounts.

## Deploying the Smart Contract

1. Sign up and log in to Kalp Studio Platform.
2. Use Kalp Instant Deployer to upload and deploy your smart contract.
3. Generate API endpoints for each function of your smart contract.
4. Create an API key for authentication.

## Interacting with the Smart Contract

After deployment, you can interact with the smart contract using the generated API endpoints. Use tools like Postman to test the following operations:

1. Initialize the contract
2. Claim tokens
3. Check balance
4. Transfer tokens

## Conclusion

This challenge provides a comprehensive introduction to smart contract development on the Kalp blockchain. It covers essential aspects of token systems and prepares you for more advanced blockchain development tasks.
