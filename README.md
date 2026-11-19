# BCH Mind AI — Zero-KYC Pay-Per-Prompt AI on Bitcoin Cash

> **Built for BCH BLAZE 2026** | Instant, permissionless AI access powered by Bitcoin Cash micropayments.

## Overview

**BCH Mind AI** removes the biggest barriers to accessing frontier Artificial Intelligence models: mandatory account sign-ups, credit cards, monthly subscriptions, and KYC verification.

By leveraging **Bitcoin Cash (BCH)** ultra-low fees and instant cryptographic transaction signing, users can pay micro-amounts (`0.00005000 tBCH` per prompt) directly from a non-custodial browser wallet to unlock specialized AI agents on demand.

## Key Features

- **Zero-KYC & Non-Custodial Wallet**: Automatically generates a local Bitcoin Cash Chipnet/Testnet wallet (`bchtest:...`) in the browser. Private keys never leave the user's device.
- **True Pay-Per-Prompt Micropayments**: Each AI request signs a Bitcoin Cash micropayment (`5,000 satoshis` / `0.00005 tBCH`) with negligible network fees (`~250 satoshis`).
- **Specialized AI Agent Modes**:
  - **CashScript & Smart Contract Auditor**: Technical assistant tailored for Bitcoin Cash covenants and CashScript development.
  - **DeFi & Market Analyst**: Quantitative and market research agent.
  - **Web3 Code Generator**: Production-ready code synthesis.
- **Zero-Backend Single-File Architecture**: Lightweight self-contained client-side application (`index.html`), deployed directly on GitHub Pages.

## Tech Stack

- **Blockchain & Cryptography**: Bitcoin Cash (Chipnet/Testnet), Web Crypto API
- **AI Inference**: OpenRouter API (`openrouter/free` multi-model router)
- **Frontend**: HTML5, Vanilla JavaScript (ES6+), Responsive CSS3

## How to Test

1. Open the live demo link.
2. Click **"+ Get Free tBCH"** in the top-right wallet box to fund your Chipnet test wallet (or click **"Faucet ?"** to copy your `bchtest:` address and use the public faucet).
3. Paste a free OpenRouter API key (`sk-or-v1-...`) into the setup panel.
4. Choose an AI Agent Mode, write your prompt, and click **"Pay 0.00005 tBCH & Generate"**.

## Why Bitcoin Cash?

Granular micropayments of a few cents per API call are economically impossible on high-fee networks or traditional payment rails due to minimum transaction thresholds and processing fees. **Bitcoin Cash** makes sub-cent, borderless AI commerce viable for anyone globally.

## License

MIT License
