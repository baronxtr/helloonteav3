Hello on Tea DApp
Overview
Hello on Tea is a fun and interactive decentralized application (DApp) built on the Tea Sepolia Testnet. It allows users to connect their wallets, send "Hello" messages, update a shared message board, and mint unique NFTs—all while engaging with the Tea Protocol community. Designed as a lightweight and user-friendly experience, this DApp showcases the capabilities of blockchain technology in a playful and social way.
Features
Wallet Integration: Connect your MetaMask wallet to interact with the DApp on Tea Sepolia Testnet.

Say Hello: Increment a global click counter and log your interaction on-chain with a simple "Say Hello" button.

Custom Messages: Set a new message (up to 15 characters) to be displayed publicly, with built-in filters for inappropriate content.

NFT Minting: Mint a special "Hello on Tea" NFT for 0.1 TEA, complete with a supply tracker and transaction confirmation.

Leaderboard: View the top 50 wallets by interaction count and see your own ranking.

Social Sharing: Share your experience on Twitter and Farcaster with pre-crafted posts.

Audio Experience: Enjoy background music with a toggleable play/mute button.

Responsive Design: Optimized for both desktop and mobile devices with a retro-inspired UI.

Tech Stack
Frontend: HTML5, CSS3, JavaScript

Blockchain: Tea Sepolia Testnet (Ethereum-compatible)

Smart Contracts: Solidity, deployed at:
Main Contract: 0x073CF9B93A3F40A4B5e8634DA06Bf5A63545780E

NFT Contract: 0xFbA581414A171B940001295B8BB61584EA43Ad86

Libraries: Ethers.js (v5.7.2) for wallet and contract interactions

IPFS: Hosted images and assets via 4everland IPFS gateway

Fonts: Press Start 2P (Google Fonts) for a retro aesthetic

Prerequisites
A MetaMask wallet with Tea Sepolia Testnet configured.

Testnet TEA tokens (available via faucets for Tea Sepolia).

A modern web browser (Chrome, Firefox, Edge) with MetaMask extension installed.

Installation
Clone the Repository:
bash

git clone https://github.com/yourusername/hello-on-tea.git

Open the Project:
Navigate to the project folder and open index.html in a browser, or

Serve it locally using a simple HTTP server (e.g., npx live-server).

Connect to Tea Sepolia:
Ensure your MetaMask is set to the Tea Sepolia Testnet (Chain ID: 10218).

Add the network manually if needed:
RPC URL: https://tea-sepolia.g.alchemy.com/public

Chain ID: 10218

Currency Symbol: TEA

Explorer: https://sepolia.tea.xyz

Interact with the DApp:
Connect your wallet, say "Hello," update the message, or mint an NFT!

Usage
Connect Wallet: Click "Connect Wallet" to link your MetaMask.

Say Hello: Press "Say Hello" to record your interaction on-chain.

Update Message: Enter a short message and click "Update Message" to set it.

Mint NFT: Click "Mint NFT" to claim your "Hello on Tea" NFT for 0.1 TEA.

Leaderboard: Toggle the leaderboard to see top interactors.

Share: Use the Twitter or Farcaster buttons to spread the word.

Optimization
Lazy Loading: Images are loaded lazily to improve initial page load time.

Async Scripts: External scripts (e.g., Ethers.js) are loaded asynchronously to prevent blocking.

IPFS Hosting: Assets are served via IPFS for decentralized and efficient delivery.

Notes
Due to high traffic on Tea Sepolia, there may be occasional delays in data updates—patience is appreciated!

The DApp is intended for testnet use only; no real funds are involved.

Credits
Built with  by @0xdor
. Powered by the Tea Protocol.
License
This project is licensed under the MIT License. See the LICENSE file for details.

