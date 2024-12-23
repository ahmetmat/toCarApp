# ToCar: Car Tokenization Marketplace

https://embeddables.testnet.andromedaprotocol.io/galileo-4/toCarMarketplace

<div align="center">
  <img src="![Screenshot 2024-12-23 at 23 00 19](https://github.com/user-attachments/assets/988e1794-db14-4d04-a20f-835b11ba5bf5)
" alt="ToCar Banner" width="600" />
</div>

This project aims to **mint** car NFTs (following the cw721 standard) and list them on a **marketplace** built on the **Andromeda Protocol**. By leveraging the “Embeddable” feature, you can display your marketplace either in an external website (through an iframe) or directly within the Andromeda UI.

---

## Table of Contents

- [Features](#features)  
- [Screenshots](#screenshots)  
- [Prerequisites](#prerequisites)  
- [Project Structure](#project-structure)  
- [Contracts](#contracts)  
  - [cw721 (NFT)](#cw721-nft)  
  - [Marketplace](#marketplace)  
- [Step-by-Step Usage](#step-by-step-usage)  
  - [1. Mint an NFT](#1-mint-an-nft)  
  - [2. Approve and List on the Marketplace](#2-approve-and-list-on-the-marketplace)  
  - [3. Using the Embeddable Interface](#3-using-the-embeddable-interface)  
- [Live Demo (Link / iFrame)](#live-demo-link--iframe)  
- [Contributing](#contributing)  
- [License](#license)

---

## Features

- **Car NFTs**: cw721 standard NFTs with metadata containing plate number, model, year, color, etc.  
- **Marketplace Integration**: Sell or auction your car NFTs (depending on the marketplace version).  
- **Embeddable**: Easily embed your Andromeda marketplace via an iframe on external websites.  
- **Testnet + Mainnet**: Deploy on testnet first for trials, then move to mainnet.

---

## Screenshots

| Minting (cw721) | Marketplace Listings |
|:---------------:|:--------------------:|
| <img src="![Screenshot 2024-12-23 at 22 58 00](https://github.com/user-attachments/assets/ec9eeb6c-cd38-4adf-bbc7-9a40ba939c56)
" alt="Mint Screen" width="300" /> | <img src="![Screenshot 2024-12-23 at 23 06 13](https://github.com/user-attachments/assets/d0b1dde8-9a9e-44de-b503-38d2f4d64244)
" alt="Marketplace Listing" width="300" /> |


---

## Prerequisites

1. **Andromeda Testnet Wallet** (Keplr, Leap, etc.)  
2. Test tokens (`uandr`) from the [Faucet](https://docs.andromedaprotocol.io/) if needed.  
3. **(Optional) Rust & Cargo** – if you plan to compile/test custom CosmWasm contracts.  
4. **(Optional) Node.js & npm/yarn** – if you’re developing a React/Next.js frontend.

---

## Project Structure

This solution is built using the **Andromeda Flex Builder** and its “Embeddable” feature. The main files/folders might look like this:
