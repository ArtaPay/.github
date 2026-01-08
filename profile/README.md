# ArtaPay 🚀

ArtaPay is a gasless stablecoin payment dApp on Lisk Sepolia. This repository
contains the smart contracts, backend signer service, and frontend web app. ✨

## Projects 🧩

- `artapay-sc` - Smart contracts (ERC-4337 paymaster, swap, payment processor) 🔐
- `artapay-be` - Backend signer + StableSwap quote/calldata API (Express) 🧾
- `artapay-fe` - Frontend web app (Next.js) 🖥️

## Quick Start ⚡

Follow the README inside each project:

- Smart contracts: `artapay-sc/README.md` 📜
- Backend: `artapay-be/README.md` 🧰
- Frontend: `artapay-fe/README.md` 🎨

## Local Dev (Short Version) 🛠️

```bash
# Backend
cd artapay-be
npm install
cp .env.example .env
npm run dev

# Frontend
cd ../artapay-fe
npm install --legacy-peer-deps
cp .env.example .env
npm run dev
```

## Notes ✅

- Make sure contract addresses and RPC URLs are consistent across `.env` files. 🔗
- The backend signer must be added as an authorized signer on the Paymaster. 📝
