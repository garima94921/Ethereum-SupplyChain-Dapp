# Supply chain & data auditing

## Overview
This DAPP is for a decentralized approach for certifcation schemes, issuance and verification.
Any party can become a Certifier and assign a suitable Authority that can delegate authority of certification

## Deployment Details

https://rinkeby.etherscan.io/tx/0xa9243fc0d29fecc43ab50b02a3fb17fac58a94fd069867a71bac4f96f2cbc0f1

## The contract addresses of this dapp

|FarmerRole| 0xf17f52151EbEF6C7334FAD080c5704D77216b732|
|DistributorRole| 0xC5fdf4076b8F3A5357c5E395ab970B5B54098Fef|
|RetailerRole| 0x821aEa9a577a9b44299B9c15c88cf3087F3b5544|
|ConsumerRole| 0x0d1d4e623D10F9FBA5Db95830F7d3839406C6AF2|
|Contract Owner| 0x627306090abaB3A6e1400e9345bC60c78a8BEf57|

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Please make sure you've already installed ganache-cli, Truffle and enabled MetaMask extension in your browser.


### Installing

```
npm install
```
```
ganache-cli -m "spirit supply whale amount human item harsh scare congress discover talent hamster"
```

In a separate terminal window, test the DApp:

```
truffle compile
truffle migrate
truffle test
```

In a separate terminal window, launch the DApp:

```
npm run dev
```
## Deployment:

To deploy the smart contract to the rinkeby test network below steps were followed -

After running tests: 

```
truffle develop 
```

to open the truffle console.
Compile and deploy the smart contract using:

```
compile
truffle migrate --reset --network rinkeby
```

## Images:

### Activity Diagram
![Activity Diagram](https://github.com/garima94921/Ethereum-SupplyChain-Dapp/blob/master/Images/Activity%20diagram.png)

### Sequence Diagram
![Sequence Diagram](https://github.com/garima94921/Ethereum-SupplyChain-Dapp/blob/master/Images/Sequence%20diagram.png)

### State Diagram
![State Diagram](https://github.com/garima94921/Ethereum-SupplyChain-Dapp/blob/master/Images/state%20diagram.png)

### Class Diagram
![Class Diagram](https://github.com/garima94921/Ethereum-SupplyChain-Dapp/blob/master/Images/UML%20Class.png)


## Built With

* [Ethereum](https://www.ethereum.org/) - Ethereum is a decentralized platform that runs smart contracts
* [IPFS](https://ipfs.io/) - IPFS is the Distributed Web | A peer-to-peer hypermedia protocol
to make the web faster, safer, and more open.
* [Truffle Framework](http://truffleframework.com/) - Truffle is the most popular development framework for Ethereum with a mission to make your life a whole lot easier.


## Authors

[Garima Bothra] (https://github.com/garima94921)

See also the list of [contributors](https://github.com/your/project/contributors.md) who participated in this project.

## Acknowledgments

* Solidity
* Ganache-cli
* Truffle
* IPFS
* Template code from Udacity
