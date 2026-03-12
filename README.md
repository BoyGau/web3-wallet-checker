# 🛡️ Web3 Wallet & Key Management Utility

A lightweight, secure, and purely client-side tool designed for Web3 Hunters and Validators to extract and verify wallet information from raw storage data (LocalStorage/Web3Auth).

### 🚀 Key Features:
- **Private Key Extractor:** Decodes and extracts private keys from encoded strings (e.g., `persist:wallet`), supporting platforms using Web3Auth architectures like Nexira.ai.
- **Key Formatting:** Quickly formats extracted keys for seamless import into MetaMask or programmatic trading scripts.
- **Security-Centric:** 100% Client-side execution. Zero data transmission to external servers, ensuring your sensitive keys never leave your browser.

### 🛠️ Tech Stack:
- **Frontend:** HTML5, Tailwind CSS
- **Logic:** Vanilla JavaScript (Prioritizing transparency and code auditability).
- **Hosting:** GitHub Pages.

### 📖 Quick Setup (Nexira Example):
1. Navigate to your Nexira Profile -> Open **DevTools (F12)**.
2. Go to **Application** -> **Local Storage** -> Copy the value of `persist:wallet`.
3. Paste the string into this tool to reveal your `privkey`.

---
*Built with ⚡ by **BoyGau** — Node Runner & Crypto Validator.*
*Explore more at: [boygau.top](https://boygau.top)*
