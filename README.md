# Project 05. Decentralized Star Notary on Ethereum

This is project 5 of Blockchain Developer Nanodegree at Udacity. In this project, I have implemented the required functionality and test cases for the decentralized star notary dapp using ethereum and various associated tools.

## Udacity Review
https://review.udacity.com/#!/reviews/1795413

## General Information

ERC-721 Token Name: **S.T.A.R. Labs**\
ERC-721 Token Symbol: **STAR**\
Truffle Version: **v5.0.2**\
OpenZeppelin: **v2.1.2**\
Rinkeby Network Token Address: **[0xD7aaB9c050dd894be5B83c2F4d25ac63f482aD4C](https://rinkeby.etherscan.io/address/0xd7aab9c050dd894be5b83c2f4d25ac63f482ad4c)**\

## Getting Started

To run this project you will need the following:

1) **Truffle v5.0.12 (core: 5.0.12)** - a development framework for Ethereum (Verify using `truffle version`)\
If you need to update truffle to the latest version use: `npm install -g truffle`
2) **Metamask: 5.3.1**\
If you need to update Metamask just delete your Metamask extension and install it again.
3) **truffle-hdwallet-provider@1.0.6** (Run this command in the project root directory: `npm install truffle-hdwallet-provider@1.0.6`)
4) **openzeppelin-solidity@2.1.2** (Run this command in the project root directory: `npm install openzeppelin-solidity@2.1.2`)
5)  * Solidity v0.5.0 (solc-js)
    * Node v10.15.3
    * Web3.js v1.0.0-beta.37

## How to run

To run your application you will need to:

* Run `truffle develop` or `sudo truffle develop` commands.
* Run `compile` command.
* Run `migrate --reset`
* Run `test`

Then

Open a second terminal window, and make sure you are inside the project directory.

* Run `cd app` to move inside the app folder.
* Run `npm run dev` command.

This will start the web server at port 8080. Open http://localhost:8080/ in your browser. Make sure the Metamask extension is installed, and you are logged into it, and also have imported the accounts.
