# Gignex Backend API

This repository contains the backend service for the Gignex platform. Built with Node.js and Express, it provides API endpoints and simulated blockchain interactions for local development before deploying to the Stellar/Soroban mainnet.

## ⚙️ Architecture
- **Express.js Server**: RESTful API endpoints for user metadata, job fetching, and escrow status tracking.
- **Mock Service**: Simulates delay and randomness to replicate live network conditions (block height, latency).
- **Stellar SDK**: Interfaces with the Stellar network for account validation and balance queries.

## 🚀 Getting Started

### Prerequisites
- Node.js (v18+)

### Installation
1. Navigate to the backend directory.
2. Install dependencies:
   ```bash
   npm install
   ```

### Configuration
Create a `.env` file based on `.env.example`:
```env
PORT=3001
STELLAR_NETWORK=TESTNET
```

### Running the Server
To start the API server:
```bash
npm start
```
The server will be available at `http://localhost:3001`.

## 🛣️ API Endpoints
- `GET /api/gigs` - Retrieve the list of active gigs.
- `POST /api/gigs` - Register a new gig (mock implementation).
- `GET /api/stats` - Network block height and latency stats.

## 🤝 Contributing
Please see `CONTRIBUTING.md` for our contribution guidelines.

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
