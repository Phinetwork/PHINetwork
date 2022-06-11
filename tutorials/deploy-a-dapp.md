# 📳 Deploy a dApp

## Overview

The purpose of this tutorial is to help you on launching and deploying your Ethereum dApp on PHI Network. We have compiled a series of resources designated to help you get the basics of PHI Network and how it works, explain to you how to connect to our mainnet public ledger, and how to use an array of existing IDEs, tools, and libraries to develop and deploy on PHI Network.

## Platform Basics

[PHI Network](https://phi.network) is an open-source [DAG](../glossary/#d) programable [smart contracts](../glossary/#s) platform built for decentralized and enterprise-level applications, in one highly scalable [ecosystem](https://phi.network/resources). It is ideal for you to deploy and run your dApp, as it will present you not only with a reliable platform to do so, but an array of development tools that will help you to scale your idea.

We run two public ledgers where you can deploy your dApp, PHI Network, and Divine Testnet - our **mainnet** and our **testnet** respectively. You can definitely run a production dApp on Divine Testnet, the main difference laying on the fact that on Divine Testnet you won't be able to monetize it on-chain, as DST (Divine Testnet's native token) can be acquired for free.

Both our public ledgers run a fork [go-ethereum](https://geth.ethereum.org/docs/getting-started), called go-phi, that has the networking, consensus, and console features replaced with PHI Network's equivalents, what's left being the Ethereum Virtual Machine, which runs Solidity smart contracts and manages data structures and blocks on the network. That means it is compatible with Ethereum dApps, as well as with its IDEs, and most wallet providers.

## Network Interaction

PHI Network uses a subset of the Ethereum API methods, which you can explorer further in our JSON RPC Methods page, but overall, you can use all the familiar APIs and IDEs that are available on Ethereum for interacting with PHI Network.

### Using a Web 3 Wallet

PHI Network is compatible with [most Web 3 wallets](../use-phi-smart-chain/compatible-wallets/) that supports Ethereum and allow custom networks to be added, including the widely used [MetaMask](../use-phi-smart-chain/additional-wallets-setup/metamask-setup.md) and [Coinbase](broken-reference) Wallet applications. You can find more information on how to get your Web 3 wallet up and running on PHI Network in our [Wallet Setup page](../use-phi-smart-chain/additional-wallets-setup/).

### Using the Public APIs

Instead of proxying your network interaction through a Web 3 wallet provider, you can use any official public node to call PHI Network's publicly available APIs.

If you chose to use a public node, some API modules won't be available for security reasons. You can check on all the publicly available API call methods in our [JSON RPC Methods page](broken-reference), or if your application requires modules that are not publicly accessible, you can [run your own node](../developers/run-a-node.md) to use them.

### Running a Local Test Network

You can run your own instance of PHI Network for development and testing purposes. For that you can download and install our publicly available versions of either go-phi or go-divine in your local machine.

## Developing and Deploying Contracts

Being compatible with Ethereum, most development tools available for Ethereum will also be compatible with PHI Network. A list of the most used IDEs to deploy smart contracts below:

* [Remix](https://remix.ethereum.org/)
* [Truffle](https://trufflesuite.com/)
* [Hardhat](https://hardhat.org/)

You can also use any Solidity-compatible IDE to write, develop, and integrate your smart contracts with your decentralized application written in Javascript, Typescript, VUE, etc. The most common IDEs used by us to develop our PHI Network-compatible applications are the [Microsoft Visual Studio](https://visualstudio.microsoft.com/) and [Atom](https://atom.io/).

## PHI Explorer

If you are deploying in one of our public ledgers, you will be able to use our officially supported block explorer to index and pull blockchain data.

## Faucets

You can Earn PHI on [PHI.Network](https://phi.network)  If you need larger quantities of PHI  you can buy it [here](https://buy.phi.holdings/product/phi).&#x20;

## Contract Function Calls

You don't have to verify your contract to call its functions on PHI Network. We have made available our [Smart Contracts interface](https://contract.phi.network), where you can upload your contract's ABI code, specify its network address, and call its functions.

## Further Support

We strive to have a comprehensive and easy-to-read documentation, but if you cannot find what you are looking for here, feel free to reach out to our support team directly, and we will be happy to help.
