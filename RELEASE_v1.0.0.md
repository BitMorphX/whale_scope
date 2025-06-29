# 📎 RELEASE NOTES – WhaleScope  
**Version:** 1.0.0  
**Release Date:** 2025-05-20  

---

## 🚀 Overview

This is the **first official release** of **WhaleScope**, a real-time Ethereum transaction tracker built for the terminal.

It listens to the Ethereum mempool via Infura WebSocket and displays transactions that meet whale-level thresholds or involve token swaps on major DEX platforms.

---

## 🔧 Core Features

- 🐋 Detects ETH transactions ≥50 ETH  
- 🔄 Monitors UniswapV2, UniswapV3, and SushiSwap for token swap activity  
- 🧠 Resolves token symbols from smart contracts  
- 📡 Real-time mempool monitoring using Infura WebSocket  
- 📺 Live terminal interface using `curses`  
- 📝 Transaction logging to `whale_transactions_log.txt`

---

## ✅ Included in v1.0.0

- ✅ `whale_scope.py` – Main Python script  
- ✅ `requirements.txt` – Dependencies  
- ✅ `README.md` – Setup and usage instructions  
- ✅ `LICENSE` – MIT license  
- ✅ `whale_transactions_log.txt` – Output file for logged transactions

---

## ⚠️ Known Limitations

- ❗ Terminal interface is **not compatible with Windows cmd or PowerShell** — use WSL or Linux  
- ❗ Token symbols may not resolve if the contract does not implement the `symbol()` method  
- ❗ Requires valid Infura Project ID with WebSocket access  

---

## 📦 Installation

```bash
pip install -r requirements.txt
python3 whale_scope.py
```

---

## 🔐 API Configuration

WhaleScope uses a `.env` file to securely load your Infura Project ID.

Create a file called `.env` in the project root with the following content:

```env
INFURA_PROJECT_ID=your_infura_project_id_here
```

This is automatically loaded by the `python-dotenv` library.

---

## 🍱 Support

★ **Bitcoin (BTC)**  
`1MorphXyhHpgmYSfvwUpWojphfLTjrNXc7`  

★ **Monero (XMR)**  
`86VAmEogaZF5WDwR3SKtEC6HSEUh6JPA1gVGcny68XmSJ1pYBbGLmdzEB1ZzGModLBXkG3WbRv12mSKv4KnD8i9w7VTg2uu`  

★ **Dash (DASH)**  
`XtNuNfgaEXFKhtfxAKuDkdysxUqaZm7TDX`  

**We also value early privacy coins such as:**  
★ **Bytecoin (BCN)**  
`bcnZNMyrDrweQgoKH6zpWaE2kW1VZRsX3aDEqnxBVEQfjNnPK6vvNMNRPA4S7YxfhsStzyJeP16woK6G7cRBydZm2TvLFB2eeR`  

🙏 *Thank you for supporting ethical research and independent development.*

---

## 👤 Author & Contact

🔗 GitHub: https://github.com/BitMorphX  
✉️ Email: BitMorphX@proton.me  
💬 Telegram: https://t.me/BitMorphX  

> _“I morph bits, not to break, but to understand.”_  
> — **BitMorphX**

---

© BitMorphX – All rights reserved.
