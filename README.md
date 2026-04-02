# 🔍 ODorker

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux%20%2F%20Windows-informational?style=flat-square&logo=linux&logoColor=white&color=0a0c10"/>
  <img src="https://img.shields.io/badge/Category-OForensics%20%2F%20OSINT-cyan?style=flat-square"/>
  <img src="https://img.shields.io/badge/Dependencies-None%20(Standalone)-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-Proprietary-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-v1.0-cyan?style=flat-square"/>
</p>

> **ODorker** is an automated Google Dorking engine. It discovers exposed sensitive files, admin panels, login pages, configuration files, credentials, backups, logs, cameras, and more using advanced Google dork queries.

---

## 📌 Overview

ODorker automates the process of building and executing Google dorks to find publicly exposed sensitive information on a target domain or across the internet. It includes over 100 built-in dorks categorized by severity and type.

**Use only on domains you own or are explicitly authorized to test.**

---

## 🖥️ Modules

| # | Module                  | Description |
|---|-------------------------|-------------|
| **[1]** | **Auto Dork**           | Run all dork categories on a target |
| **[2]** | **Selective Dork**      | Choose specific dork categories |
| **[3]** | **Custom Dork**         | Run your own custom dork query |
| **[4]** | **Dork Builder**        | Build dork queries interactively |
| **[5]** | **Bulk Targets**        | Dork multiple domains at once |
| **[6]** | **Dork Library**        | Browse all built-in dorks |

---

## 📊 Key Features

- **100+ Built-in Dorks** — Categorized by severity (Critical, High, Medium, Info)
- **Dork Categories**:
  - **Admin** — Panels, dashboards, control boards
  - **Login** — Authentication forms, portals
  - **Files** — Leaked PDFs, SQL dumps, CSVs, documents
  - **Config** — `.env`, `wp-config`, `settings.php`, YAML files
  - **Backup** — `.bak`, `.zip`, `.tar.gz`, database backups
  - **Database** — phpMyAdmin, Adminer, exposed DB interfaces
  - **Logs** — Error logs, debug output, access logs
  - **Cameras** — Exposed IP cameras and CCTV panels
  - **Credentials** — API keys, tokens, passwords in URLs
  - **Git** — Exposed `.git` directories and source leaks
  - **Dirs** — Open directory listings
  - **Vulns** — Potential vulnerable parameters and errors
- **Result Parsing** — Extracts URL, title, snippet with deduplication
- **Export Options** — JSON and TXT reports
- **Rate Limiting** — Configurable delay to avoid blocks

---

## ⚙️ Requirements

- **Linux or Windows**
- **No additional dependencies** — uses only Python standard library

---

## 🚀 Usage

```bash
./ODorker

📁 Output

Live Results — Color-coded findings with severity icons
Detailed Reports — URL, title, snippet, and original dork used
JSON Export — Structured data for further analysis
TXT Export — Human-readable summary


📦 Part of OwlSec Toolkit
This tool is part of the OwlSec suite — a collection of 300+ security and privacy tools.
🔗 owlsec.org

©️ License
Proprietary — © Khaled S. Haddad
Tools are distributed as pre-built executables. Source code is proprietary.

AUTHORISED SECURITY TESTING & OSINT USE ONLY
