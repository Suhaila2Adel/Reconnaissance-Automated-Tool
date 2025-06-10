# Reconnaissance-Automated-Tool
This is task 1 of IT Solera internship 
A modular Python-based reconnaissance tool developed as part of the **ITSOLERA Cyber Department Summer Internship 2025**. The tool automates passive and active information gathering to support early-stage penetration testing and vulnerability assessments.

## 📌 Features

| Module         | Description |
|----------------|-------------|
| `--whois`      | Performs WHOIS lookup of target domain |
| `--dns`        | Enumerates DNS records (A, MX, TXT, NS) |
| `--subdomains` | Finds subdomains using crt.sh and HackerTarget |
| `--active`     | Basic active reconnaissance (IP resolution, banner grabbing) |
| `--ports`      | Scans common ports using Nmap |
| `--dirs`       | Brute-forces common directories using wordlist |
| `--vulns`      | Detects exposed `.env` or `.git/config` files |


## ⚙️ Installation
> Requires **Python 3.10+** and **Nmap** installed and added to your system PATH.
> open **main.py**, **providers** and **config** files in pycharm

Use this command in the pycharm terminal
```bash
# python main.py example.com --whois --dns --subdomains --ports --dirs --vulns 
