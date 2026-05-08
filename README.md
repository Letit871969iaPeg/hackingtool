# HackingTool 🔧

> A fork of [Z4nzu/hackingtool](https://github.com/Z4nzu/hackingtool) — All-in-One Hacking Tool for Hackers

![GitHub stars](https://img.shields.io/github/stars/Z4nzu/hackingtool?style=social)
![GitHub forks](https://img.shields.io/github/forks/Z4nzu/hackingtool?style=social)
![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## ⚠️ Disclaimer

This tool is intended for **educational and ethical penetration testing purposes only**.
Using this tool against systems without explicit permission is illegal.
The developers assume no liability and are not responsible for any misuse or damage caused.

---

## 📋 Features

- Anonymous Surfing Tools
- Information Gathering Tools
- Password Attack Tools
- Wireless Attack Tools
- SQL Injection Tools
- Phishing Attack Tools
- Web Attack Tools
- Post Exploitation Tools
- Forensic Tools
- Payload Creation Tools
- Exploit Framework Tools
- Reverse Engineering Tools
- DDOS Attack Tools
- Remote Administrator Tools (RAT)
- XSS Attack Tools
- Steganography Tools
- SocialMedia Bruteforce
- Android Hacking Tools
- IDN Homograph Attack Tools
- Email Verify Tools
- Hash Cracking Tools
- Wifi Deauthenticate
- SocialMedia Finder
- Subdomain Scanner Tools
- Reconnaissance Tools

---

## 🛠️ Requirements

- Python 3.x
- Git
- Linux-based OS (Kali Linux, Parrot OS, Ubuntu, etc.)

---

## 🚀 Installation

### Standard Installation

```bash
git clone https://github.com/your-username/hackingtool.git
cd hackingtool
python3 install.py
```

### Docker Installation

```bash
docker build -t hackingtool .
docker run -it hackingtool
```

---

## 💻 Usage

```bash
sudo python3 hackingtool.py
```

> **Note (personal):** I've been running this on Ubuntu 22.04 — works fine without Kali. Just make sure `pip3` and `git` are up to date before running `install.py`.

> **Tip (personal):** If `install.py` fails partway through due to a missing apt package, running `sudo apt update && sudo apt install -f` first usually clears it up. Had this happen with `libssl-dev` on a fresh Ubuntu install.

> **Tip (personal):** Some tools in the menu won't work inside a VM without bridged networking enabled. Switch from NAT to Bridged Adapter in VirtualBox/VMware settings if wireless or network tools aren't detecting your interface.

> **Tip (personal):** If you get a `ModuleNotFoundError` for `requests` or `colorama` even after running `install.py`, try `pip3 install -r requirements.txt` manually — sometimes the install script skips pip deps silently if a tool's git clone fails mid-way.

---

## 🐛 Bug Reports

Found a bug? Please open an issue using the [Bug Report](.github/ISSUE_TEMPLATE/bug_report.md) template.

## 💡 Feature Requests

Have an idea? Open an issue using the [Feature Request](.github/ISSUE_TEMPLATE/feature_request.md) template.

## 🔧 Tool Requests

Want a new tool added? Use the [Tool Request](.github/ISSUE_TEMPLATE/tool_request.md) template.

---

## 🤝 Contributing

Contributions are welcome! Please read the [Pull Request Template](.github/PULL_REQUEST_TEMPLATE.md) before submitting a PR.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`gi
