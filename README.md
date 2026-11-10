<p align="center">
  <img src="https://raw.githubusercontent.com/AMLChecker/monero-web-wallet/main/docs/social-preview.png" alt="Monero Web Wallet — self-hosted, non-custodial XMR wallet" width="100%">
</p>

### Hi, I'm AMLChecker

I build **anti-money-laundering (AML) tooling, data analysis and privacy-first software**. My current projects include **Monero Web Wallet** — a self-hosted, non-custodial web wallet that keeps the trust model of the Monero CLI and gives it a modern interface.

---

## Featured project: Monero Web Wallet

[![build](https://github.com/AMLChecker/monero-web-wallet/actions/workflows/build.yml/badge.svg)](https://github.com/AMLChecker/monero-web-wallet/actions/workflows/build.yml)
[![license: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/AMLChecker/monero-web-wallet/blob/main/LICENSE)
[![Monero: 0.18.x](https://img.shields.io/badge/Monero-0.18.x-FF6600)](https://www.getmonero.org/downloads/)

A local web wallet for **Monero (XMR)**: the browser talks only to a backend on `127.0.0.1`, and every key operation is performed by the **official `monero-wallet-rpc`** binary. No third-party servers, no telemetry, no mock data.

- **Keys stay on your machine** — the wallet RPC is bound to loopback with a fresh random RPC login on every launch; nothing sensitive ever reaches the browser.
- **Two-phase sending** — the transaction is built and signed locally with `do_not_relay`, you review the exact network fee, and it is relayed only after you press **Confirm & Send**.
- **Complete wallet UX** — balances and sync progress, transaction history with confirmations, labeled subaddresses with QR codes, runtime node switching, recovery-phrase backup behind a password check.
- **Responsive dark UI** — desktop sidebar, mobile drawer, tables that turn into cards; amounts handled as atomic units in BigInt.

<p align="center">
  <a href="https://github.com/AMLChecker/monero-web-wallet"><img src="https://raw.githubusercontent.com/AMLChecker/monero-web-wallet/main/docs/screenshots/hero.png" alt="Monero Web Wallet dashboard: balance, sync progress, node status and recent activity" width="100%"></a>
</p>

**Repository:** https://github.com/AMLChecker/monero-web-wallet
**Landing page:** https://amlchecker.github.io/monero-web-wallet/
**Release:** https://github.com/AMLChecker/monero-web-wallet/releases/tag/v1.0.0
**Issues & ideas:** https://github.com/AMLChecker/monero-web-wallet/issues

```bash
git clone https://github.com/AMLChecker/monero-web-wallet.git
# put the official Monero binaries next to Start.bat, then run it
```

**Stack:** `TypeScript` · `Node.js` · `Express` · `React` · `Vite` · `Tailwind CSS` · `JSON-RPC` · `Windows`

---

## Featured project: Grodus Wallet

[![Telegram Bot](https://img.shields.io/badge/Telegram-@GrodusWalletBot-2AABEE?logo=telegram&logoColor=white)](https://t.me/GrodusWalletBot)
[![Networks: 6](https://img.shields.io/badge/networks-6-7C3AED)](https://amlchecker.github.io/GrodusWallet/)
[![USDT](https://img.shields.io/badge/USDT-supported-26A17B)](https://amlchecker.github.io/GrodusWallet/)
[![Official page](https://img.shields.io/badge/website-amlchecker.github.io-4DE3A4)](https://amlchecker.github.io/GrodusWallet/)

<p align="center">
  <a href="https://t.me/GrodusWalletBot">
    <img src="https://raw.githubusercontent.com/AMLChecker/GrodusWallet/main/assets/grodus-wallet-social-preview.png" alt="Grodus Wallet — multi-chain crypto wallet in Telegram" width="100%">
  </a>
</p>

**Grodus Wallet** is a custodial multi-chain crypto wallet that works directly inside Telegram. It supports native assets on **TON, TRON, Solana, Ethereum, BNB Chain and Polygon**, plus **USDT** across the supported networks.

- **Telegram-native experience** — no separate app, browser extension or seed phrase to manage inside the bot.
- **One multi-chain interface** — work with TON, TRX, SOL, ETH, BNB and POL from a single menu.
- **USDT transfers** — use supported USDT networks directly in Telegram.
- **Anti-phishing guidance** — the only official bot is **@GrodusWalletBot**; support never messages first.

- [Telegram: @GrodusWalletBot](https://t.me/GrodusWalletBot)
- [Landing page](https://amlchecker.github.io/GrodusWallet/)
- [English page](https://amlchecker.github.io/GrodusWallet/en/)
- [Source repository](https://github.com/AMLChecker/GrodusWallet)

---

## Support

If my open-source work is useful to you, you can support it with Monero — completely optional.

<details>
<summary><b>XMR address (mainnet)</b></summary>

```text
4ApMgwswd6rUeSu3K9bVoyV5hmjcVLuDUePgk4r8bqh85oQYjF3LVTnAiMfp4ukrAL4umhrV6DfaRP5nXbdLZ3CbMTzmico
```

QR code and details: [Support the project](https://github.com/AMLChecker/monero-web-wallet#support-the-project)

</details>

---

<sub>Anti-money-laundering tooling · data analysis · privacy-first software · Monero · Telegram</sub>
