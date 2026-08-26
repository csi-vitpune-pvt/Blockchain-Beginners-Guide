# Phase 2: Blockchain Architecture & Multi-Chain Ecosystem

With the fundamentals in place, this phase explores how modern blockchain networks are actually built and how the ecosystem has diversified beyond Bitcoin into dozens of competing and complementary chains.

## Topics List

### 2.1 Ethereum & the EVM
- What is Ethereum? From Bitcoin to "World Computer"
- The Ethereum Virtual Machine (EVM)
- Account Model vs. UTXO Model
- Gas, Gas Limits, and Transaction Fees
- EIP-1559 and Fee Market Mechanics

### 2.2 Alternative Layer 1 Blockchains
- Solana — High-Throughput Architecture and Proof of History
- Cardano — Research-Driven, Peer-Reviewed Development
- Avalanche — Subnets and Consensus Protocol
- Polkadot — Relay Chain and Parachains
- Cosmos — The "Internet of Blockchains" and IBC Protocol
- Comparing Trade-offs: Speed, Decentralization, Security (the "Blockchain Trilemma")

### 2.3 Nodes, RPCs & Network Infrastructure
- Full Nodes vs. Light Nodes vs. Archive Nodes
- What is an RPC (Remote Procedure Call) Endpoint?
- Node Providers (Alchemy, Infura, QuickNode)
- Running Your Own Node vs. Using a Provider
- Block Explorers and How They Work

### 2.4 Tokenomics & Token Standards
- Native Coins vs. Tokens
- Fungible vs. Non-Fungible Assets
- Introduction to Token Standards (ERC-20, ERC-721, ERC-1155 — covered in depth in Phase 3)
- Basics of Token Supply, Inflation, and Vesting

### 2.5 Layer 2 & Scaling Solutions
- Why Blockchains Need to Scale
- Optimistic Rollups (Arbitrum, Optimism)
- Zero-Knowledge Rollups (zkSync, Starknet, Polygon zkEVM)
- Sidechains vs. Rollups vs. State Channels
- Polygon PoS as a Scaling Example

## Resources

**1. Ethereum & the EVM**
- Resource
  - Finematics — How Does Ethereum Work?
  - Whiteboard Crypto — EVM Explained
- Reference Material
  - Ethereum.org Developer Portal

**2. Alternative Layer 1 Blockchains**
- Resource
  - Coin Bureau — Layer 1 Blockchain Comparisons
  - Solana Foundation — Solana 101
  - Polkadot Wiki — Getting Started
- Reference Material
  - Cosmos Network Documentation

**3. Nodes, RPCs & Network Infrastructure**
- Resource
  - Alchemy — What is a Node? (blog/video series)
  - QuickNode Guides — RPC Basics
- Reference Material
  - Ethereum.org — Nodes and Clients documentation

**4. Tokenomics & Token Standards**
- Resource
  - Finematics — Tokenomics 101
  - Coin Bureau — Understanding Tokenomics
- Reference Material
  - Ethereum.org — Token Standards Overview

**5. Layer 2 & Scaling Solutions**
- Resource
  - Finematics — Rollups Explained (Optimistic vs. ZK)
  - Polygon Blog — Introduction to Layer 2 Scaling
- Reference Material
  - Ethereum.org — Layer 2 documentation

## Practice Exercises

**Beginner**
- Create a free RPC endpoint using a provider like Alchemy or Infura and use it to fetch the latest block number via a simple script.
- Compare gas fees for the same type of transaction across Ethereum mainnet, a Layer 2 (e.g., Arbitrum), and an alt-L1 (e.g., Solana) using their respective explorers.

**Intermediate**
- Set up a wallet connected to two different testnets (e.g., Ethereum Sepolia and Polygon Amoy) and send a test transaction on each.
- Write a script using a Web3 library to query token balances across two different EVM-compatible chains using the same wallet address.

**Advanced**
- Research and document the trade-offs of the Blockchain Trilemma for three different chains (e.g., Ethereum, Solana, Cosmos) and present which design choices each made.

## Course Links
- Alchemy University — Ethereum Developer Bootcamp (free)
- Solana Bootcamp (Buildspace / Solana Foundation)
- Coursera — Blockchain Specialization (University at Buffalo / SUNY)
