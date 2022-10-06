# Charla

Charla is a social media platform that runs on Coinex Smart Chain. Currently, this demo has been deployed to Testnet.

Just like any other Node project, you can launch this by running the following commands:

npm install
npm run start

Before running, make sure you have MetaMask installed and you have added the CSC Testnet.

Also, please be sure to update to your deployed contract by making changes to these files:
./src/utils/CharlaContract.json (swap out with the json file that was created AFTER deploying your contract)
./src/config.js (this file must have your contract address)