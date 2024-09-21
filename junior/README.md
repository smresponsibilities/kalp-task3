# 🚀 Develop a Token Airdrop System with Frontend on Kalp Blockchain

## Challenge Overview

This challenge involves creating a comprehensive token airdrop system on the Kalp blockchain, consisting of two main components:

1. A smart contract written in Go for managing fungible token distribution.
2. A React-based frontend application for user interaction with the smart contract.

## Learning Objectives

By completing this challenge, you will:

- Gain practical experience with Go programming and smart contract development.
- Implement fungible tokens similar to ERC-20 standards.
- Learn to deploy and interact with smart contracts on the Kalp blockchain.
- Develop skills in building decentralized applications (dApps).
- Enhance your React and TypeScript proficiency.
- Master API integration and state management in frontend development.

## Understanding Token Airdrops

Token airdrops are a method of distributing free tokens to users' wallets, often used to promote blockchain projects and build community engagement. This challenge simulates this process, allowing you to create both the distribution mechanism and the user interface for claiming tokens.

## Project Setup

### Prerequisites

1. Go (version >=1.19 but <1.20)
2. Node.js (version >=14.x) and npm (version >=6.x)

### Installation Steps

1. Clone the repository:
   ```
   git clone https://github.com/Build-Hackathon/junior.git
   ```

2. Set up the smart contract:
   ```
   cd junior/airdrop-vending-machine/smart-contract
   go mod tidy
   ```

3. Set up the frontend:
   ```
   cd ../frontend
   npm install
   ```

## Project Structure

```
airdrop-vending-machine
├── smart-contract
│   ├── vendor
│   ├── go.mod
│   ├── go.sum
│   ├── main.go
│   └── krc.go
├── frontend
    ├── src
    │   ├── app
    │   ├── hooks
    │   │   └── useKalpApi.ts
    │   └── pages
    ├── public
    ├── package.json
    └── tsconfig.json
```

## Key Components

1. Smart Contract (`krc.go`): Manages token initialization, minting, transfers, and balance checks.
2. Frontend Hook (`useKalpApi.ts`): Facilitates communication between the frontend and the smart contract.

## Deployment and Configuration

1. Deploy the smart contract using Kalp Studio.
2. Configure the frontend with the generated API endpoints and API key.
3. Update environment variables in the frontend project.

## Running the Application

1. Start the frontend development server:
   ```
   npm run dev
   ```
2. Access the application at `http://localhost:3000`.

## Submission Guidelines

- Implement all required functionalities in both smart contract and frontend.
- Ensure code quality, proper documentation, and clear instructions.
- Deploy the frontend and provide a live link.
- Additional features are encouraged and will be considered favorably.

## Conclusion

This challenge offers a comprehensive learning experience in blockchain development, combining smart contract creation with frontend application development. It provides practical insights into the world of decentralized applications and token systems.
