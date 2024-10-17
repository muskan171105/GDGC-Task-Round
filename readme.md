# MyToken ERC-20 Smart Contract

This repository contains a Solidity implementation of an ERC-20 token smart contract, built as part of a task for Domain Leads Recruitment 2024-25 in the Blockchain domain.

## Project Overview

This project showcases an understanding of how to create an ERC-20 token using the Solidity programming language. The contract has been deployed on a test network and implements all mandatory functions as per the ERC-20 standard, along with a few custom features.

### Features:
- **ERC-20 Compliant**: Follows the ERC-20 token standard, ensuring compatibility with various decentralized applications (dApps).
- **Token Name**: `MyToken`
- **Symbol**: `MTK`
- **Decimals**: `18`
- **Initial Supply**: 1000000
  
### Functions Implemented:
1. `totalSupply`: Returns the total number of tokens in existence.
2. `balanceOf`: Returns the balance of a specific address.
3. `transfer`: Transfers tokens from the sender's address to another.
4. `approve`: Approves a spender to transfer tokens from the sender’s account.
5. `transferFrom`: Allows a spender to transfer tokens from another address, provided they are approved.
6. `allowance`: Returns the remaining number of tokens that a spender is allowed to transfer from an owner’s account.
7. `burn`: Allows an address to burn its tokens, permanently reducing the total supply.

### Test Network Deployment:
The contract has been deployed on the **Sepolia ETH** test network, and the deployment details are as follows:
- **Contract Address**: [0xd9145CCE52D386f254917e481eB44e9943F39138]
- **Transaction Hash**: [0x8042e8570fd00ddfcafa95b3a7060459732ee90ffedb709d79d2fba9d8c0c944]

You can interact with the contract using any Ethereum wallet (such as MetaMask) and blockchain explorer like [Etherscan](https://etherscan.io).

## Getting Started

### Accessing Remix IDE
1. Open your web browser.
2. Go to the Remix IDE website: [https://remix.ethereum.org](https://remix.ethereum.org).

### Create Your Contract
1. In the contracts folder, create a new file called MyToken.sol.
2. Paste your ERC-20 contract code into the file.

### Compile the Contract
1. On the left sidebar, go to the Solidity Compiler tab.
2. Click the Compile MyToken.sol button.

### Test Locally
1. Go to the Deploy & Run Transactions tab (also on the left sidebar).
2. In the Environment dropdown, choose `Remix VM (Cancun)`. This simulates a local blockchain in your browser.
3. Click Deploy. This will deploy the contract locally in the browser, and you can interact with it without using real or test ETH.
4. Once deployed, you can interact with the contract functions like `transfer`, `balanceOf`, `approve`, etc., from the UI.

### Contract Deployed Successfully
![My Token Image](https://github.com/muskan171105/GDGC-Task-Round/blob/main/Screenshot2024-10-17-102254.png)
