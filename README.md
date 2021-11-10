# Ethereum Blockchain Application - Todo List

Simple and secure todo list powered by smart contracts.

## New Technologies:
* [Solidity](https://docs.soliditylang.org/en/v0.5.3/) - High-level language for implementing Smart Contracts 
* [Truffle Framework](https://www.trufflesuite.com/truffle) - Ethereum DApps 
* [Ganache](https://www.trufflesuite.com/ganache) - Personal Ethereum blockchain on your local machine
* [Metamask](https://metamask.io/) Ethereum Wallet - Chrome Extension 
* [web3.js](https://web3js.readthedocs.io/en/v1.3.4/) - Library for interacting with Ethereum blockchain 
* [Node.js](https://nodejs.org/en/)

## Deployment 
1. Install Metamask browser extension to securely connect to Ethereum blockchain. <br>Metamask allows for managing our personal account when connecting to the blockchain, as well as manage ETH funds needed to pay for transactions. 

<img width="794" alt="9-metamask" src="https://user-images.githubusercontent.com/59374267/123530068-5cd2c280-d6ab-11eb-9e0b-85c6411f3602.png"><br>
2. Install Ganache to set up our own blockchains that we will use to secure the todo list items. <br>Its a Local development blockchain used to mimic the behavior of a public blockchain. Allows for deploying smart contracts, develop applications, and run tests.

<img width="1195" alt="Screen Shot 2021-06-26 at 6 29 06 PM" src="https://user-images.githubusercontent.com/59374267/123530177-67418c00-d6ac-11eb-8b5e-3afd65fc48fc.png"><br>
3. Install nodejs and npm. 
4. Other deployment steps:
```bash
# Installing dependencies 
$ npm install -g truffle@5.0.2
$ npm install

# Migrate the smart contract 
truffle migrate --reset

# Run the app
$ npm run dev
```
