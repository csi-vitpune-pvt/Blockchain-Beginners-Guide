# Phase 1: Blockchain & Cryptography Fundamentals

This phase builds the theoretical foundation every blockchain developer needs before touching any code. It covers how distributed ledgers work, the cryptography that secures them, and the consensus mechanisms that let untrusted parties agree on shared state.

## Topics List

### 1.1 What is Blockchain?
- The Problem of Trust in Distributed Systems
- Centralized vs. Decentralized vs. Distributed Systems
- Key Principles: Decentralization, Immutability, and Transparency
- Blocks, Chains, and Distributed Ledgers
- Public, Private, and Consortium Blockchains

### 1.2 Cryptography Basics
- Hash Functions (SHA-256, Keccak-256) and Their Properties
- Public-Key (Asymmetric) Cryptography
- Digital Signatures and How They Prove Ownership
- Merkle Trees and Merkle Proofs
- Elliptic Curve Cryptography (ECDSA) — Conceptual Overview

### 1.3 Consensus Mechanisms
- Why Consensus Matters: The Byzantine Generals Problem
- Proof of Work (PoW) — Mining and Security Trade-offs
- Proof of Stake (PoS) — Validators and Staking
- Other Mechanisms: Delegated PoS, Proof of Authority, Proof of History
- Finality vs. Probabilistic Consensus

### 1.4 Bitcoin & the UTXO Model
- Bitcoin's Origins and the Bitcoin Whitepaper
- The UTXO (Unspent Transaction Output) Model
- Transactions, Fees, and Mempools
- Bitcoin Scripting Basics
- Halving and Bitcoin's Monetary Policy

### 1.5 Wallets & Key Security
- Public vs. Private Keys
- Hot Wallets vs. Cold Wallets (Hardware Wallets)
- Seed Phrases (BIP-39) and Hierarchical Deterministic Wallets (BIP-32/44)
- Custodial vs. Non-Custodial Wallets
- Best Practices for Key Management and Security

## Resources

**1. What is Blockchain?**
- Resource
  - Bitcoin Whitepaper by Satoshi Nakamoto (foundational reading)
  - Blockchain Explained in 2 Minutes (quick overview video)
  - Whiteboard Crypto YouTube Channel (beginner-friendly concepts)
  - Simply Explained YouTube Channel (visual breakdowns of blockchain concepts)
- Reference Material
  - Ethereum.org — Introduction to Blockchain

**2. Cryptography Basics**
- Resource
  - Khan Academy — Journey into Cryptography
  - 3Blue1Brown — But How Does Bitcoin Actually Work? (visual explainer)
  - Computerphile — Public Key Cryptography Videos
- Reference Material
  - NIST — Secure Hash Standard (SHA-256) documentation

**3. Consensus Mechanisms**
- Resource
  - Finematics YouTube Channel (excellent visual explanations of PoW/PoS)
  - Coin Bureau — Consensus Mechanisms Explained
- Reference Material
  - Ethereum.org — Proof of Stake documentation

**4. Bitcoin & the UTXO Model**
- Resource
  - Bitcoin.org — How Bitcoin Works
  - Andreas Antonopoulos — "Mastering Bitcoin" (free online book)
- Reference Material
  - Bitcoin Developer Guide

**5. Wallets & Key Security**
- Resource
  - MetaMask Learn — Wallet Security Basics
  - Ledger Academy — Crypto Security Fundamentals
- Reference Material
  - BIP-39 Specification (Mnemonic Seed Phrases)

## Practice Exercises

**Beginner**
- Manually compute a SHA-256 hash of a text string using an online tool and observe the avalanche effect (change one character, see the hash change completely).
- Set up a MetaMask wallet on a testnet and safely back up a seed phrase (using a test wallet only, never a real one).
- Explore a block explorer (e.g., Etherscan or a Bitcoin explorer) and trace a real transaction from sender to receiver.

**Intermediate**
- Write a simple script (Python or JS) that builds a basic Merkle tree from a list of transactions and verifies a Merkle proof.
- Simulate a basic Proof of Work algorithm by writing code that finds a nonce producing a hash with a certain number of leading zeros.

**Advanced**
- Research and write a short comparison of PoW vs. PoS security assumptions (cost of attack, energy use, decentralization trade-offs).

## Courses(Optional) 
- Cyfrin Updraft — Blockchain Basics Course (free)
- freeCodeCamp — Blockchain and Cryptocurrency Explained
- Coursera — Bitcoin and Cryptocurrency Technologies (Princeton University)
