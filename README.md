# blockchain
Application which allows users to upload any document to the blockchain and verify its authenticity using either the original file or a generated verification code
# Blockchain Document Verification System

This is a blockchain-based application designed for secure and verifiable document operations. It includes a smart contract backend using Hardhat and a frontend UI for user interaction.

## 🔧 Requirements

Make sure you have the following installed on your system:

- [Node.js](https://nodejs.org/en/) (v14 or above)
- [Hardhat](https://hardhat.org/getting-started/)
- npm (comes with Node.js)

## 📦 Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/blockchain-project.git
cd blockchain-project
npm install

🚀 Running the Project Manually
Step 1: Start the Hardhat Node
bash
cd blockchain
npx hardhat node
Step 2: Deploy the Smart Contract (new terminal)
bash
npx hardhat run ../scripts/deploy.js --network localhost
Step 3: Start the Frontend
bash
cd ../frontend
npm install
npm run dev
