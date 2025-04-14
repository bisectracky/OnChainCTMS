# MetisCTMS
Metis + Clinical Trial Management SaaS

## Overview
Metis L2 and  LazAI’s Alith framework can significantly enhance clinical trial SaaS software by addressing key pain points in the industry like data integrity, transparency, patient consent, and traceability.

## Features  
- **Real-time AI Analysis**: ML models predict data nonconformant and potential protocol deviation.  
- **Metis L2 Integration**: Low fees enable frequent, cost-effective data logging.  
- **Data Provenance and Integrity**: Data hashes (not the raw data itself) can be written to LazAI to ensure it hasn't been altered.
- **Immutable Audit Trails**: Each change or data entry can be timestamped and recorded on-chain via LazAI. This creates a tamper-proof audit trail—perfect for regulatory compliance.
- **Token-Based Incentives**:
--- ***Problem Identification***
         ****Patient retention and engagement in long trials is tough.****
    ***Blockchain Solution***
         ****Tokens or NFTs could reward patient milestones (e.g., completed visits, reporting side effects).****
    ***Patient Benefits***
         ****Creating a gamified experience with optional off-chain redeemable value.****

## Tech Stack
- **Blockchain**: Metis L2, Solidity, foundry
- **AI/ML**: Alith agents  
- **Frontend**: Next.js, ethers.js, tailwind css  
- **Tools**: LazAI Data Anchoring, IPFS.

## Getting Started  
1. Clone the repo:  
   ```bash  
   git clone https://github.com/MetisCTMS/core.git
   ```
2. Install dependencies:
  ```bash
  cd core && npm install
  ```
3. Deploy contracts:
   ```bash
   npx hardhat deploy --network metis
   ```
4. Start the frontend:
   ```bash
   cd frontend && npm start
   ```
