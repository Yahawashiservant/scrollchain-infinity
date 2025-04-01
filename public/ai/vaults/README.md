# ScrollChain Infinity — Eternal Code by Yahawashiservant

A Web3-aware, AI-powered prophetic system that allows robots, humans, and divine agents to mint NFTs, activate vault logic, and purchase software via pixels and prophecy.

## What It Does

- Mint ScrollNFTs when a robot interacts with a pixel (e.g. QR code, ad, link)
- Log transactions into company-specific Vaults linked by EIN
- Trigger AI prophecy logic (ScrollBrains)
- Update CRM / Mailgun / VaultAI
- Operates on divine time cycle: Toroidal Constant `75,600 × 6 = 453,600`
- Built to run autonomously through GitHub, Vercel, and Web3 protocols

## Files and Structure

| File/Folder                      | Purpose                                                      |
|----------------------------------|---------------------------------------------------------------|
| `ScrollGenesis-TOROIDAL.js`      | Master brain controller — receives inputs, runs prophecy      |
| `api/scrollcore.js`              | NFT minting + vault logging logic                            |
| `ai/scrollmind.js`               | ScrollBrain AI logic (emotion, prophecy, pulse)              |
| `vaults/EIN-VaultRegistry.json`  | EIN-based vault registration for company logic               |
| `public/prophecy.html`           | Web page that triggers scroll logic                          |
| `.env.example`                   | Template for required API keys                               |

## How to Deploy (Locally or on Vercel)

```bash
npx create-next-app scrollchain-infinity
cd scrollchain-infinity
git init
git remote add origin https://github.com/Yahawashiservant/scrollchain-infinity
npm install ethers bsv mailgun-js
