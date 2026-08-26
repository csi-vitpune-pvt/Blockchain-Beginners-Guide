# Phase 3: Smart Contracts & Programming

This phase moves from theory into hands-on development — writing, testing, and securing smart contracts, and getting a first look at how different chains approach contract programming.

## Topics List

### 3.1 Solidity Fundamentals
- Structure of a Smart Contract (pragma, contract, constructor)
- Variables and Data Types (uint, string, address, bool, structs, mappings, arrays)
- Operators and Control Flow
- Functions (Visibility: public, private, internal, external)
- State Modifiers (view, pure, payable)

### 3.2 Advanced Solidity Concepts
- Events and Logging
- Inheritance & Interfaces
- Error Handling (require, revert, assert, custom errors)
- Common Security Vulnerabilities (Re-entrancy, Integer Overflow, Access Control Flaws)
- Gas Optimization Techniques

### 3.3 Token Standards
- ERC-20: Fungible Tokens
- ERC-721: Non-Fungible Tokens (NFTs)
- ERC-1155: Multi-Token Standard
- Using OpenZeppelin for Secure, Audited Implementations

### 3.4 Beyond Solidity: Alternative Smart Contract Languages
- Rust for Solana Development (Anchor Framework)
- Move for Aptos & Sui
- Why Different Chains Use Different Languages (Design Philosophy)

### 3.5 Development Frameworks & Testing
- Why Use a Framework? (Compilation, Testing, Deployment)
- Overview of Hardhat (JavaScript-based) and Foundry (Solidity-based)
- Writing Automated Tests (Ethers.js, Chai, or Foundry's Forge)
- Running a Local Test Network
- Deploying to Public Testnets and Verifying Contracts on Explorers

## Resources

**1. Solidity Fundamentals**
- Resource
  - CryptoZombies (interactive coding school for Solidity)
  - Solidity Course by Patrick Collins (freeCodeCamp) — comprehensive video course
  - Learn Solidity in 1 Hour by EatTheBlocks (quick start video)
- Reference Material
  - Official Solidity Documentation

**2. Advanced Solidity Concepts**
- Resource
  - Smart Contract Security Field Guide by ConsenSys
  - Secureum — Smart Contract Security Bootcamp Notes
- Reference Material
  - SWC Registry (Smart Contract Weakness Classification)

**3. Token Standards**
- Resource
  - OpenZeppelin Contracts Wizard (interactive contract generator)
  - Alchemy — ERC-20 vs. ERC-721 vs. ERC-1155 Explained
- Reference Material
  - OpenZeppelin Contracts Documentation

**4. Beyond Solidity**
- Resource
  - Solana Anchor Book (official guide to the Anchor framework)
  - Aptos & Sui — Move Language Documentation and Tutorials
- Reference Material
  - Move Language Book

**5. Development Frameworks & Testing**
- Resource
  - Hardhat Tutorial (official step-by-step guide)
  - Foundry Book (official Foundry documentation and tutorials)
  - Hardhat for Beginners by Nader Dabit (video tutorial)
- Reference Material
  - Official Hardhat Documentation
  - Official Foundry Documentation

## Practice Exercises

**Beginner**
- Complete the CryptoZombies interactive course through at least Lesson 3.
- Write and deploy a simple "Hello World" storage contract that lets a user store and retrieve a number.

**Intermediate**
- Build an ERC-20 token contract using OpenZeppelin and deploy it to a testnet using Hardhat or Foundry.
- Write automated tests for a contract covering both expected behavior and failure cases (e.g., reverts on invalid input).

**Advanced**
- Deliberately write a contract with a re-entrancy vulnerability, then fix it using the checks-effects-interactions pattern or a reentrancy guard.
- Build an ERC-721 NFT minting contract with a supply cap and owner-only minting, then verify it on a block explorer.

## Course Links
- Cyfrin Updraft — Solidity & Smart Contract Security Courses (free)
- Solidity Course by Patrick Collins (freeCodeCamp, YouTube)
- Alchemy University — Ethereum Developer Bootcamp
- Solana Developer Bootcamp (Buildspace / Solana Foundation)
