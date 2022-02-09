# mint your own nfts!

### **What is it?**
This is a simple NFT minting site that runs on a custom smart contract and deploy to the Rinkeby etheruem testnet. It features a simple UI created in ReactJS that allows you to mint and view your own NFTs on the testnet. Web3 takeover !
To learn more about the smart contract and minting view the info below.
### **Site Setup**
To get started with this site, please use the following commands:

1. Run `npm install` at the root of your directory
2. Run `npm run start` to start the project
3. Open http://localhost:3000 in your browser
4. Mint a NFT!

### **Smart Contract Info**
You can find the full smart contract project structured on [GitFront](https://gitfront.io/r/user-5698640/862f843eb2c63eff3615783f3c26c4976ff5fc7a/mintanft-smartcontract):
Note: you need to make sure you add your own `hardhat.config.js` file to the root of your contract dir and update the contract address in the referencing files. 

The files provided in this repo include:
- `MyNft.sol` - main smart contract file
- `scripts/deploy.js` - deploys the smart contract to the testnet
- `libraries/Base64.sol` - base64 library for encoding and decoding

### **Dependencies**
- nodejs/npm - used to run the project
- hardhat - tool used to help deploy smart contract
- solidity - lang used to compile smart contract
- reactjs - used to create site UI
- metamask - interacts with rinkeby testnet and site, only wallet supported for mint currently
