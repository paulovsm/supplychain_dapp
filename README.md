# Supply Chain DApp


>
## Contract Address (Rinkeby)
>
[0x98BfE69b60c200DbcCfBDCb1d9A145a9b77ca0e9](https://rinkeby.etherscan.io/address/0x98BfE69b60c200DbcCfBDCb1d9A145a9b77ca0e9)
>

## Requirement 1: Project write-up - UML

### Activity Diagram
[Model Diagrams](uml/model.md)


## Requirement 2: Project write-up - Libraries
### Libraries Version
>
    Truffle v5.5.21 (core: 5.5.21)
    Ganache v7.2.0
    Solidity v0.5.16 (solc-js)
    Node v16.14.2
    Web3.js v1.7.4

## Requirement 3: Project write-up - IPFS
I used IPFS to deliver my website for this project. HTML, CSS, and JS files have been added to IPFS in order to fully decentralize my Supply Chain DAPP.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Installing

A step by step series of examples that tell you have to get a development env running

```
cd application
npm install

```

Launch Truffle in Developoment Mode:

```
truffle dev"
```

In a separate terminal window, Compile smart contracts:

```
truffle compile
```

This will create the smart contract artifacts in folder ```build\contracts```.

Migrate smart contracts to the locally running blockchain, ganache-cli:

```
truffle migrate
```

Test smart contracts:

```
truffle test
```

All 10 tests should pass.

In a separate terminal window, launch the DApp:

```
npm run dev
```
