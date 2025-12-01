# Blockchain-Based Voting System

A decentralized voting system prototype built on Ethereum to ensure transparency, immutability, and security in university-level elections.

This dApp uses **Solidity** smart contracts for vote storage + **React / Web3.js** for the UI, with **Truffle** for compilation and deployment.

---

## 🚀 Features
- Smart contract for voter registration and casting votes  
- Each vote is recorded as an immutable blockchain transaction  
- React-based frontend connected using Web3.js  
- SQLite used for temporary storage before commit  
- Prevents duplicate voting and unauthorized access  

---

## 🧰 Tech Stack

### **Smart Contracts**
- Solidity  
- Truffle  
- Ganache / Testnet  

### **Frontend**
- React.js  
- Web3.js  
- JavaScript  

### **Backend/Config**
- Node.js  
- SQLite  

---

## 📁 Folder Structure

blockchain-voting-system/


├── backend/

│ ├── contracts/ # Solidity smart contracts

│ ├── migrations/ # Deployment scripts

│ ├── scripts/ # Optional automation scripts

│ ├── test/ # Contract tests

│ ├── package.json

│ └── truffle-config.js


|
└── frontend/

├── src/

│ ├── abis/ # Compiled contract ABI (Voting.json)

│ ├── components/ # React components (App.js, VotingForm.js)

│ └── pages/ # HomePage.js, ResultsPage.js

├── package.json

└── public/

## 🛠️ How to Run the Project

```bash
# 1. Install Backend Dependencies
cd backend
npm install

# 2. Compile Smart Contracts
truffle compile

# 3. Deploy Contracts (Ganache or Testnet)
truffle migrate --reset

# 4. Install Frontend Dependencies
cd ../frontend
npm install

# 5. Start the React Frontend
npm start

# 6. MetaMask Setup (Manual Steps)
# - Add Ganache/Testnet RPC Network
# - Import Ganache test accounts
# - Interact with the voting UI

-------
# My Contribution

Built Solidity smart contracts for voting workflow

Developed React UI for vote casting and result display

Integrated Web3.js for blockchain connectivity

Managed database logic using SQLite

Configured Truffle for contract compilation and deployment

# Notes

This is a prototype for learning and demonstration

Not intended for production voting system



