# OnChainCTMS
Blockchain + Clinical Trial Management SaaS

## Overview
Integrating NERO Chain with a Clinical Trial Management System (CTMS) involves connecting the blockchain’s innovative features—like flexible gas fees, token utility, and account abstraction—to enhance transparency, auditability, and compliance in clinical research processes. NERO's framework can significantly enhance clinical trial SaaS software by addressing key pain points in the industry like data integrity, transparency, patient consent, and traceability.

## Features  
- **NERO L2 Integration**: Low fees enable frequent, cost-effective data logging.  
- **Data Provenance and Integrity**: Data hashes (not the raw data itself) can be written to NERO to ensure it hasn't been altered.
- **Immutable Audit Trails**: Each change or data entry can be timestamped and recorded on-chain via NERO. This creates a tamper-proof audit trail—perfect for regulatory compliance.
- **Token-Based Incentives**: 1. Problem Identification => Patient retention and engagement in long trials is tough; 2. Blockchain Solution => Tokens or NFTs could reward patient milestones (e.g., completed visits, reporting side effects); 3. Patient Benefits => Creating a gamified experience with optional off-chain redeemable value.
- **Transparent Randomization & Blinding**: Bias in randomization and unblinding can skew trial results, compromising the scientific validity of clinical studies. Randomization logic encoded in smart contracts ensures provably fair treatment allocation, which is verifiable by third parties.


## Tech Stack
- **Blockchain**: NERO, Solidity, foundry
- **Frontend**: Next.js, ethers.js, tailwind css  
- **Tools**: , IPFS.

## Getting Started  
1. Clone the repo:  
   ```bash  
   git clone https://github.com/bisectracky/OnChainCTMS.git
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
