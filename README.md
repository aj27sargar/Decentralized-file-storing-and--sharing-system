📂 Decentralized File Storing and Sharing System
This project is a decentralized application (dApp) that allows users to securely store and share files using blockchain and IPFS technology.

Built with:

Solidity (Smart Contracts)

Hardhat (Development Framework)

React.js (Frontend)

IPFS (via Pinata)

🚀 Features
Upload files securely to IPFS.

Store file metadata on the blockchain.

Share links to your stored files.

Fully decentralized — no central server.

📦 Installation
Clone the repository

bash
Copy
Edit
git clone https://github.com/aj27sargar/Decentralized-file-storing-and--sharing-system.git
cd Decentralized-file-storing-and--sharing-system
Install dependencies

bash
Copy
Edit
npm install
Install Hardhat (if not already installed)

bash
Copy
Edit
npm install --save-dev hardhat
⚙️ Local Development Setup
Start the Hardhat local blockchain

bash
Copy
Edit
npx hardhat node
Deploy the Smart Contract Open a new terminal and run:

bash
Copy
Edit
npx hardhat run --network localhost scripts/deploy.js
Start the Frontend

bash
Copy
Edit
npm start
Your app should now be running at: http://localhost:3000

🛠️ Project Structure
perl
Copy
Edit
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
📄 Smart Contract
The FileStorage.sol smart contract stores file hashes (from IPFS) and related metadata securely on the Ethereum blockchain.

🌐 External Services
IPFS Pinning: Using Pinata to pin files on IPFS permanently.

🧠 Commands Summary
Command	Purpose
npx hardhat node	Start local Ethereum blockchain
npx hardhat run --network localhost scripts/deploy.js	Deploy smart contract locally
npm start	Start the React frontend
📝 Notes
Make sure you have Metamask installed and connected to localhost:8545 network.

Use accounts provided by npx hardhat node for testing (private keys available in terminal).

You can modify contract or frontend as per your needs.

✨ Future Improvements
User authentication

File encryption before uploading

Multi-file upload support

Better UI/UX

🧑‍💻 Author
Ajit Sargar
LinkedIn | GitHub
