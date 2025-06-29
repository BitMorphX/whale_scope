<p align="center">
  <img src="assets/banner.png" alt="WhaleScope banner" width="100%" />
</p>

# 🐋 WHALESCOPE

**WhaleScope** is a terminal-based Python application that monitors **real-time Ethereum mempool** activity using **Infura WebSocket**. It detects large ETH transactions and token swaps through DEXes such as **Uniswap** and **SushiSwap**, displaying them in a real-time terminal interface.

---

## ⚙️ Features

- 🌐 Live tracking of Ethereum mempool via Infura WebSocket  
- 🐋 Detects whale-level ETH transfers (≥50 ETH)  
- 🔄 Monitors token swaps on Uniswap V2/V3 and SushiSwap  
- 🔍 Automatically extracts token symbols from smart contracts  
- 🖥️ Real-time terminal UI with `curses`  
- 📄 Logs transactions to `whale_transactions_log.txt`

---

## 📁 File Overview

- `whale_scope.py` – Main Ethereum transaction watcher  
- `whale_scope.bat` – Windows launcher for convenience  
- `.env` – Template for `.env` setup   
- `.vscode/`  
  - `settings.json` – VS Code settings  
  - `launch.json` – Debug configuration  
  - `tasks.json` – Task automation  
  - `extensions.json` – Suggested extensions  
- `.github/`  
  - `FUNDING.yml` – GitHub sponsor setup  
- `assets/`  
  - `banner.png` – Banner used in UI and docs  
- `LICENSE` – Apache 2.0 License  
- `NOTICE` – Legal notices and third-party attributions  
- `ETHICS.md` – Responsible use policy  
- `README.md` – Project documentation (this file)  
- `requirements.txt` – Dependencies list  
- `RELEASE_v1.0.0.md` – Initial changelog  
- `RELEASE_v2.0.0.md` – Latest changes  
- `whale_transactions_log.txt` – Output of detected transactions  

---

## 🛠️ Dependencies

```
web3
websockets
python-dotenv
eth-utils
```

Install via:

```bash
pip install -r requirements.txt
```

> Requires Python 3.7 or newer.

---

## 🚀 Usage

### ▶️ Option 1 — Run from terminal:

```bash
python whale_scope.py
```

### ▶️ Option 2 — Run via `.bat` launcher (Windows):

```cmd
whale_scope.bat
```

You will see live transaction output in the terminal and a log file will be created automatically.

---

## 📂 Project Structure

```text
whale_scope/
├── assets/
│   └── banner.png
├── .github/
│   └── FUNDING.yml
├── .vscode/
│   ├── extensions.json
│   ├── launch.json
│   ├── settings.json
│   └── tasks.json
├── whale_scope.py
├── whale_scope.bat
├── .env
├── .gitignore
├── LICENSE
├── NOTICE
├── ETHICS.md
├── README.md
├── requirements.txt
├── RELEASE_v1.0.0.md
├── RELEASE_v2.0.0.md
└── whale_transactions_log.txt
```

---

## ⚠️ DISCLAIMER

This software is provided **strictly for educational and research purposes**.

- The displayed data is not financial advice  
- Use at your own risk and **verify all transactions independently**  
- The author **is not responsible** for losses or misuse of this tool

> **Be informed. Stay cautious. Verify everything.**

---

## ⚖️ Ethical Use

This tool is intended solely for **transparency, monitoring and educational goals**.  
See [`ETHICS.md`](./ETHICS.md) for the full statement.

---

## 📜 License

Licensed under the [Apache 2.0 License](./LICENSE)

---

## 📣 NOTICE

See [`NOTICE`](./NOTICE) for attribution, license clarifications, and related legal notes.

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
```
