Project Link: https://crowdsale-kyle-tredway.netlify.app/

Local Development Requirements

To run this project locally, you’ll need Hardhat and MetaMask set up correctly.

First, make sure Hardhat is installed on your machine and that all project dependencies are installed.

Next, start a local Hardhat blockchain by running the Hardhat node. This will create local test accounts and simulate an Ethereum network.

In MetaMask, add the Hardhat local network and import one of the generated Hardhat accounts using its private key. This account will be used to deploy contracts and interact with the dApp.

After the node is running, deploy the smart contracts by running the project’s deployment script. This will deploy the token and crowdsale contracts to the local Hardhat network.

Once deployed, start the frontend and connect MetaMask to the Hardhat network. The application will only function correctly if MetaMask is connected to the same local network where the contracts were deployed.
