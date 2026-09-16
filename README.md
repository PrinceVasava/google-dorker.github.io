# Google Dork Intelligence 🔍

A sleek, modern dark-themed reconnaissance and OSINT search intelligence dashboard built for Security Researchers, Bug Bounty Hunters, and Penetration Testers.

🌐 **Live Demo:** [https://princevasava.github.io/google-dorking.github.io/](https://princevasava.github.io/google-dorking.github.io/)

---

## ✨ Features

- **Wildcard Domain Targeting:** Seamlessly interpolate wildcard scopes (`site:*.{target}`) into search queries.
- **Category-Wise Intelligence:**
  - 🌐 Subdomains & APIs
  - 📄 Sensitive Documents
  - ⚙️ Config & Environment Leaks
  - 🔐 Admin Panels & Login Gateways
  - 📁 Directory Indexing & Traversal
  - ☁️ Cloud Storage & Buckets
  - 📦 Source Code & Repositories
  - 🛡️ Vulnerabilities & Error Dumps
  - 🔎 OSINT & 3rd-Party Recon
- **Input Sanitization & Security:** Strict XSS prevention, character whitelisting, and protocol verification.
- **Minimalist Cyber UI:** High-density dark glassmorphic interface with custom cyber backdrop.

---

## 🚀 Usage

1. Open the [live application](https://princevasava.github.io/google-dorking.github.io/) in your browser.
2. Enter your target domain in the controller input (e.g. `example.com`).
3. Select any category from the filter pills to browse tailored dorks.
4. Click **Search on Google** or **Open External Service** to launch targeted queries.

---

## ⚠️ Advisory & Rate Limiting

- Executing numerous queries in rapid succession may trigger Google anti-automation mechanisms (such as CAPTCHA challenges or temporary rate limits).
- Pace query executions moderately and inspect results manually.

---

## ⚖️ Legal Disclaimer

> **IMPORTANT:** This tool is designed strictly for authorized security research, bug bounty hunting, and penetration testing within explicitly defined scopes. Users are responsible for complying with all applicable laws and program guidelines.

---

## 👤 Author

- **Created by:** [Prince Vasava](https://github.com/PrinceVasava)
- **GitHub Profile:** [github.com/PrinceVasava](https://github.com/PrinceVasava)
- **Copyright:** © 2026 Prince Vasava. All rights reserved.
