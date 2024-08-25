# ChangeLink: Pooling Small Change for Big Impact Across Chains

![ChangeLink Logo](./assets/logo.png)  <!-- Replace with the link to your project's logo -->

## Overview

ChangeLink is an innovative web3 project that enables users to pool small amounts of cryptocurrency from their wallets across multiple blockchains into a single, purpose-driven wallet. These pooled funds are used to support a common goal, such as funding a specific project. By leveraging Chainlink's Cross-Chain Interoperability Protocol (CCIP), ChangeLink automates the collection, batching, and transfer of small change every 48 hours, making it easy for users to contribute effortlessly.

## Features

- **Cross-Chain Interoperability:** Seamlessly transfer small amounts of cryptocurrency across supported blockchains using Chainlink CCIP.
- **Automated Batching:** Contributions are automatically pooled every 48 hours and sent to a designated wallet.
- **User-Friendly Interface:** A simple, wallet-based web interface allows users to track their contributions and the progress of the funding goal.
- **Contribution History:** View detailed records of your contributions and monitor the overall impact of the community’s pooled resources.
- **Minimal Setup:** Quick and easy wallet-based onboarding with no complicated setup.

## Technologies Used

- **Chainlink CCIP:** Provides secure and reliable cross-chain transactions.
- **Solidity:** Smart contracts for managing the collection, batching, and transfer of funds.
- **Node.js & Express:** Backend server to handle API requests and interact with the blockchain.
- **React.js:** Frontend framework for building a responsive and dynamic user interface.
- **Web3.js/Ethers.js:** Libraries for blockchain interaction from the frontend.
- **MongoDB:** Database for storing user contribution history and tracking the funding goal progress.

## How It Works

1. **User Interaction:**
   - Users connect their wallets through the ChangeLink web interface.
   - Users can select whether to contribute all units of a specific coin or just small change (e.g., amounts under 0.2 USDC).

2. **Batching and Transfer:**
   - Every 48 hours, the smart contract batches all collected contributions and automatically transfers the total amount to a unique wallet controlled by a DAO or other entity.

3. **Tracking Progress:**
   - Users can view their contribution history and monitor the progress toward the funding goal directly through the web interface.

## Installation and Setup

### Prerequisites

- Node.js and npm installed.
- An Ethereum wallet (e.g., MetaMask).
- Access to Chainlink CCIP.

### Steps to Run Locally

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/ChangeLink.git
   cd ChangeLink
