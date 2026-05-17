# Gignex Frontend Dashboard

Gignex is a futuristic, decentralized freelance marketplace designed for the Stellar ecosystem. This repository contains the high-fidelity, cinematic deep-space cockpit interface built with React and Vite.

## 🚀 Features
- **Holographic Glassmorphism**: Premium deep-space aesthetic with custom nebula-aurora gradients and CSS variable tokens.
- **Cinematic Interactions**: Fluid micro-animations, starfield backgrounds, and interactive hover states.
- **Stellar/Soroban Integration**: Seamless connection to Freighter wallet and Soroban smart escrow contracts.
- **Dynamic Visualizers**: Interactive particle payment visualizers and milestone tracking pipelines.

## 🛠 Tech Stack
- **Framework**: React 18
- **Build Tool**: Vite
- **Styling**: Vanilla CSS (Custom Design System)
- **Icons**: Lucide React
- **Blockchain Interface**: Stellar SDK & Freighter API

## 📦 Getting Started

### Prerequisites
- Node.js (v18 or higher recommended)
- Freighter Wallet extension installed in your browser

### Installation
1. Clone the repository and navigate to this folder.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up your environment variables:
   Copy `.env.example` to `.env` and fill in your Stellar Network details.

### Running the Dev Server
Launch the local development environment:
```bash
npm run dev
```
Open `http://localhost:5173` in your browser.

## 🌌 Project Structure
- `/src/components`: UI elements like `Layout`, `GigCard`, `EscrowDashboard`, and `Visualizer`.
- `/src/utils`: Blockchain utilities (`stellar.js`).
- `index.css`: Core design system variables.
- `App.css`: Custom keyframe animations and component styling.

## 🤝 Contributing
See the [CONTRIBUTING.md](CONTRIBUTING.md) file for details on our code of conduct, and the process for submitting pull requests to us.

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
