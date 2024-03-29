﻿# StakingDapp - Smart Contract & DApp Deployment Guide

Welcome to the StakingDapp project! This guide provides instructions for deploying smart contracts and running the DApp. If you're interested in a Hindi tutorial, check out the [Staking Dapp Tutorial (Hindi)](https://www.youtube.com/@CodeEater21).

## Overview of Staking DApp

StakingDapp is a decentralized application allowing users to stake ERC20 tokens and earn rewards. Users stake tokens, generating reward tokens per second based on the staked amount. This guide outlines key tokens, how the DApp works, and instructions for smart contract interactions.

### Key Tokens

- **Stake Token:** ERC20 token for staking; requires approval before staking.
  
- **Reward Token:** ERC20 token generated per second during staking; users earn these as rewards.

## How the Staking DApp Works

1. **Stake Tokens:**
   - Users approve stake tokens for staking via the staking smart contract.

2. **Generate Reward Tokens:**
   - Staking generates reward tokens per second based on the staked amount.

3. **Accumulate Rewards:**
   - Users accumulate reward tokens over time.

4. **Claim Rewards:**
   - Users claim accumulated rewards using the `getReward()` function.

5. **Unstake Tokens:**
   - Users can unstake tokens to retrieve staked tokens and rewards.

## Smart Contract Instructions

### 1) Approve Stake Token
Before using `stake()`, approve stake tokens to the staking contract.

### 2) Transfer Reward Token
Before using `getReward()`, transfer reward tokens to the staking contract.

## DApp Instructions

### Prerequisites
- **Metamask:** Install Metamask for DApp access.

### Steps to Deploy Smart Contracts on Sepolia
1. Deploy staking, stake token, and reward token smart contracts on Sepolia.
   
### Configuration for the DApp

1. **Copy and Paste ABI**
   - Copy ABIs of staking contract and stake token.
   - Paste ABIs into `src/ABI` folder.

2. **Update Contract Addresses**
   - Update staking contract and stake token addresses in `utils/connectWallet.jsx`.

### Running the DApp Locally

1. **Navigate to the Client Directory**
   ```bash
   cd client
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Start the Development Server**
   ```bash
   npm run dev
   ```

Feel free to reach out if you encounter any issues!
