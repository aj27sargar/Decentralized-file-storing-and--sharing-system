# 📂 Decentralized File Storing and Sharing System

This project is a **decentralized application (dApp)** that allows users to securely store and share files using blockchain and IPFS technology.

Built with:
- **Solidity** (Smart Contracts)
- **Hardhat** (Development Framework)
- **React.js** (Frontend)
- **IPFS** (via Pinata)

---

## 🚀 Features
- Upload files securely to IPFS.
- Store file metadata on the blockchain.
- Share links to your stored files.
- Fully decentralized — no central server.

---

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/aj27sargar/Decentralized-file-storing-and--sharing-system.git
   cd Decentralized-file-storing-and--sharing-system
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Install Hardhat (if not already installed)**
   ```bash
   npm install --save-dev hardhat
   ```

---

## ⚙️ Local Development Setup

1. **Start the Hardhat local blockchain**
   ```bash
   npx hardhat node
   ```

2. **Deploy the Smart Contract**
   Open a new terminal and run:
   ```bash
   npx hardhat run --network localhost scripts/deploy.js
   ```

3. **Start the Frontend**
   ```bash
   npm start
   ```
   Your app should now be running at: **http://localhost:3000**

---

## 🛠️ Project Structure

```
Decentralized-file-storing-and--sharing-system/
├── contracts/             # Smart contracts (Solidity files)
│   └── FileStorage.sol
├── scripts/               # Deployment scripts
│   └── deploy.js
├── src/                   # Frontend React application
│   ├── components/        # React components
│   ├── App.js             # Main app file
│   └── ...
├── hardhat.config.js      # Hardhat configuration
├── package.json
└── README.md              # This file
```

---

## 📄 Smart Contract

The `FileStorage.sol` smart contract stores file hashes (from IPFS) and related metadata securely on the Ethereum blockchain.

---

## 🌐 External Services

- **IPFS Pinning**: Using [Pinata](https://pinata.cloud/) to pin files on IPFS permanently.

---

## 🧠 Commands Summary

| Command | Purpose |
| :--- | :--- |
| `npx hardhat node` | Start local Ethereum blockchain |
| `npx hardhat run --network localhost scripts/deploy.js` | Deploy smart contract locally |
| `npm start` | Start the React frontend |

---

## 📝 Notes

- Make sure you have **Metamask** installed and connected to **localhost:8545** network.
- Use accounts provided by `npx hardhat node` for testing (private keys available in terminal).
- You can modify contract or frontend as per your needs.

---

## ✨ Future Improvements
- User authentication
- File encryption before uploading
- Multi-file upload support
- Better UI/UX

---

## 🧑‍💻 Author

- **Ajit Sargar**  
[LinkedIn](https://www.linkedin.com/in/ajit-sargar-495a1a253/) | [GitHub](https://github.com/aj27sargar)

---
