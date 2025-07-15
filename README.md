# Sneaker Resale Auction dApp — Powered by Andromeda Protocol

> *Built on the [Andromeda Protocol](https://www.andromedaprotocol.io/) testnet using ANDR tokens.*

---

## Overview

Welcome to the **Sneaker Resale Auction dApp**, a decentralized application that transforms how rare sneakers are resold. Powered by the Andromeda Protocol and its ADOs (Andromeda Digital Objects), our platform enables sneakerheads to bid, buy, and resell authentic, limited-edition sneakers through secure and transparent blockchain auctions using **ANDR testnet tokens**.

---

## DEMO LINK

_Deployed on Vercel_  [ SneakSale](https://sneaksale.vercel.app/)

---
# Embeddable Demo Link
[https://embeddables.testnet.andromedaprotocol.io/galileo-4/Sneaker-Resale](https://embeddables.testnet.andromedaprotocol.io/galileo-4/Sneaker-Resale)

# Andromeda Testnet Wallet Address
andr1kdqz6q7etk9xzmwlu9p7u7kwdrkwcqf83l0vhf

## Visual Tour

### 🏠 Hero & Navigation
Sleek landing interface with quick navigation to Live Auctions, Upcoming Drops, User Profile, and Bidding History.

<img width="1280" height="720" alt="Untitled" src="https://github.com/user-attachments/assets/7a6c4f49-8550-4290-bb32-88c6278c0624" />

### 🔥 Hot Deals
View the hottest sales on ongoing sneaker resale auctions, with real-time bidding data and countdowns.

<img width="1280" height="720" alt="3" src="https://github.com/user-attachments/assets/1ee5821f-0c11-4bbe-b9d5-ff289dbe6434" />



### 🥇 Featured Collections  
Get details of the sneaker of the featured sneakers of the week this will be editor-picked.

<img width="1280" height="720" alt="4" src="https://github.com/user-attachments/assets/579f1a5f-265b-4530-8130-5e19c21bcff7" />


### 👟 Explore Sneakers
Every sneaker is a unique NFT with detailed metadata — brand, size, release year, condition, rarity tier, and seller profile.

<img width="1280" height="720" alt="2" src="https://github.com/user-attachments/assets/05e3074b-0298-4a7f-a762-0ef9a6e3066a" />


### 🧾 Help 
A detailed Q&A section with most asked questions and doubts.

<img width="1280" height="720" alt="5" src="https://github.com/user-attachments/assets/8a263943-e672-4e28-a614-036dccb78789" />


---

## Features

-   **NFT-Based Sneaker Listings**: Each sneaker is tokenized as an NFT to prove authenticity and ownership.
-   **Decentralized Auction System**: Transparent, time-bound auctions for fair resale pricing.
-   **Bid with ANDR Tokens**: Users bid using **ANDR testnet tokens** on the Andromeda Testnet.
-   **Real-time Bidding**: Track bids in real-time with instant updates.
-   **Auction Automation**: Auctions automatically close and transfer ownership upon timeout.
-   **Secure Wallet Integration**: Seamless wallet login for minting, bidding, and claiming NFTs.
-   **Responsive Design**: Fully functional on mobile and desktop.

---

## Use Cases

1.  **Sneakerhead Marketplace**
    -   Resell rare sneakers as NFTs.
    -   Enable global access to limited drops and resale markets.
    -   Track ownership, resale history, and sneaker provenance on-chain.

2.  **Hot Deals**
    -   Limited-time auctions for hyped sneakers (e.g., Travis Scott x Jordan, Off-White collabs).
    -   Bidders compete live using ANDR tokens.

3.  **Sneaker Collections**
    -   Showcase sneaker NFTs in a digital collection.
    -   View rarity score, estimated resale value, and previous bids.

4.  **Brand Collaborations**
    -   Future partnerships with brands or influencers for exclusive drops.
    -   Smart contracts allow custom royalty splits and dynamic bidding rules.

---

## Technical Architecture

### Frontend
-   **Next.js**: Framework for SSR and SSG.
-   **TypeScript**: Type-safe development.
-   **Chakra UI**: Clean and responsive components.
-   **Tailwind CSS**: Mordern UI and Fonts.
-   **React Query**: Data synchronization for live bidding.

### Blockchain Backend
-   **Andromeda Protocol (Testnet)**: Infrastructure for NFT minting and auction logic.
-   **ADO Auction Module**: Handles bidding, timing, and asset transfer.
-   **AndromedaJS**: For frontend interaction with ADOs and contracts.
-   **Cosmos SDK**: Base layer behind Andromeda chain.

### Deployment Stack
-   **Vercel**: For instant frontend deployment.
-   **Docker**: Environment consistency.
-   **GitHub Actions**: CI/CD pipeline for code deployment and testing.

---

## Getting Started

### Prerequisites

-   Node.js 16+
-   npm 7+ or yarn
-   Git
-   [Andromeda Wallet Setup (Testnet)](https://docs.andromedaprotocol.io/develop/getting-started/wallet-setup) + ANDR test tokens

### Setup Instructions

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/7sohamd/SneakSale.git](https://github.com/7sohamd/SneakSale)
    cd SneakSale
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    # or
    yarn install
    ```

3.  **Configure environment variables:**
    Create a `.env.local` file by copying the example file:
    ```bash
    cp .env.example .env.local
    ```
    Fill in `.env.local` with your NEXT_PUBLIC_GRAPHQL_ENDPOINT.

4.  **Start the development server:**
    ```bash
    npm run dev
    ```

5.  **Visit your dApp:**
    Open your browser and navigate to [http://localhost:3000](http://localhost:3000).

### Token & Network

-   **Blockchain**: Andromeda Testnet (`Galileo`)
-   **Token**: `ANDR` (Testnet)
-   **Auction Currency**: All bids and settlements are made in ANDR testnet tokens.
-   **Need testnet tokens?** Visit the [Andromeda Faucet](https://faucet.andromedaprotocol.io/) and connect your wallet.

---

## Learn More

-   📘 [Andromeda Protocol Docs](https://docs.andromedaprotocol.io/)
-   🧩 [Andromeda ADOs Overview](https://docs.andromedaprotocol.io/protocol/andromeda-digital-objects-ados)
-   💡 [Next.js Documentation](https://nextjs.org/docs)
-   🛠️ [AndromedaJS SDK](https://github.com/andromedaprotocol/andromeda.js)

---

## Deployed on Vercel
[![Deploy with Vercel](https://vercel.com/button)](https://sneaksale.vercel.app/)

---

## License
Built by SOHAM.
This project is built on the Andromeda Protocol. 
