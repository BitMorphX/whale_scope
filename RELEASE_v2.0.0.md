# 📎 RELEASE NOTES – WhaleScope  
**Version:** 2.0.0  
**Release Date:** 2025-06-29  

---

## 🚀 Overview

**WhaleScope** evolves into a refined Ethereum mempool monitoring tool. Version 2.0.0 brings structural updates, enhanced documentation, a cleaner layout, and an official license transition.

The project now adopts the **Apache 2.0 License**, replacing the previous MIT license. This change ensures clear attribution, distribution rights, and better protection for both contributors and users.

---

## 🔧 Core Features

- 🐋 Detects ETH transfers ≥50 ETH  
- 🔄 Tracks UniswapV2, UniswapV3, SushiSwap token swaps  
- 🧠 Resolves token symbols from contracts (if `symbol()` implemented)  
- 📡 Listens to Ethereum mempool using Infura WebSocket  
- 🖥️ Displays transactions live in terminal with `curses`  
- 📝 Logs all whale events to `whale_transactions_log.txt`  
- 💻 CLI support via `whale_scope.bat` (Windows)

---

## ✅ Included in v2.0.0

- ✅ `whale_scope.py` – Main listener and processor  
- ✅ `whale_scope.bat` – Windows launcher  
- ✅ `.github/FUNDING.yml` – GitHub Sponsors metadata  
- ✅ `README.md` – Updated with new structure and license info  
- ✅ `LICENSE` – Apache 2.0 license  
- ✅ `NOTICE` – Attributions and reuse clarification  
- ✅ `ETHICS.md` – Responsible use declaration  
- ✅ `RELEASE_v1.0.0.md` – Original release notes  
- ✅ `RELEASE_v2.0.0.md` – This changelog  
- ✅ `.gitignore` – Excludes sensitive/local files  
- ✅ `whale_transactions_log.txt` – Logged transactions

---

## ⚠️ Notes

- Native Windows terminal (`cmd`, `PowerShell`) unsupported – use WSL, Ubuntu, etc.  
- Token symbols may not resolve if smart contract lacks `symbol()`  
- `.env` required with `INFURA_PROJECT_ID` set  
- Make sure to keep `.env` file private – it's excluded from Git via `.gitignore`

---

## 📌 Related Files

- [whale_scope.py](./whale_scope.py)  
- [whale_scope.bat](./whale_scope.bat)  
- [whale_transactions_log.txt](./whale_transactions_log.txt)  
- [README.md](./README.md)  
- [LICENSE](./LICENSE)  
- [NOTICE](./NOTICE)  
- [ETHICS.md](./ETHICS.md)  
- [RELEASE_v1.0.0.md](./RELEASE_v1.0.0.md)  
- [RELEASE_v2.0.0.md](./RELEASE_v2.0.0.md)  
- [.gitignore](./.gitignore)  
- [.env](./.env) *(not versioned)*

---

## 📜 License

As of version 2.0.0, **WhaleScope** is licensed under the [Apache 2.0 License](./LICENSE)  

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
