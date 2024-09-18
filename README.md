# Project Setup and Deployment

## Installation

To get started, after cloning the repository, you need to install the required packages. Run the following command:

```bash
npm install
```

### Compiling and Deploying the Smart Contract

Before running the application, you must compile the smart contract and upload it to the blockchain. Execute the following commands:

```bash
npx hardhat compile
npx hardhat run scripts/deploy.js --network sepolia
```

### Running the Application

Once the contract is deployed, start the application by running:

```bash
npm start
```
