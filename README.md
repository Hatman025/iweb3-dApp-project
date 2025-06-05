PROJECT TITLE: Reward DApp Video Demo: https://youtu.be/zdKJ8aZZW0I Description: The Reward Dapp is an that gives rewards. This app is like a small Ethereum wallet you use in your browser. It works with MetaMask, it is like a key to your Ethereum money. When you click on "Receive token Wallet" button the app connect with metamask, when connected to metamask it shows your Ethereum address. The app let you send reward in Ethereum to someone by inputting the receiver ethereum address and also the amount of ETH you want to send. You send the ethereum by clicking the "Send Reward (ETH)" button to credit the receiver wallet.

Overview of the DApp: “REward DApp Wallet” This decentralized application (DApp) called “REward DApp Wallet” is a simple web-based tool that allows users to interact directly with the Ethereum blockchain using their browser wallet, such as MetaMask. The primary features of the DApp are:

Connecting a user's Ethereum wallet

Viewing the user's ETH balance

Sending ETH to another Ethereum address

Although it may seem simple, this app demonstrates the fundamental building blocks of Web3 development. It shows how a web app can communicate with the Ethereum blockchain using JavaScript libraries like Ethers.js, and how wallet extensions like MetaMask bridge the gap between users and decentralized networks.

🏗️ Project Architecture This DApp is built using the following components:

Vite (Build Tool) Vite is a fast and lightweight frontend build tool that allows for rapid development. Unlike traditional tools like Webpack, Vite uses native ES modules in the browser during development, leading to faster startup and instant hot module replacement (HMR).
In our project, Vite is used to scaffold the initial project structure, manage JavaScript modules, and serve the app during development.

Vanilla JavaScript & HTML Rather than using frameworks like React or Vue, this app is built using plain HTML and JavaScript. This keeps the project simple and helps beginners focus on understanding blockchain interaction without needing to learn frontend frameworks.

Ethers.js Ethers.js is a lightweight library that allows JavaScript applications to interact with the Ethereum blockchain. It supports connecting to wallets, querying balances, sending transactions, interacting with smart contracts, and more.

In this DApp, Ethers.js is used to:

Connect to the MetaMask provider

Fetch the user’s Ethereum address

Read the ETH balance from the blockchain

Send ETH to other wallets

MetaMask MetaMask is a browser extension that acts as a digital wallet. It allows users to securely store and manage their Ethereum accounts and interact with DApps directly from their browser.
Our app depends on MetaMask to:

Request account access

Sign and send ETH transactions

This App let you check your ethereum reward wallet and also send reward to someone with ethereum account. The App was created using Vite, the index.html code and CSS file was edited to create the final Reward DApp UI

