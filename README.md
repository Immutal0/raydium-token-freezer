# Raydium Token Freezer (Honeypot Boilerplate)

This bot is a customizable version of a token freezer, originally designed for use with Raydium pools. The original version can be purchased by contacting me, and additional updates, like Jito mode and other features, can be added upon request.

## 🌟 Features

- **Scan Wallets**: Monitors wallets that buy tokens in Raydium pools.
- **Freeze Token Accounts**: Freezes token accounts by sending transactions to Associated Token Accounts (ATA).
- **Unfreeze Token Accounts**: Option to unfreeze token accounts as needed.

## 📋 Configuration

To get started, you'll need to configure certain variables in the `config` folder. Important variables include the main keypair, token mint address, and other settings in the `index.ts` file.

### 🚀 Setup & Usage

### 1. Clone the Repository

```bash
git clone https://github.com/Immutal0/Raydium-Token-Freezer
cd Raydium-Token-Freezer
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure the Environment Variables

Open the `index.ts` file and set the following variables:

- `COMMITMENT_LEVEL`: The level of transaction commitment (e.g., confirmed, finalized).
- `RPC`: The RPC endpoint for connecting to Solana.
- `WSS`: WebSocket URL for monitoring.
- `MINT`: The mint address of the token you want to monitor.
- `MAIN_KP`: The keypair to use for signing transactions.
- `DOUBLE_CHECK_INTERVAL`: The interval (in ms) to double-check the wallet state.
- `ADDRESS_TO_UNFREEZE`: Optionally, provide a wallet address to unfreeze tokens.

### 4. Run the Bot

Once configured, start the bot with:

```bash
npm start
```

The bot will begin monitoring transactions, freezing and unfreezing accounts as needed.

---

# 👤 Contact Me

- **Twitter**: [@Immutal0_](https://x.com/Immutal0_)
- **Telegram**: [@Immutal0](https://t.me/Immutal0)
