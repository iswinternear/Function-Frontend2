# Function-Frontend

This program is simple program that demonstrates the functions and displays the values in the frontend of the application. This program is
a partial requirement for the ETH + AVAX PROOF: Intermediate EVM Course.

## Description

This program is written in JavaScript and Solidity. The program has three main functions:

connectAccount - which connects the user's metamask wallet

deposit - which deposits 1 ETH 

withdraw - which withdraws 1 ETH

## Getting Started

### Executing program

To run this program, I recommend using Gitpod. To open, click the link here: https://gitpod.io/.

Click "New Workspace" button and paste this link: https://github.com/iswinternear/Function-Frontend2.git

Create three terminal and type these commands

In the first terminal, type: npm i

In the second terminal, type: npx hardhat node

In the third terminal, type: npx hardhat run --network localhost scripts/deploy.js

Go back to the first terminal and type: npm run dev

Click the "Connect MetaMask Wallet" button to connect your Metamask wallet to the app. After successfully connecting your wallet to the app, it will display your address and the balance inside your wallet, and two buttons: Deposit 1 ETH and Withdraw 1 ETH.

## Authors

Jhon Louise Tan
