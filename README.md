# SubGhost - Powerful  Subdomain Finder

**SubGhost** is a fast and efficient subdomain enumeration tool designed to help security researchers, penetration testers, and bug bounty hunters find subdomains of target domains.

---

## 🚀 Features
- **Fast Subdomain Enumeration** using Private APIs.
- **Multi-threading Support** for faster processing (`-t` option).
- **Batch Processing** from a file containing multiple domains (`-f` option).
- **Clean and Simple Interface** with a cool ASCII banner.
- **Automatic Result Saving** into `.txt` files named after the target domain.
- **Duplicate Domain Handling** to avoid redundant checks.

---

## ⚙️ Installation
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Muhammad-Durjoy/Sub-Ghost.git
   cd SubGhost
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

---

## 📦 Usage
```bash
python SubGhost.py [OPTIONS]
```

### **Options:**
- `-d <domain>`       : Enumerate subdomains for a single domain.
- `-f <file.txt>`     : Enumerate subdomains for multiple domains from a file.
- `-t <threads>`      : Enable multi-threading with the specified number of threads.

---

## 💡 Example Usage
1. **Single Domain:**
   ```bash
   python SubGhost.py -d Domain.com
   ```

2. **Multiple Domains from File:**
   ```bash
   python  SubGhost.py -f domains.txt
   ```

3. **With Multi-threading:**
   ```bash
   python  SubGhost.py -f domains.txt -t 5
   ```

4. **File Format (domains.txt):**
   ```
   google.com
   tesla.com
   example.com
   Domain.com
   ```

---

## 📋 Example Output
```bash
[+] Fetching subdomains for: tesla.com
 - shop.tesla.com
 - support.tesla.com
 - forums.tesla.com

[+] Subdomains saved to tesla.txt
```

Output will be saved in a `.txt` file named after the domain, e.g., `tesla.txt`.

---
## 👤 Authors
- **Muhammad Durjoy**   
  - [X](https://x.com/MuhammadDurjoy1)  
  - [Teligram](http://t.me/Not_Durjoy)
  - [GitHub](https://github.com/Muhammad-Durjoy)   



---
## ⚠️ Disclaimer
This tool is for educational and ethical penetration testing purposes only. The author is **not responsible** for any misuse or illegal activities performed using this tool.

## 📄 License
This project is licensed under the **MIT License**. See the `LICENSE` file for details.

