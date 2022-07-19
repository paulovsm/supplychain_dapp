# Supply Chain DApp

[Dapp URL](https://infura-ipfs.io/ipfs/QmYYrkgtuaxwgjLYdBaWT3e7vTwuaWDjc6Sz4Dd8qEeytu)

>
## Contract Address (Rinkeby)
>
[0x98BfE69b60c200DbcCfBDCb1d9A145a9b77ca0e9](https://rinkeby.etherscan.io/address/0x98BfE69b60c200DbcCfBDCb1d9A145a9b77ca0e9)

Transaction ID - 0xecf17ee70ddcdce828e4432b9aadba03d77c7f851dc4596a4a6c238ebf6abc71

[Contract creation log](truffle-logs/deploy_rinkeby_log.txt)

<br>

## Requirement 1: Project write-up - UML

### Activity Diagram
[Model Diagrams](uml/model.md)

<br>

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
### DApp UI 

![DApp UI 1](/application/app-log/Dapp_UI_1.png)
![DApp UI 2](/application/app-log/Dapp_UI_2.png)
![DApp UI 3](/application/app-log/Dapp_UI_3.png)

### Transaction History (Example)
![Tx History](/application/app-log/item_transaction_history.png)