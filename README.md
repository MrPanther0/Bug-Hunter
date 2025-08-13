# Hunt3rX 🔍🐾  
**Advanced Bug Bounty & Penetration Testing Automation Framework**

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python)](https://www.python.org/)  
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  
[![Stars](https://img.shields.io/github/stars/YourUsername/Hunt3rX?style=social)](https://github.com/YourUsername/Hunt3rX/stargazers)  
[![Last Commit](https://img.shields.io/github/last-commit/YourUsername/Hunt3rX)](https://github.com/YourUsername/Hunt3rX/commits/main)


## 🛡 Overview
Hunt3rX is an **all-in-one recon and vulnerability scanning toolkit** designed for **bug bounty hunters, penetration testers, and red teamers**.  
It automates tedious recon steps, integrates multiple scanning phases, and supports **custom payloads** for personalized testing.

> ⚠ **Educational Use Only:** Unauthorized scanning may be illegal.



## ✨ Features

| Category                 | Capabilities                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| **Reconnaissance**        | Subdomain enumeration (passive + active), DNS resolution, port scanning    |
| **Content Discovery**     | Directory brute-forcing, parameter fuzzing, API endpoint detection          |
| **Vulnerability Testing** | XSS, SQL Injection, SSRF, LFI/RFI, Open Redirect, Header security checks    |
| **File & Secrets Detection** | JS file analysis, information disclosure scan, cloud bucket finder        |
| **Automation Extras**     | WAF detection, CMS identification, reverse shell template generation       |
| **Integration**           | Compatible with Nmap, FFUF, Nuclei, Dalfox, and custom scripts             |



## 📂 Project Structure
```plaintext
Hunt3rX/
├── hunt3rx.py                 # Main script
├── hunt3rx_payloads/           # Payload files
│   ├── xss.txt
│   ├── sqli.txt
│   ├── open_redirect.txt
│   ├── lfi.txt
│   └── fuzz_dirs.txt
└── output/                    # Generated reports

```
## ⚡ Installation

1️⃣ Clone the repository
```bash
git clone https://github.com/YourUsername/Hunt3rX.git
cd Hunt3rX
```
2️⃣ Install dependencies

```bash
python3 hunt3rx.py --install
```
This will:

- Create the output/ folder.
- Download and set up required external tools.
- Create default payload templates.


## 🚀 Usage

```bash
python3 hunt3rx.py -d target.com

```


### Options

| Flag            | Description                         |
|-----------------|-------------------------------------|
| `-d`            | Target domain                       |
| `--install`     | Run the initial setup               |
| `--payload-dir` | Use custom payload directory        |
| `--no-banner`   | Disable ASCII banner                |
| `-h`            | Show help menu                      |

## 🛠 Examples

- **Full recon + vulnerability scan:**
  ```bash
  python3 hunt3rx.py -d example.com
- **Using custom payloads:**

    ```bash
    python3 hunt3rx.py -d example.com --payload-dir ~/payloads

- Silent mode without banner:

    ```bash
    python3 hunt3rx.py -d example.com --no-banner

## 📜 License
This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.



## ⚠ Disclaimer
**Hunt3rX** is intended for authorized security testing and educational purposes only.  
You are solely responsible for how you use this tool.



## 👤 Author
**Saurav Prajapati** (*P4nTh3r*)
