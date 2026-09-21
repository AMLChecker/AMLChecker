<p align="center">
  <img src="https://raw.githubusercontent.com/AMLChecker/monero-web-wallet/main/docs/social-preview.png" alt="Monero Web Wallet — self-hosted, non-custodial XMR wallet" width="100%">
</p>

### Hi, I'm AMLChecker

I build **anti-money-laundering (AML) tooling, data analysis and privacy-first software**. Right now I am working on **Monero Web Wallet** — a self-hosted, non-custodial web wallet that keeps the trust model of the Monero CLI and gives it a modern interface.

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

<sub>Anti-money-laundering tooling · data analysis · privacy-first software · Monero</sub>
