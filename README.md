# README.md for Hunt3rX

## 🐾 Hunt3rX
**Made by P4nTh3r**

Hunt3rX is an automated bug bounty reconnaissance and scanning toolkit designed to streamline the process of subdomain enumeration, port scanning, vulnerability detection, and more — all in one script.

---

### Features
- **Subdomain Enumeration** using subfinder, amass, and assetfinder.
- **Port Scanning** with nmap and masscan.
- **Web Recon** with screenshots, directory brute-forcing, and content discovery.
- **JavaScript Analysis** and **Parameter Discovery**.
- **Vulnerability Testing** for XSS, SQLi, LFI/RFI, SSRF, Open Redirects.
- **API Recon, CMS Detection, WAF Detection**.
- **S3 Bucket Enumeration & Information Disclosure Scans**.
- **Metasploit & Reverse Shell Automation**.

---

### Requirements
**Python Packages** (install with `pip install -r requirements.txt`):
```
requests
colorama
tqdm
```

**External Tools**:
subfinder, amass, assetfinder, nmap, masscan, eyewitness, aquatone, ffuf, gobuster, linkfinder, gf, paramspider, arjun, dalfox, XSStrike, sqlmap, gopherus, interactsh-client, lfisuite, fimap, oralyzer, nikto, httpx, kiterunner, gau, waybackurls, AWSBucketDump, cmseek, wafw00f, GitDumper, msfvenom, msfconsole.

---

### Installation
```bash
git clone https://github.com/yourusername/bug-hunter.git
cd bug-hunter
pip install -r requirements.txt
```

---

### Usage
```bash
python3 bug_hunter.py -d target.com
```
Optional flags:
- `--skip` to skip specific phases
- `--only` to run specific phases
- `--threads` to control concurrency

---

### Disclaimer
This tool is for **educational purposes only**. Do not use it without explicit permission from the target owner.

---

**Author:** P4nTh3r
