# Phase 4: dApp Development & Chain Interaction

This phase connects smart contracts to real, user-facing applications — covering how frontends talk to the blockchain, pull in off-chain data, and store assets in a decentralized way.

## Topics List

### 4.1 Connecting Frontend to Blockchain
- Introduction to Ethers.js / Web3.js
- Connecting to a User's Wallet (MetaMask, Phantom, WalletConnect)
- Providers, Signers, and Contract Instances
- Multi-Chain Wallet Connections (EVM vs. Solana vs. others)

### 4.2 Reading and Writing to the Blockchain
- Calling view and pure Functions to Read Data
- Sending Transactions to Execute State-Changing Functions
- Listening for Smart Contract Events
- Handling Transaction Confirmations and Errors

### 4.3 Building a dApp Frontend with React.js
- Setting Up a React Project for Web3
- Using React Hooks (useState, useEffect) to Manage Blockchain Data
- Wallet Connection Libraries (RainbowKit, ConnectKit, Wallet Adapter for Solana)
- Displaying On-Chain Data in the UI

### 4.4 Oracles & Off-Chain Data
- The Oracle Problem: Getting Off-Chain Data On-Chain
- Introduction to Chainlink for Real-World Data Feeds
- Chainlink Price Feeds, VRF (randomness), and Automation
- Trade-offs of Centralized vs. Decentralized Oracles

### 4.5 Decentralized Storage
- Why Decentralized Storage?
- Introduction to IPFS (InterPlanetary File System)
- Storing NFT Metadata and Other Assets on IPFS
- Arweave as a Permanent Storage Alternative

## Resources

**1. Connecting Frontend to Blockchain**
- Resource
  - Build a dApp with Ethers.js (from the official docs)
  - Solana Web3.js Documentation and Quickstart Guide
- Reference Material
  - Official Ethers.js Documentation

**2. Reading and Writing to the Blockchain**
- Resource
  - Dapp University — Reading and Writing to Smart Contracts (video tutorial)
- Reference Material
  - Ethers.js Contract Interaction Guide

**3. Building a dApp Frontend with React.js**
- Resource
  - RainbowKit Documentation (easy wallet connection for React)
  - Connect to MetaMask with React & Ethers.js by Dapp University (video tutorial)
  - Solana Wallet Adapter Documentation
- Reference Material
  - React JS Official Documentation

**4. Oracles & Off-Chain Data**
- Resource
  - Chainlink Official Documentation and Tutorials
  - Patrick Collins — Chainlink Fundamentals (video course)
- Reference Material
  - Chainlink Developer Documentation

**5. Decentralized Storage**
- Resource
  - IPFS Docs — Getting Started Guide
  - Pinata — IPFS Pinning Service Documentation
  - Arweave — Getting Started Guide
- Reference Material
  - Official IPFS Documentation

## Practice Exercises

**Beginner**
- Build a simple webpage that connects to MetaMask and displays the connected wallet address and balance.
- Upload an image and JSON metadata file to IPFS using Pinata and retrieve it via a gateway URL.

**Intermediate**
- Build a React frontend that reads data from a deployed smart contract (e.g., a counter or voting contract) and displays it live.
- Integrate a Chainlink price feed into a smart contract and display the fetched price on a frontend.

**Advanced**
- Build a full NFT minting dApp: contract stores metadata pointing to IPFS, and the React frontend lets a user connect their wallet, mint, and view their minted NFT.

## Course Links
- Alchemy University — Ethereum Developer Bootcamp
- buildspace — Project-Based Web3 Learning
- Chainlink Bootcamp / Chainlink Labs YouTube Tutorials
