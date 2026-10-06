<div align="center">

# 👋 Hi, I'm Trần Bách Thăng

### 🤖 AI Red Teamer · LLM/AI Security · Agent Engineering

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&pause=1000&color=2EA44F&center=true&vCenter=true&width=560&lines=AI+Red+Teamer+%7C+LLM+Security;Agent+Engineering+%26+Guardrails;Offensive+Security+Background;Threat+Model+%E2%86%92+Exploit+%E2%86%92+Evidence+%E2%86%92+Mitigation)](https://git.io/typing-svg)

<img src="https://komarev.com/ghpvc/?username=tranbachthang&color=2EA44F&style=for-the-badge&label=PROFILE+VIEWS" alt="views"/>

</div>

---

## 🧑‍💻 About Me

- 🤖 **AI Red Teamer** — studying the full **HTB Academy AI Red Teamer Job-Role Path (ID 418)**: 12 modules / 230 sections — prompt injection, LLM output attacks, data poisoning, adversarial evasion, privacy attacks, AI defence
- 🛡️ **Offensive security background** — CyberJutsu Web Pentest: exploited **7 vulnerabilities** on a real app (incl. **Critical RCE, CVSS 9.8** via PHP POP-chain deserialization) and delivered a 28-page report
- 🧱 **Build the things that get attacked** — I run my own agent platform (extensions, skills, sub-agents, model-routing gateway) with an untrusted-content boundary and a policy guard + kill-switch
- 🎓 HCMUTE — Faculty of IT, Computer Systems & Networks · MSSV 23162094
- 🎯 Target: **AI Red Teamer / AI Security Engineer / AI Agent Trainer**

> I test AI the way I test web apps: **threat model → exploit → evidence → mitigation**.

## 🔬 AI Security Focus

**LLM / AI Red Teaming**<br>
Prompt injection (direct · indirect · multi-turn) · jailbreak & refusal analysis · system-prompt extraction · LLM output weaponisation (XSS/SQLi from model output) · data poisoning & label flipping · adversarial evasion (FGSM, gradient-based, L0/EAD sparsity) · Membership Inference · OWASP LLM / ML Top 10 threat modelling

**AI Defence & Guardrails**<br>
Untrusted-content boundaries for agent input · instruction/data separation · rule-based policy enforcement + kill-switch · allowlist tool gating · system-wide prompt guidelines · outcome logging for audit

**Agent Engineering**<br>
Multi-agent orchestration (planner → scout → worker → reviewer) · tool/function registration · agent memory (per-target recall/remember) · skill packaging with metadata + promote/rollback · multi-model routing gateway · telemetry & watchdog · budget brakes for unattended runs

## 🚀 Featured Projects

| Project | Description | Stack |
|---------|-------------|-------|
| 🎯 **Automated Prompt-Injection Harness** | `ai_arena.js` — red-teams live LLM-agent apps end to end: catalogue pull, headful browser drive, curated injection library (system-prompt extraction, instruction override, debug/JSON tricks), score read-back + verbatim responses persisted to a behavioural dataset | Node.js · Browser Automation |
| 🛡 **Untrusted Tool-Output Boundary** | Every external tool result (HTTP responses, scans, downloaded files) wrapped in a random-**nonce** marker so attacker-embedded `SYSTEM: ignore previous instructions` is treated as data, never instruction | TypeScript · Agent Hook |
| ⚖️ **Policy Guard & Kill-Switch** | Declarative rule engine (`policy_rules.mjs`, self-testable) that blocks protected actions and logs every block with the rule that fired; per-day cost brake + sleep-until-reset for unattended agents | Node.js · Append-only Audit |
| 🧠 **Self-Built Agent Platform** | Platform I run daily: **19 extensions · 63 skills · 10 sub-agents · 313 assistant files** — promote/rollback skill pipeline, per-target memory, multi-model routing (zero-cost for mechanical work), telemetry + 3 independent brakes (rounds / cost / minutes) | TypeScript · Node.js |
| 📡 [**pcap-pipeline**](https://github.com/tranbachthang/pcap-pipeline) | PCAP intrusion detection — 8 phases, **10 AI agents**, rule-based scoring + **Isolation Forest** ML; detects port scan, brute force, C2 beaconing, exfiltration, backdoor, DNS tunneling/DGA | Python · Scapy · ML |
| 📶 [**network-monitoring-system**](https://github.com/tranbachthang/network-monitoring-system) | Network monitoring & anomaly detection (Zabbix + PRTG + SNMP + Isolation Forest) with alerting | Flask · ML |
| 🎯 [**web-pentest-toolkit**](https://github.com/tranbachthang/web-pentest-toolkit) | Blind SQLi brute-force + Playwright browser-automation agent | Python · Playwright |

**Web App Pentest — Social Network (CyberJutsu Final Exam, grey-box)**<br>
7 vulnerabilities chained into full compromise — Insecure Deserialization (PHP POP chain) → RCE **9.8**, SQLi (32-table dump) **8.1**, webshell upload **8.1**, blind SQLi **8.1**, RSA private-key disclosure **7.5**, IDOR **6.5**, reflected XSS → admin JWT theft **6.1**. 28-page report with PoC, CVSS, root cause and remediation. Plus a self-hosted **59-exercise training range** (Docker + nginx + Cloudflare Tunnel) and `DeepRecon`, a 5-agent recon framework (OSINT → attack surface → NVD CVE lookup → validation → report).

## 📜 Certifications & Training

- 🤖 **HTB Academy — AI Red Teamer Job-Role Path (418)** — in progress · 12 modules / 230 sections self-summarised into a 244-file study base
- 📶 **HTB Academy — Wi-Fi Pentester path** — 802.11 attacks, WPS/WEP/WPA2/WPA3, evil twin, password cracking
- 🏆 **CyberJutsu Academy** — Web Penetration Testing Certificate (2026) — 7 exploited vulnerabilities incl. Critical RCE
- 🧪 **PortSwigger Web Security Academy** — ~100 labs (SQLi, XSS, access control, XXE, JWT, deserialization)
- 🧠 OWASP WebGoat / Juice Shop — hands-on labs

## 🛠 Tech Stack

**AI / Security R&D**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Scapy](https://img.shields.io/badge/Scapy-000000?style=for-the-badge)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)

**Offensive Security**<br>
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white)
![OWASP ZAP](https://img.shields.io/badge/OWASP_ZAP-00549E?style=for-the-badge&logo=owasp&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-0E83CD?style=for-the-badge&logo=nmap&logoColor=white)
![sqlmap](https://img.shields.io/badge/sqlmap-000000?style=for-the-badge)
![Metasploit](https://img.shields.io/badge/Metasploit-2596BE?style=for-the-badge&logo=metasploit&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)

**Languages & Infra**<br>
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

## 📊 GitHub Stats

<div align="center">

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=tranbachthang&theme=github-dark&hide_border=true&area=true)

<img height="170" src="https://github-readme-stats.vercel.app/api?username=tranbachthang&show_icons=true&theme=github_dark&hide_border=true&count_private=true"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=tranbachthang&layout=compact&theme=github_dark&hide_border=true"/>

<img src="https://streak-stats.demolab.com?user=tranbachthang&theme=github-dark-blue&hide_border=true" alt="streak"/>

![Trophy](https://github-profile-trophy.vercel.app/?username=tranbachthang&theme=onedark&no-frame=true&column=6&margin-w=15)

</div>

## 🐍 Contribution Snake (animation)

<div align="center">

![snake](https://raw.githubusercontent.com/tranbachthang/tranbachthang/output/github-contribution-grid-snake.svg)

</div>

## 📫 Contact

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:thangtran.hcmute@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/tranbachthang)

</div>
