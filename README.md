<div align="center">

# 🛡️ Perimeter Notes
### Blue Team Practitioner | SOC · DFIR · Threat Intel · Malware Analysis

[![Status](https://img.shields.io/badge/Status-Active_Development-blue?style=flat-square&logo=git&logoColor=white)]()
[![Focus](https://img.shields.io/badge/Focus-Blue_Team_%7C_Defensive_Security-orange?style=flat-square)]()
[![Environment](https://img.shields.io/badge/Environment-Linux_Mint-green?style=flat-square&logo=linuxmint&logoColor=white)]()

*A defensive security portfolio documenting SOC operations, incident investigation, and custom tooling — built while progressing across the full Blue Team spectrum: monitoring, triage, forensics, threat hunting, and malware analysis.*

</div>

---

## 🧭 About the Repository

**Perimeter Notes** documents my path as a Blue Team practitioner, from foundational SOC operations to advanced Digital Forensics & Incident Response (DFIR) and malware analysis. Rather than focusing narrowly on tooling, this repository covers the full defensive lifecycle: detecting and triaging events, investigating incidents end-to-end, hunting for threats in logs and network traffic, and building the custom scripts that support those workflows. Designed to run efficiently on local, lightweight infrastructure, it serves as both a training log and a functional workspace for methodically dissecting adversarial tradecraft.

---

## 📂 Repository Architecture

```text
perimeter-notes/
├── tools/                  # Custom defensive scripts and automation
│   ├── log-parser-java/    # Security log ingestion and correlation engine (Java)
│   └── hardening-script-bash/ # Linux OS baseline hardening automation
└── writeups/               # Blue Team investigations: SOC triage, DFIR & threat hunting
    ├── 01-logjammer/       # [Easy] Log triaging and event correlation
    ├── 02-bumblebee/       # [Easy] Forensic artifact extraction
    ├── 03-pikaptcha/       # [Easy] Network and traffic inspection
    ├── 04-subatomic/       # [Medium] Intermediate threat hunting
    ├── 05-holmes-2-watchmans-residue/ # [Medium] Deep investigative tracking
    ├── 06-holmes-4-tunnel-without-walls/ # [Hard] Advanced network pivoting
    ├── 07-lockpick3/       # [Hard] System tampering and analysis
    ├── 08-safecracker/     # [Insane] Complex binary & structural compromise
    ├── 09-stonks/          # [Insane] High-complexity threat isolation
    └── 10-kamikaze/        # [Insane] Advanced malware tradecraft & forensics
```

---

## ⚙️ Blue Team Skillset & Tooling

* **SOC & Monitoring:** Log analysis and correlation, alert triage, SIEM-style workflows.
* **DFIR:** Forensic artifact extraction, timeline reconstruction, incident investigation end-to-end.
* **Threat Hunting & Network Analysis:** Wireshark, traffic inspection, native Linux CLI utilities (`grep`, `awk`, `jq`).
* **Malware Analysis (in progress):** Static/behavioral analysis fundamentals, building toward reverse engineering.
* **Scripting & Tooling:** Java (log parsing), Bash (automation & hardening).
* **Platforms & Labs:** Hack The Box (Sherlocks).
* **Environment:** Native Linux Mint XFCE (terminal-first, resource-optimized workflow).

---
*Author: Johan Emilio Regalado Cuesta*
