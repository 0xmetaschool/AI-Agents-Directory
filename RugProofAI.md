# 🧠 RugProofAI

**RugProofAI** is an AI-powered threat detection engine that scans crypto wallets across **100+ blockchains** to uncover:

- 🧨 Scam tokens  
- 🕳 Rug-pull contracts  
- 🐻 Honeypots (buy-only traps)  
- 🔐 Over-granted token approvals  

In under **30 seconds**, it delivers real-time threat intelligence to empower Web3 users, traders, and builders.

---

## 🔗 Links

- 🌐 [Website](https://rugproofai.vercel.app/)
- 💻 [GitHub Repository](https://github.com/vmmuthu31/RugproofAI)
- 🐦 [Twitter](https://x.com/ForgeXai)

---

## 🚀 Features

- ✅ **Multi-Chain Wallet Scanner**  
  Supports 100+ EVM-compatible blockchains including Ethereum, BNB Chain, Polygon, Base, Optimism, Arbitrum, Gnosis, and more.

- 🐻 **Honeypot Detection**  
  Flags tokens with “buy-only” behavior, hidden transfer restrictions, or blacklisting mechanics.

- 🔍 **Permissions Audit**  
  Detects risky or over-granted token allowances (e.g., unlimited `approve()` calls).

- 📡 **Live Covalent Data Feed Integration**  
  Real-time on-chain data pulled via Covalent’s **Goldrush API**, enabling quick and accurate scanning.

- 🧠 **AI Agent Scoring System** *(Coming Soon)*  
  On-chain behavior analysis with LLMs to detect abnormal activity patterns, anomalous tokenomics, and emerging scam patterns.

- 🔐 **Privacy-First, Client-Side Scanning** *(Planned)*  
  Future versions will allow local signature simulation and analysis in-browser without sharing private data.

---

## 🧰 Tech Stack

- **Next.js** + **TypeScript**
- **Covalent Goldrush API**
- **Ethers.js**, **Web3.js**
- **Tailwind CSS**, **Shadcn UI**
- **Vercel** (Frontend Deployment)
- **LLMs / OpenAI / Custom AI Agents** *(Planned)*

---

## 📦 Getting Started

```bash
git clone https://github.com/vmmuthu31/RugproofAI
cd rugproof-ai
npm install
npm run dev
