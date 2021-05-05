# Decentralized Star Notary Service Project

For this project, I created a DApp by creating a Star NOtary smart contract and deploying it on the public testnet (Rinkeby).
The Star Notary smart contract allows to:
- create a star
- transfer a star to another user
- exchange stars between users
- put a star up for sale at a particular price
- buy a star that has been previously put up for sale



### Rinkeby Deployed Artifacts:
- **ERC Token Name**: StarNotary
- **ERC Token Symbol**: SNY
- **Token Address**: [0x6c315b94a32a8104ed6fac5b46b3b9463fdcc89b](https://rinkeby.etherscan.io/token/0x6c315b94a32a8104ed6fac5b46b3b9463fdcc89b)


### Dependencies
- truffle v5.3.4
- openzeppelin 2.3.0

1. **Node and NPM** installed - NPM is distributed with [Node.js](https://www.npmjs.com/get-npm)
```bash
# Check Node version
node -v
# Check NPM version
npm -v
```


2. **Truffle v5.3.4** - A development framework for Ethereum. 
```bash
# Unsinstall any previous version
npm uninstall -g truffle
# Install
npm install -g truffle
# Specify a particular version
npm install -g truffle@5.0.2
# Verify the version
truffle version
```


2. **Metamask: 5.3.1 or above** - If you need to update Metamask just delete your Metamask extension and install it again.


3. [Ganache](https://www.trufflesuite.com/ganache) - Make sure that your Ganache and Truffle configuration file have the same port.


4. **Other mandatory packages**:
```bash
cd app
# install packages
npm install --save  openzeppelin-solidity@2.3
npm install --save  truffle-hdwallet-provider@1.0.17
npm install webpack-dev-server -g
npm install web3
```


### Run the application
1. Clean the frontend 
```bash
cd app
# Remove the node_modules  
# remove packages
rm -rf node_modules
# clean cache
npm cache clean
rm package-lock.json
# initialize npm (you can accept defaults)
npm init
# install all modules listed as dependencies in package.json
npm install
```


2. Start Truffle by running
```bash
# For starting the development console
truffle develop
# truffle console

# For compiling the contract, inside the development console, run:
compile

# For migrating the contract to the locally running Ethereum network, inside the development console
migrate --reset

# For running unit tests the contract, inside the development console, run:
test
```

3. Frontend - Once you are ready to start your frontend, run the following from the app folder:
```bash
cd app
npm run dev
```

---

