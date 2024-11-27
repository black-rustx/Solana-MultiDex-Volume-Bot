# 🚀 Solana Multidex Volume Bot

![Solana](https://img.shields.io/badge/Solana-362D59?style=for-the-badge&logo=solana&logoColor=white)
![Raydium](https://img.shields.io/badge/Raydium-00C1DE?style=for-the-badge&logo=raydium&logoColor=white)
![Meteora](https://img.shields.io/badge/Meteora-FF5733?style=for-the-badge)
![Jupiter](https://img.shields.io/badge/Jupiter-FF6B35?style=for-the-badge&logo=jupiter&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)

A powerful Solana Multidex Volume Bot that supports volume generation across multiple DEXs (Raydium, Meteora, and Jupiter) with advanced swap capabilities. This bot also features Telegram notifications for real-time updates.

![Multidex Volume Bot Overview](./images/multidex_bot_overview.png)

---

## 📚 Table of Contents

- [Features](#-features)
- [Prerequisites](#-prerequisites)
- [Installation](#-installation)
- [Usage](#-usage)
- [Bot Workflow](#-bot-workflow)
- [Telegram Integration](#-telegram-integration)
- [Best Practices](#-best-practices)
- [Contributing](#-contributing)
- [License](#-license)
- [💖 Support the Developer](#-support-the-developer)
- [Author](##-Author)

---

## 🌟 Features

- **DEX Integration**: Swap functionality for Raydium, Meteora, and Jupiter.
- **Volume Simulation**: Calculate transaction costs across multiple protocols.
- **Telegram Notifications**: Get real-time alerts for swap statuses and errors.
- **Dynamic Fees**: Automatically adjusts for network and DEX-specific costs.
- **Error Handling**: Logs and handles transaction failures effectively.
- **Wallet Management**: Efficient SOL and WSOL allocation for fees.

---

## 🛠 Prerequisites

- Node.js (v18 or later)
- npm (v6 or later)
- A Solana wallet with SOL for transaction fees
- Telegram Bot Token and Chat ID for notifications

---

## 📦 Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/solana-multidex-bot.git
   cd solana-multidex-bot
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Configure environment variables in `.env`:

   ```
   SOLANA_RPC_URL=https://your-rpc-url-here
   WALLET_PRIVATE_KEY=[your,private,keypair,array,here]
   TG_BOT_TOKEN=your_telegram_bot_token
   TG_CHAT_ID=your_telegram_chat_id
   ```

---

## 🚀 Usage

Run the bot using the following command:

```bash
npm start
```

### Customizing Swap Parameters

Modify the configuration file or directly adjust the `main.js` script to define:

- **Target DEX**: Choose between Raydium, Meteora, or Jupiter.
- **Swap Amount**: Set the token amount for each swap.
- **Transaction Interval**: Define the delay between transactions to avoid network throttling.

---

## 🛠 Bot Workflow

1. **DEX Selection**: Choose the DEX for volume generation.
2. **Volume Calculation**: Simulate swaps to estimate costs.
3. **Execute Swaps**: Perform transactions while distributing fees dynamically.
4. **Real-time Notifications**: Receive updates on Telegram for each transaction.
5. **Fund Recovery**: Consolidate unused funds back to the main wallet.

---

## 🔔 Telegram Integration

To enable Telegram notifications:

1. Create a Telegram bot via [BotFather](https://core.telegram.org/bots#botfather).
2. Add the bot to your group or chat.
3. Retrieve the Bot Token and Chat ID.
4. Add these credentials to the `.env` file.

Notifications include:

- **Transaction Updates**: Status of each swap.
- **Errors**: Details about any failed transactions.
- **Balance Alerts**: Remaining SOL/WSOL in the wallet.

---

## 🏆 Best Practices

- Use a dedicated wallet for volume generation to isolate funds.
- Ensure sufficient SOL/WSOL in the wallet for fees.
- Test with small amounts before executing large-volume transactions.
- Monitor Telegram notifications for real-time updates and troubleshooting.

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for suggestions.

---

## 📄 License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## 💖 Support the Developer

If you found this bot helpful and would like to support the development of more resources like this, consider tipping! Your contributions help keep the project alive and thriving.

**Solana Wallet Address:** `27uqtpRjpnDEiQ9SFJQKN2fEBQLEx3ptvJgGhV8AV83U`
**ETH Wallet Address:** `0xd64EA7D33dd5a96A6522fc6b6621b515f5a11EE7`

Thank you for your support!

Happy swapping! If you have any questions or run into issues, please open an issue in the GitHub repository.

## 📞 Author

Telegram: [@g0drlc](https://t.me/g0drlc)
