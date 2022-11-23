# dapp-marketplace-hardhat
Dapp developed with Solidity, React, Ganache and Hardhat in Ethereum blockchain

### 1. Install Dependencies:
`$ npm install`
### 2. Start local Blockchain for development
`$ npx hardhat node`

### 3. Connect accounts to blockchain by Metamask
- Copy accounts private key and import to Metamask
- Connect Metamask to Hardhat Blockchain, 127.0.0.1:8545

### 4. Migrate Smart Contracts
`$ npx hardhat run src/backend/scripts/deploy.js`

### 5. Execute Tests
`$ npx hardhat test`

### 6. Start Frontend
`$ npm run start`