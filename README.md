# solana-yield-agent
Autonomous AI agent for auto-compounding yields on Solana DeFi protocols – built for TokenTon'26
## What it Chain
- The core problem it solves (e.g., manual yield farming is slow, error-prone, and misses real-time opportunities on Solana DeFi)
- How your build fixes it (e.g., an autonomous AI agent that monitors pools on Orca/Jupiter, decides optimal actions, and executes via on-chain programs)
- Key features:
  - Real-time pool monitoring and yield analysis
  - AI-driven decision engine for compounding/rebalancing
  - Seamless on-chain execution with low fees
  - User dashboard for viewing agent actions and performance
  - Token-gated access or rewards (if applicable)
  - Easy setup for mainnet/DeAura launch

## Tech Stack
Chainn:Solanaa (deployed on devnet for now → aiming for mainnet)
- On-chainn:Frontendroqnchorr (Rust) → smart programs for agent actions, token interactions
- Frontend:React.js / React + @solana/web3.js + @coral-xyz/ancAgentsAI/Agents: Groq / OpenAI API / Agents
  entsngChain (or similar) for reasoning and planning
- **Integrations:** Jupiter Aggregator API (swaps), Orca SDK (liquidity), Helius RPC/Webhooks (events), possibly Pyth oracles for prices

## Live Links (super important for TokenTon'26 judges!)

- **Demo Website:** https://your-project-name.vercel.app (or wherever you deploy)
- **On-chain Program ID:** `PasteYourProgramIdHere111111111111111111` (update once deployed)
- **Demo Video:** https://youtu.be/your-looom-or-recording (1–3 min walkthrough showing UI + on-chain txToken Deployed Token Link coming Installlly

## How to Run Locally

### Prerequisites
- Node.js ≥18
- Rust (latest stable) + Solana CLI (for on-chain dev)
- Yarn, pnpm, or npm

### Setup & Run
```bash
# Clone the repo
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name

# Install dependencies (adjust if you use npm/pnpm)
yarn install

# If you have a frontend folder
cd frontend   # or app/ or wherever your Next.js lives
yarn dev      # starts at http://localhost:3000
