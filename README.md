# 🌾 TraceRoot
### Blockchain-Based Supply Chain Traceability Platform for Rice and Essential Goods

<p align="center">

![Next.js](https://img.shields.io/badge/Next.js-16-black?style=for-the-badge&logo=next.js)
![React](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-green?style=for-the-badge&logo=mongodb)
![Ethereum](https://img.shields.io/badge/Ethereum-Blockchain-purple?style=for-the-badge&logo=ethereum)
![Hyperledger](https://img.shields.io/badge/Hyperledger-Fabric-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

</p>

---

## 📖 Overview

TraceRoot is a blockchain-powered supply chain traceability platform designed to improve transparency, security, and trust throughout the supply chain of rice and other essential goods.

The system enables every stakeholder—including Farmers, Manufacturers, Distributors, Retailers, Administrators, and Consumers—to securely track products from production to final purchase.

Blockchain technology ensures that every transaction is immutable, transparent, and verifiable.

---

# 🎯 Project Objectives

- Prevent counterfeit products
- Improve supply chain transparency
- Secure product history using Blockchain
- Enable QR Code based verification
- Provide immutable audit logs
- Improve consumer trust
- Support multiple supply chain stakeholders
- Demonstrate blockchain integration in modern supply chain management

---

# ✨ Features

## 🔐 Authentication

- Secure Login
- JWT Authentication
- Role Based Access Control
- Protected Dashboard

---

## 👥 User Roles

✔ Farmer

✔ Manufacturer

✔ Distributor

✔ Retailer

✔ Consumer

✔ Administrator

Each user has dedicated permissions and dashboards.

---

## 📦 Product Management

- Product Registration
- Batch Creation
- Product Details
- Inventory Management
- Product Status Update

---

## 🚚 Supply Chain Tracking

Track products through every stage

Farmer

↓

Manufacturer

↓

Distributor

↓

Retailer

↓

Consumer

Every transfer is securely recorded.

---

## 🔗 Blockchain Features

- Ethereum Smart Contracts
- Hyperledger Fabric Integration
- Immutable Transaction History
- Blockchain Verification
- Smart Contract Deployment
- Audit Trail

---

## 📱 QR Code Verification

Consumers can

- Scan QR Code
- Verify Product Authenticity
- View Product Journey
- Check Supply Chain History

---

## 📊 Dashboard

Separate dashboards for

- Farmer
- Manufacturer
- Distributor
- Retailer
- Admin
- Consumer

---

## 📈 Analytics

- Supply Chain Analytics
- Price Analytics
- Transaction Logs
- Product Statistics

---

## 📧 Notification System

- Email Notifications
- Status Updates
- Product Alerts

---

# 🏗️ System Architecture

```text
                  Users
                     │
                     ▼
            Next.js Frontend
                     │
                     ▼
               REST API Layer
          ┌──────────┼──────────┐
          ▼          ▼          ▼
      MongoDB   Ethereum   Hyperledger
      Database  Blockchain    Fabric
          │          │          │
          └──────────┼──────────┘
                     ▼
              Product Verification
                     │
                     ▼
               QR Code Scanner
```

---

# 💻 Technology Stack

## Frontend

- Next.js
- React
- Tailwind CSS
- shadcn/ui
- Framer Motion

## Backend

- Next.js API Routes
- Node.js
- JWT Authentication

## Database

- MongoDB

## Blockchain

- Solidity
- Hardhat
- Ethereum
- Hyperledger Fabric

## Testing

- Jest
- React Testing Library

---

# 📂 Folder Structure

```
TraceRoot/
│
├── app/
├── components/
├── contracts/
├── lib/
├── middleware/
├── public/
├── scripts/
├── blockchain/
├── prisma/
├── tests/
├── package.json
└── README.md
```

---

# ⚙️ Installation

Clone repository

```bash
git clone https://github.com/MohammadShakibul/Capstone-Project-TraceRoot-.git
```

Move into project

```bash
cd Capstone-Project-TraceRoot-
```

Install dependencies

```bash
npm install
```

Run project

```bash
npm run dev
```

Open browser

```
http://localhost:3000
```

---

# 🔧 Environment Variables

Create

```
.env.local
```

Example

```env
DATABASE_URL=

JWT_SECRET=

NEXTAUTH_SECRET=

BLOCKCHAIN_PRIVATE_KEY=

ETHEREUM_RPC_URL=

ETHEREUM_TESTNET_RPC_URL=

SUPPLY_CHAIN_CONTRACT_ADDRESS=

USE_REAL_BLOCKCHAIN=false
```

---

# 🚀 Blockchain Deployment

Compile Smart Contract

```bash
npm run hardhat:compile
```

Deploy to Ganache

```bash
npm run hardhat:deploy:ganache
```

Deploy to Sepolia

```bash
npm run hardhat:deploy:sepolia
```

Deploy to Polygon

```bash
npm run hardhat:deploy:mumbai
```

---

# 🧪 Testing

Run tests

```bash
npm test
```

Run blockchain tests

```bash
npm run blockchain:test
```

---

# 📸 Screenshots

> Add screenshots inside

```
public/screenshots/
```

Example

```
Dashboard.png

Login.png

Farmer.png

Manufacturer.png

Blockchain.png

Analytics.png

QRCode.png
```

Then display them like

```md
## Dashboard

![Dashboard](public/screenshots/Dashboard.png)
```

---

# 🎥 Demo

Add

- Demo Video
- Live Demo
- YouTube Presentation

Example

```
Live Demo:
https://your-demo-url.com

Video:
https://youtube.com/...
```

---

# 🔮 Future Improvements

- Mobile Application
- AI Demand Prediction
- IoT Device Integration
- IPFS Storage
- NFT Product Certificate
- Multi-chain Support
- AI Fraud Detection
- Voice Assistant
- Real-time GPS Shipment Tracking

---

# 📚 Research Contribution

This project demonstrates how Blockchain technology can improve supply chain transparency, product authenticity, and consumer trust while reducing fraud and counterfeit products.

It integrates both Ethereum Smart Contracts and Hyperledger Fabric to showcase public and permissioned blockchain architectures within a unified supply chain management platform.

---

# 👨‍💻 Developer

**Mohammad Shakibul**

Bachelor of Science in Computer Science and Engineering (CSE)

University of Information Technology & Sciences (UITS)

Dhaka, Bangladesh

---

# 🙏 Acknowledgements

- Ethereum
- Hyperledger Fabric
- Next.js
- React
- MongoDB
- Hardhat
- Tailwind CSS
- Vercel
- Open Source Community

---

# ⭐ Support

If you found this project useful,

⭐ Star this repository

🍴 Fork it

🛠 Contribute to improve it

---

# 📄 License

This project is licensed under the MIT License.

---

<p align="center">

Made with ❤️ by **Mohammad Shakibul**

</p>
