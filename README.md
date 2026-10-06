<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:1E3A8A,100:2EA44F&height=200&section=header&text=Tr%E1%BA%A7n%20B%C3%A1ch%20Th%C4%83ng&fontSize=44&fontColor=ffffff&fontAlignY=38&desc=AI%20Red%20Teamer%20%C2%B7%20LLM%2FAI%20Security%20%C2%B7%20Malware%20Analysis%20%26%20RE&descAlignY=58&descSize=17" width="100%"/>

### 🤖 AI Red Teamer · LLM/AI Security · Agent Engineering · Malware Analysis

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&pause=1000&color=2EA44F&center=true&vCenter=true&width=620&lines=AI+Red+Teamer+%7C+LLM+Security;Malware+Analysis+%26+Reverse+Engineering;Agent+Engineering+%26+Guardrails;Threat+Model+%E2%86%92+Exploit+%E2%86%92+Evidence+%E2%86%92+Mitigation)](https://git.io/typing-svg)

<a href="https://github.com/tranbachthang?tab=repositories"><img src="https://img.shields.io/badge/Repositories-23-181717?style=for-the-badge&logo=github&logoColor=white" alt="repos"/></a>
<a href="mailto:thangtran.hcmute@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="mail"/></a>
<img src="https://komarev.com/ghpvc/?username=tranbachthang&color=2EA44F&style=for-the-badge&label=PROFILE+VIEWS" alt="views"/>

<sub>📍 Ho Chi Minh City, Vietnam · 🎓 HCMUTE — Faculty of IT, Computer Systems & Networks · MSSV 23162094</sub>

</div>

---

## 🧑‍💻 About Me

- 🤖 **AI Red Teamer** — studying the full **HTB Academy AI Red Teamer Job-Role Path (ID 418)**: 12 modules / 230 sections — prompt injection, LLM output attacks, data poisoning, adversarial evasion, privacy attacks, AI defence
- 🧬 **Malware analysis & reverse engineering** — static + dynamic + manual unpack of real samples in an isolated VM (DIE · PEStudio · CFF Explorer · PE-sieve · x32dbg · Procmon · Regshot · FakeNet-NG · IDA Free), with a self-built pipeline that pushes every artefact to the host as text and auto-generates the Word report
- 🛡️ **Offensive security background** — CyberJutsu Web Pentest: exploited **7 vulnerabilities** on a real app (incl. **Critical RCE, CVSS 9.8** via PHP POP-chain deserialization) and delivered a 28-page report
- 🧱 **Build the things that get attacked** — I run my own agent platform (extensions, skills, sub-agents, model-routing gateway) with an untrusted-content boundary and a policy guard + kill-switch
- 🎯 Target: **AI Red Teamer / AI Security Engineer / AI Agent Trainer**

> I test AI the way I test web apps and binaries: **threat model → exploit → evidence → mitigation**.

<div align="center">

### ⚡ At a glance

| 🤖 AI / LLM Red Teaming | 🧬 Malware Analysis & RE | 🛡️ Offensive Security |
|:---:|:---:|:---:|
| Prompt injection (direct · indirect · jailbreak) | Static triage: DIE · PEStudio · CFF Explorer | 7 web vulns exploited on a live app |
| LLM output weaponisation (XSS/SQLi) | Dynamic in network-isolated VM | **Critical RCE 9.8** (PHP POP chain) |
| Adversarial evasion · data poisoning | **Manual unpack**: LoadLibrary + PE-sieve | SQLi · IDOR · SSRF · XXE · upload bypass |
| Guardrails, kill-switch, audit logging | IOC extraction · embedded-PE carving | Report with PoC · CVSS · remediation |

</div>

---

## 🔬 AI Security Focus

**LLM / AI Red Teaming**<br>
Prompt injection (direct · indirect · multi-turn) · jailbreak & refusal analysis · system-prompt extraction · LLM output weaponisation (XSS/SQLi from model output) · data poisoning & label flipping · adversarial evasion (FGSM, gradient-based, L0/EAD sparsity) · Membership Inference · OWASP LLM / ML Top 10 threat modelling

**AI Defence & Guardrails**<br>
Untrusted-content boundaries for agent input · instruction/data separation · rule-based policy enforcement + kill-switch · allowlist tool gating · system-wide prompt guidelines · outcome logging for audit

**Malware Analysis & Reverse Engineering**<br>
Static triage (hash · entropy · section/import analysis · strings/FLOSS IOC extraction) · dynamic analysis in a network-isolated VM · **manual unpacking** (LoadLibrary loader + PE-sieve memory dumps) · embedded-PE carving & XOR-key hunting · anti-analysis awareness (packer detection, obfuscation, `.rsrc` compression) · artifact/provenance verification (a dumped blob that "looked like payload" was proven to be Windows MUI resources — conclusion corrected, not written up as a find)

**Agent Engineering**<br>
Multi-agent orchestration (planner → scout → worker → reviewer) · tool/function registration · agent memory (per-target recall/remember) · skill packaging with metadata + promote/rollback · multi-model routing gateway · telemetry & watchdog · budget brakes for unattended runs

---

## 🚀 Featured Projects

| Project | Description | Stack |
|---------|-------------|-------|
| 🎯 **Automated Prompt-Injection Harness** | `ai_arena.js` — red-teams live LLM-agent apps end to end: catalogue pull, headful browser drive, curated injection library (system-prompt extraction, instruction override, debug/JSON tricks), score read-back + verbatim responses persisted to a behavioural dataset | Node.js · Browser Automation |
| 🛡 **Untrusted Tool-Output Boundary** | Every external tool result (HTTP responses, scans, downloaded files) wrapped in a random-**nonce** marker so attacker-embedded `SYSTEM: ignore previous instructions` is treated as data, never instruction | TypeScript · Agent Hook |
| ⚖️ **Policy Guard & Kill-Switch** | Declarative rule engine (`policy_rules.mjs`, self-testable) that blocks protected actions and logs every block with the rule that fired; per-day cost brake + sleep-until-reset for unattended agents | Node.js · Append-only Audit |
| 🧠 **Self-Built Agent Platform** | Platform I run daily: **19 extensions · 63 skills · 10 sub-agents · 313 assistant files** — promote/rollback skill pipeline, per-target memory, multi-model routing (zero-cost for mechanical work), telemetry + 3 independent brakes (rounds / cost / minutes) | TypeScript · Node.js |
| 🧬 **Malware Analysis Pipeline** | 3 real samples analysed end to end (static → dynamic → manual unpack → report); reusable tooling: `analyze.ps1` + `vm_receiver.py` push text over HTTP instead of reading hundreds of screenshots | PowerShell · PE-sieve · Python |
| 📡 [**pcap-pipeline**](https://github.com/tranbachthang/pcap-pipeline) | PCAP intrusion detection — 8 phases, **10 AI agents**, rule-based scoring + **Isolation Forest** ML; detects port scan, brute force, C2 beaconing, exfiltration, backdoor, DNS tunneling/DGA | Python · Scapy · ML |
| 📶 [**network-monitoring-system**](https://github.com/tranbachthang/network-monitoring-system) | Network monitoring & anomaly detection (Zabbix + PRTG + SNMP + Isolation Forest) with alerting | Flask · ML |
| 🎯 [**web-pentest-toolkit**](https://github.com/tranbachthang/web-pentest-toolkit) | Blind SQLi brute-force + Playwright browser-automation agent | Python · Playwright |

#### 🧬 Malware Analysis — real samples, isolated VM (Win7 x64, VNC, no shared folders)

Analysed **PE64 DLL samples** end to end: `Detect It Easy` triage (packed 81%, entropy 6.54, VS2022, 7 sections) → 307-line IOC extraction (config keys, `JSON-RPC 2.0` C2 protocol, Mutex, PDB path, raw-Winsock imports WS2_32/CRYPT32/bcrypt/ADVAPI32) → **manual unpack** with a PowerShell `LoadLibrary` loader + PE-sieve → post-processing on the host with self-written Python (`check_resc_blob.py`, `extract_embed.py`, `xor_key_hunt.py`) → Word report with POC screenshots. Cross-checked behaviour with **Regshot / FakeNet-NG / x32dbg / Procmon**.

#### 🎯 Web App Pentest — Social Network (CyberJutsu Final Exam, grey-box)

7 vulnerabilities chained into full compromise: Insecure Deserialization (PHP POP chain) → RCE **9.8** · SQLi (32-table dump) **8.1** · webshell upload **8.1** · blind SQLi **8.1** · RSA private-key disclosure **7.5** · IDOR **6.5** · reflected XSS → admin JWT theft **6.1**. Delivered a 28-page report with PoC, CVSS, root cause and remediation. Plus a self-hosted **59-exercise training range** (Docker + nginx + Cloudflare Tunnel) and `DeepRecon`, a 5-agent recon framework (OSINT → attack surface → NVD CVE lookup → validation → report).

---

## 📜 Certifications & Training

| | |
|---|---|
| 🤖 **HTB Academy** | AI Red Teamer Job-Role Path (418) — in progress · 12 modules / 230 sections self-summarised into a 244-file study base |
| 📶 **HTB Academy** | Wi-Fi Pentester path — 802.11 attacks, WPS/WEP/WPA2/WPA3, evil twin, password cracking |
| 🏆 **CyberJutsu Academy** | Web Penetration Testing Certificate (2026) — 7 exploited vulnerabilities incl. Critical RCE |
| 🧪 **PortSwigger** | Web Security Academy — ~100 labs (SQLi, XSS, access control, XXE, JWT, deserialization) |
| 🧠 **OWASP** | WebGoat / Juice Shop — hands-on labs |

---

## 🛠 Tech Stack

**Core languages & runtime**<br>
<img src="https://skillicons.dev/icons?i=py,ts,js,nodejs,php,java,bash,powershell,docker,linux,git" alt="core"/>

**AI / LLM security**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Scapy](https://img.shields.io/badge/Scapy-000000?style=for-the-badge)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![OWASP LLM Top 10](https://img.shields.io/badge/OWASP_LLM_Top_10-00549E?style=for-the-badge&logo=owasp&logoColor=white)

**Malware Analysis & Reverse Engineering**<br>
![Detect It Easy](https://img.shields.io/badge/Detect_It_Easy_(DIE)-2E7D32?style=for-the-badge)
![PEStudio](https://img.shields.io/badge/PEStudio-4B5563?style=for-the-badge)
![CFF Explorer](https://img.shields.io/badge/CFF_Explorer-6B7280?style=for-the-badge)
![PE-sieve](https://img.shields.io/badge/PE--sieve-1F2937?style=for-the-badge)
![x32dbg](https://img.shields.io/badge/x32dbg-374151?style=for-the-badge)
![IDA Free](https://img.shields.io/badge/IDA_Free-111827?style=for-the-badge)
![FLOSS](https://img.shields.io/badge/FLOSS-7C3AED?style=for-the-badge)
![Procmon](https://img.shields.io/badge/Procmon-0EA5E9?style=for-the-badge)
![Regshot](https://img.shields.io/badge/Regshot-0D9488?style=for-the-badge)
![FakeNet-NG](https://img.shields.io/badge/FakeNet--NG-B91C1C?style=for-the-badge)
![VMware Sandbox](https://img.shields.io/badge/VMware_Sandbox-607078?style=for-the-badge&logo=vmware&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)

**Offensive Security**<br>
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white)
![OWASP ZAP](https://img.shields.io/badge/OWASP_ZAP-00549E?style=for-the-badge&logo=owasp&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-0E83CD?style=for-the-badge&logo=nmap&logoColor=white)
![sqlmap](https://img.shields.io/badge/sqlmap-000000?style=for-the-badge)
![ffuf](https://img.shields.io/badge/ffuf-000000?style=for-the-badge)
![Gobuster](https://img.shields.io/badge/Gobuster-2C3E50?style=for-the-badge)
![Metasploit](https://img.shields.io/badge/Metasploit-2596BE?style=for-the-badge&logo=metasploit&logoColor=white)
![Hydra](https://img.shields.io/badge/Hydra-DC2626?style=for-the-badge)
![John the Ripper](https://img.shields.io/badge/John_the_Ripper-1F2937?style=for-the-badge)
![hashcat](https://img.shields.io/badge/hashcat-1E40AF?style=for-the-badge)
![aircrack-ng](https://img.shields.io/badge/aircrack--ng-0F766E?style=for-the-badge)
![hcxdumptool](https://img.shields.io/badge/hcxdumptool_%2F_hcxpcapngtool-334155?style=for-the-badge)

**Blue Team / Monitoring**<br>
![Suricata](https://img.shields.io/badge/Suricata-B91C1C?style=for-the-badge)
![Zabbix](https://img.shields.io/badge/Zabbix-D40000?style=for-the-badge&logo=zabbix&logoColor=white)
![PRTG](https://img.shields.io/badge/PRTG-00A3E0?style=for-the-badge)
![SNMP](https://img.shields.io/badge/SNMP-475569?style=for-the-badge)
![GNS3](https://img.shields.io/badge/GNS3-1E3A8A?style=for-the-badge)
![Cisco Packet Tracer](https://img.shields.io/badge/Cisco_Packet_Tracer-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

![Profile details](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=tranbachthang&theme=github_dark)

<img height="170" src="https://github-readme-stats.vercel.app/api?username=tranbachthang&show_icons=true&theme=github_dark&hide_border=true&count_private=true&rank_icon=github"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=tranbachthang&layout=compact&theme=github_dark&hide_border=true&langs_count=8"/>

<img src="https://streak-stats.demolab.com?user=tranbachthang&theme=github-dark-blue&hide_border=true" alt="streak"/>

</div>

---

<div align="center">

### 📫 Let's talk security

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:thangtran.hcmute@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/tranbachthang)

<sub>Open to <b>AI Red Team / AI Security / Pentest</b> opportunities and research collaboration.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2EA44F,50:1E3A8A,100:0F172A&height=120&section=footer" width="100%"/>

</div>
