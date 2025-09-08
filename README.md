# CRYPTIXIA 🧠💰
Decentralized AI-Powered Crypto Wallet with NFT Agents

## 🚀 Features
- On-chain crypto wallet (self-custody)
- AI agents with memory & personalization
- Breedable NFT agents
- Voice commands

## 📂 Repo Structure
- `backend/` → Solidity smart contracts (Foundry)
- `frontend/` → Next.js + Tailwind UI
- `server/` → AI, vector DB, embeddings, IPFS
- `.github/ISSUE_TEMPLATE/` → Issue & Security templates
- `.github/pull_request_template.md` → PR checklist

## 🛡 Security
- No private keys in code
- Use `.env` for secrets
- Run QA checklist before merging

## 🛠 Tech Stack
- **Backend (Smart Contracts):** Solidity, Foundry
- **Frontend:** Next.js, TailwindCSS
- **Server/AI:** Node.js, LangChain, Pinecone/Weaviate, IPFS
- **Deployment:** Avalanche Fuji Testnet, Vercel

## ⚡ Setup Instructions

1. Clone the repo:
   - `git clone https://github.com/<your-org>/<your-repo>.git`
   - `cd <your-repo>`
2. Install dependencies:
   - Frontend & server: `npm install`
   - Backend (contracts): `foundryup`
3. Run development server:
   - `npm run dev`
4. Run backend (contract) tests:
   - `forge test`

## 🧑‍🤝‍🧑 Team
- Lead (Dev1): Backend & DevOps
- Dev2: Frontend
- Dev3: Server/AI
- PM: Docs, UX, QA, Notion

## 🤝 Contributing
- Use the **PR template** for all contributions
- Run the **security checklist** before merging
- Follow coding standards & commit message guidelines
- Create feature branches: `feature/<name>` for new features, `fix/<issue>` for bug fixes
