# MyToken ERC-20 Smart Contract

This repository contains a Solidity implementation of an ERC-20 token smart contract, built as part of a task for Domain Leads Recruitment 2024-25 in the Blockchain domain.

## Project Overview

This project showcases an understanding of how to create an ERC-20 token using the Solidity programming language. The contract has been deployed on a test network and implements all mandatory functions as per the ERC-20 standard, along with a few custom features.

### Features:
- **ERC-20 Compliant**: Follows the ERC-20 token standard, ensuring compatibility with various decentralized applications (dApps).
- **Token Name**: `MyToken`
- **Symbol**: `MTK`
- **Decimals**: `18`
- **Initial Supply**: The initial supply is set during deployment and assigned to the contract creator.
  
### Functions Implemented:
1. `totalSupply`: Returns the total number of tokens in existence.
2. `balanceOf`: Returns the balance of a specific address.
3. `transfer`: Transfers tokens from the sender's address to another.
4. `approve`: Approves a spender to transfer tokens from the sender’s account.
5. `transferFrom`: Allows a spender to transfer tokens from another address, provided they are approved.
6. `allowance`: Returns the remaining number of tokens that a spender is allowed to transfer from an owner’s account.
7. `burn`: Allows an address to burn its tokens, permanently reducing the total supply.

### Test Network Deployment:
The contract has been deployed on the [Rinkeby/Goerli] test network, and the deployment details are as follows:
- **Contract Address**: [Insert Test Network Contract Address]
- **Transaction Hash**: [Insert Deployment Transaction Hash]

You can interact with the contract using any Ethereum wallet (such as MetaMask) and blockchain explorer like [Etherscan](https://etherscan.io).

## Getting Started

### Prerequisites:
- Solidity Compiler (`solc`)
- Node.js
- Ethereum Wallet (e.g., MetaMask)
- A test network like Rinkeby or Goerli
- [Remix IDE](https://remix.ethereum.org/) or a local Ethereum development framework (like [Truffle](https://www.trufflesuite.com/) or [Hardhat](https://hardhat.org/))

### Steps to Deploy and Test:
1. **Clone this repository**:
   ```
   git clone https://github.com/muskan171105/MyToken.git
   cd MyToken
2. **Compile the contract:**
- Use Remix IDE or run the following command if using a local development environment:
  ```
  solc --optimize --bin --abi MyToken.sol -o build/
  ```
3. **Deploy the contract:**
 You can deploy the contract on any Ethereum-compatible test network like Goerli or Rinkeby using Remix or any Ethereum development tool like Truffle.

4. **Interact with the contract:**
   Use the functions available to transfer tokens, approve an allowance, or burn tokens from an address.

### Example Interactions:

1. **Transfer Tokens**: 
   - You can transfer tokens to another address using the `transfer` function:
   ```solidity
   transfer(address recipient, uint256 amount)
   ```
This will transfer the specified amount of tokens from the caller’s account to the recipient address.

2. **Burn Tokens**:
   ```solidity
   burn(uint256 amount)
    ```
This will permanently reduce the total supply by the amount specified from the caller’s account.


