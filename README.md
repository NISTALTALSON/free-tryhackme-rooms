<div align="center">

# 🔐 Free TryHackMe Hacking Roadmap
### A Structured Path From Zero to Hacker — 400+ Free Rooms, Zero Paywalls

[![Maintained by](https://img.shields.io/badge/Maintained%20by-NISTALTALSON-blue?style=for-the-badge&logo=github)](https://github.com/NISTALTALSON)
[![TryHackMe](https://img.shields.io/badge/Platform-TryHackMe-red?style=for-the-badge)](https://tryhackme.com)
[![Rooms](https://img.shields.io/badge/Free%20Rooms-400%2B-green?style=for-the-badge)](https://tryhackme.com)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

> **"Everyone deserves to learn hacking. This roadmap is your cheat code."**

</div>

---

## 🧠 Why This Exists

Most free TryHackMe lists are just category dumps.  
This one is a **structured learning roadmap** — each phase builds on the last, designed so a total beginner becomes a real threat by the end.

No subscription. No courses to buy. Just grind.

---

## 📊 Roadmap Overview

```
PHASE 0 ──▶ PHASE 1 ──▶ PHASE 2 ──▶ PHASE 3 ──▶ PHASE 4
  Start        Core         Tools      Recon &      Web
  Here       Foundations   & Scanning   OSINT      Hacking

PHASE 5 ──▶ PHASE 6 ──▶ PHASE 7 ──▶ PHASE 8 ──▶ PHASE 9
  Privesc   Post-Exploit   Defense     Advanced     CTF
& Exploit    & AD Attacks  Track (SOC)  Tracks    Practice
```

---

## 📋 Table of Contents

| Phase | Topic | Rooms |
|-------|-------|-------|
| [Phase 0](#-phase-0--start-here) | Start Here — Orientation | 8 |
| [Phase 1](#-phase-1--core-foundations) | Core Foundations — Linux, Windows, Networking | 16 |
| [Phase 2](#-phase-2--scripting--cryptography) | Scripting & Cryptography | 14 |
| [Phase 3](#-phase-3--hacking-methodology--tools) | Hacking Methodology & Tools | 20 |
| [Phase 4](#-phase-4--reconnaissance--osint) | Reconnaissance & OSINT | 12 |
| [Phase 5](#-phase-5--web-application-hacking) | Web Application Hacking | 28 |
| [Phase 6](#-phase-6--exploitation--privilege-escalation) | Exploitation & Privilege Escalation | 22 |
| [Phase 7](#-phase-7--defense-track--soc--dfir) | Defense Track — SOC, DFIR, Forensics | 20 |
| [Phase 8](#-phase-8--advanced-specializations) | Advanced Specializations | 36 |
| [Phase 9](#-phase-9--ctf-practice) | CTF Practice — Easy → Hard | 100+ |
| [Bonus](#-bonus--special-events) | Special Events & Advent of Cyber | 10 |

> ⚠️ **Note:** TryHackMe occasionally moves rooms behind a paywall. If a room shows as Premium, it's been flagged below or skip to the next one.

---

## ☑️ Progress Tracker

Use checkboxes to track what you've done. Fork this repo and check them off as you go!

---

## 🟢 Phase 0 — Start Here

> **Who is this for?** Absolute beginners. Never used TryHackMe before.  
> **Time estimate:** ~2–3 hours  
> **Goal:** Get the platform set up, understand how hacking rooms work.

- [ ] [TryHackMe | Tutorial](https://tryhackme.com/room/tutorial) — Your very first room. Deploy a machine, answer questions.
- [ ] [TryHackMe | How to use TryHackMe](https://tryhackme.com/room/howtousetryhackme) — Navigate the platform like a pro.
- [ ] [TryHackMe | Hello](https://tryhackme.com/room/hello) — Quick welcome room.
- [ ] [TryHackMe | OpenVPN](https://tryhackme.com/room/openvpn) — Set up your VPN to access machines.
- [ ] [TryHackMe | Learning Cyber Security](https://tryhackme.com/room/beginnerpathintro) — Overview of the entire field.
- [ ] [TryHackMe | Starting Out In Cyber Sec](https://tryhackme.com/room/startingoutincybersec) — Career paths: Red Team vs Blue Team.
- [ ] [TryHackMe | Introductory Researching](https://tryhackme.com/room/introtoresearch) — How hackers Google. Seriously.
- [ ] [TryHackMe | CC: Pen Testing](https://tryhackme.com/room/ccpentesting) — A taste of what pentesting actually looks like.

---

## 🔵 Phase 1 — Core Foundations

> **Who is this for?** Anyone who needs Linux/Windows/networking basics before hacking.  
> **Time estimate:** ~1–2 weeks  
> **Goal:** Speak fluent terminal, understand how computers and networks actually work.

### 🐧 Linux Fundamentals

- [ ] [TryHackMe | Learn Linux](https://tryhackme.com/room/zthlinux) — Full Linux intro: commands, files, permissions.
- [ ] [TryHackMe | Linux Modules](https://tryhackme.com/room/linuxmodules) — Deeper Linux: users, processes, services.
- [ ] [TryHackMe | Linux Fundamentals Part 1](https://tryhackme.com/room/linuxfundamentalspart1) — File system navigation, basic commands.
- [ ] [TryHackMe | Linux Strength Training](https://tryhackme.com/room/linuxstrengthtraining) — Hardcore Linux drills to build muscle memory.
- [ ] [TryHackMe | Linux Agency](https://tryhackme.com/room/linuxagency) — Gamified Linux challenge with 30+ missions.

> ⚠️ Linux Fundamentals Part 2 & 3 have been moved to Premium. Supplement with [OverTheWire: Bandit](https://overthewire.org/wargames/bandit/) (free forever).

### 🪟 Windows Fundamentals

- [ ] [TryHackMe | Windows Fundamentals 1](https://tryhackme.com/room/windowsfundamentals1xbx) — The Windows file system, GUI, and processes.
- [ ] [TryHackMe | Windows Fundamentals 2](https://tryhackme.com/room/windowsfundamentals2x0x) — System config, UAC, Task Manager.
- [ ] [TryHackMe | Windows Fundamentals 3](https://tryhackme.com/room/windowsfundamentals3xzx) — Windows security features, Defender, BitLocker.

### 🌐 Networking

- [ ] [TryHackMe | What is Networking?](https://tryhackme.com/room/whatisnetworking) — IP, MAC, how data moves.
- [ ] [TryHackMe | Introductory Networking](https://tryhackme.com/room/introtonetworking) — OSI model, TCP/IP, packets.
- [ ] [TryHackMe | Networking](https://tryhackme.com/room/bpnetworking) — Practical network concepts.
- [ ] [TryHackMe | HTTP in Detail](https://tryhackme.com/room/httpindetail) — How web requests and responses work. Critical for web hacking.
- [ ] [TryHackMe | DNS in Detail](https://tryhackme.com/room/dnsindetail) — How domain names resolve. Essential for recon.
- [ ] [TryHackMe | Dumping Router Firmware](https://tryhackme.com/room/rfirmware) — Hardware-level networking. Bonus.

---

## 🟡 Phase 2 — Scripting & Cryptography

> **Who is this for?** You know Linux basics. Now automate attacks and understand encryption.  
> **Time estimate:** ~1 week  
> **Goal:** Write your own tools. Crack hashes. Understand what encryption actually is.

### 🐍 Scripting

- [ ] [TryHackMe | Python Basics](https://tryhackme.com/room/pythonbasics) — Variables, loops, functions. Start here.
- [ ] [TryHackMe | Python Playground](https://tryhackme.com/room/pythonplayground) — Build small scripts in a sandbox.
- [ ] [TryHackMe | Intro PoC Scripting](https://tryhackme.com/room/intropocscripting) — Write actual proof-of-concept exploit scripts.
- [ ] [TryHackMe | Bash Scripting](https://tryhackme.com/room/bashscripting) — Automate everything with bash. A hacker must-have.
- [ ] [TryHackMe | JavaScript Basics](https://tryhackme.com/room/javascriptbasics) — Essential for web hacking and XSS.
- [ ] [TryHackMe | Regular Expressions](https://tryhackme.com/room/catregex) — Pattern matching that powers every security tool.
- [ ] [TryHackMe | Learn Rust](https://tryhackme.com/room/rust) — Optional: Modern systems language used in malware and tools.

### 🔐 Cryptography & Hashes

- [ ] [TryHackMe | Cryptography for Dummies](https://tryhackme.com/room/cryptographyfordummies) — Symmetric, asymmetric, hashing. No math degree needed.
- [ ] [TryHackMe | Encryption - Crypto 101](https://tryhackme.com/room/encryptioncrypto101) — Deep dive into real encryption schemes.
- [ ] [TryHackMe | Crack the Hash](https://tryhackme.com/room/crackthehash) — MD5, SHA1, bcrypt — crack them all.
- [ ] [TryHackMe | Crack The Hash Level 2](https://tryhackme.com/room/crackthehashlevel2) — Harder hashes, custom wordlists.
- [ ] [TryHackMe | Brute It](https://tryhackme.com/room/bruteit) — Dictionary attacks in practice.
- [ ] [TryHackMe | Agent Sudo](https://tryhackme.com/room/agentsudoctf) — Hashes + steganography combined mini-challenge.

---

## 🟠 Phase 3 — Hacking Methodology & Tools

> **Who is this for?** You have foundations. Time to pick up hacker tools.  
> **Time estimate:** ~1–2 weeks  
> **Goal:** Know your toolkit cold. Nmap, Metasploit, Burp Suite, Hydra — fluent use.

### 🧭 Methodology & Fundamentals

- [ ] [TryHackMe | Pentesting Fundamentals](https://tryhackme.com/room/pentestingfundamentals) — Rules of engagement, phases, legal framework.
- [ ] [TryHackMe | Principles of Security](https://tryhackme.com/room/principlesofsecurity) — CIA Triad, defense concepts.
- [ ] [TryHackMe | The Hacker Methodology](https://tryhackme.com/room/hackermethodology) — Recon → Scan → Exploit → Report.
- [ ] [TryHackMe | Physical Security Intro](https://tryhackme.com/room/physicalsecurityintro) — Social engineering + physical attacks.
- [ ] [TryHackMe | Vulnerabilities 101](https://tryhackme.com/room/vulnerabilities101) — CVEs, CVSS scoring, how vulns are classified.
- [ ] [TryHackMe | OpenVAS](https://tryhackme.com/room/openvas) — Automated vulnerability scanning.

### 🔧 Core Tools

- [ ] [TryHackMe | Nmap](https://tryhackme.com/room/furthernmap) — The most important recon tool. Master it.
- [ ] [TryHackMe | Nmap Live Host Discovery](https://tryhackme.com/room/nmap01) — Host detection techniques.
- [ ] [TryHackMe | RustScan](https://tryhackme.com/room/rustscan) — Nmap on steroids. Faster port scanning.
- [ ] [TryHackMe | Metasploit: Introduction](https://tryhackme.com/room/metasploitintro) — World's most used exploitation framework.
- [ ] [TryHackMe | Metasploit](https://tryhackme.com/room/rpmetasploit) — Practical Metasploit usage.
- [ ] [TryHackMe | Hydra](https://tryhackme.com/room/hydra) — Brute-force logins on SSH, FTP, HTTP.
- [ ] [TryHackMe | Burp Suite: Repeater](https://tryhackme.com/room/burpsuiterepeater) — Intercept, modify, replay web requests.
- [ ] [TryHackMe | Introduction to OWASP ZAP](https://tryhackme.com/room/learnowaspzap) — Automated web vulnerability scanner.
- [ ] [TryHackMe | ffuf](https://tryhackme.com/room/ffuf) — Fast web fuzzer — directories, parameters, VHosts.
- [ ] [TryHackMe | TShark](https://tryhackme.com/room/tshark) — CLI packet analysis.
- [ ] [TryHackMe | Nessus](https://tryhackme.com/room/rpnessusredux) — Enterprise vulnerability scanner.
- [ ] [TryHackMe | Sublist3r](https://tryhackme.com/room/rpsublist3r) — Subdomain enumeration.
- [ ] [TryHackMe | tmux](https://tryhackme.com/room/rptmux) — Terminal multiplexer every hacker needs.
- [ ] [TryHackMe | Toolbox: Vim](https://tryhackme.com/room/toolboxvim) — Edit files on remote servers like a pro.

---

## 🟣 Phase 4 — Reconnaissance & OSINT

> **Who is this for?** Tool-ready hackers. Learn to gather intel before you touch anything.  
> **Time estimate:** ~5–7 days  
> **Goal:** Find more information about a target than they thought was public.

- [ ] [TryHackMe | Passive Reconnaissance](https://tryhackme.com/room/passiverecon) — WHOIS, DNS lookups, certificate transparency.
- [ ] [TryHackMe | Active Reconnaissance](https://tryhackme.com/room/activerecon) — Ping sweeps, port scanning, web crawling.
- [ ] [TryHackMe | OhSINT](https://tryhackme.com/room/ohsint) — Find a person's digital footprint from one image. Eye-opening.
- [ ] [TryHackMe | Google Dorking](https://tryhackme.com/room/googledorking) — Advanced Google operators to find exposed data.
- [ ] [TryHackMe | Shodan.io](https://tryhackme.com/room/shodan) — Internet-wide device search engine. Cameras, servers, everything.
- [ ] [TryHackMe | WebOSINT](https://tryhackme.com/room/webosint) — Investigating websites: ownership, history, tech stack.
- [ ] [TryHackMe | Sakura Room](https://tryhackme.com/room/sakura) — Real OSINT challenge tracking a hacker across the internet.
- [ ] [TryHackMe | Searchlight - IMINT](https://tryhackme.com/room/searchlightosint) — Image intelligence: find location from photos.
- [ ] [TryHackMe | Red Team Recon](https://tryhackme.com/room/redteamrecon) — Advanced recon from a red team perspective.
- [ ] [TryHackMe | KaffeeSec - SoMeSINT](https://tryhackme.com/room/somesint) — Social media OSINT techniques.
- [ ] [TryHackMe | Geolocating Images](https://tryhackme.com/room/geolocatingimages) — Find where a photo was taken.
- [ ] [TryHackMe | Tor](https://tryhackme.com/room/torforbeginners) — Anonymous communication + dark web fundamentals.

---

## 🔴 Phase 5 — Web Application Hacking

> **Who is this for?** Pentesters-in-training. Web apps are the #1 attack surface.  
> **Time estimate:** ~2–3 weeks  
> **Goal:** Own web applications. SQLi, XSS, LFI, SSRF, IDOR, SSTI — all of it.

### 🌐 Web Fundamentals

- [ ] [TryHackMe | Web Fundamentals](https://tryhackme.com/room/webfundamentals) — HTTP, cookies, sessions, how the web works.
- [ ] [TryHackMe | Walking An Application](https://tryhackme.com/room/walkinganapplication) — Manual recon of a web app like a real tester.
- [ ] [TryHackMe | Web Scanning](https://tryhackme.com/room/rpwebscanning) — Automated scanning workflows.
- [ ] [TryHackMe | WebAppSec 101](https://tryhackme.com/room/webappsec101) — Intro to all major web vulnerabilities.

### 🔟 OWASP Top 10

- [ ] [TryHackMe | OWASP Top 10](https://tryhackme.com/room/owasptop10) — The 10 most critical web vulnerabilities. Must-complete.
- [ ] [TryHackMe | OWASP Juice Shop](https://tryhackme.com/room/owaspjuiceshop) — Intentionally vulnerable app. Practice everything here.
- [ ] [TryHackMe | OWASP Mutillidae II](https://tryhackme.com/room/owaspmutillidae) — Another vulnerable app with more attack vectors.
- [ ] [TryHackMe | DVWA](https://tryhackme.com/room/dvwa) — Damn Vulnerable Web App. Classic practice target.
- [ ] [TryHackMe | WebGoat](https://tryhackme.com/room/webgoat) — OWASP's own training app.

### 💉 Injection Attacks

- [ ] [TryHackMe | Injection](https://tryhackme.com/room/injection) — Command, SQL, and other injection types.
- [ ] [TryHackMe | SQL Injection](https://tryhackme.com/room/sqlinjectionlm) — Manual SQLi from scratch.
- [ ] [TryHackMe | SQL Injection Lab](https://tryhackme.com/room/sqlilab) — Hands-on SQLi exercises.
- [ ] [TryHackMe | SQHell](https://tryhackme.com/room/sqhell) — Advanced SQL injection challenge.
- [ ] [TryHackMe | SSTI](https://tryhackme.com/room/learnssti) — Server-Side Template Injection. RCE through templates.

### 📂 File & Access Vulnerabilities

- [ ] [TryHackMe | LFI Basics](https://tryhackme.com/room/lfibasics) — Local File Inclusion explained.
- [ ] [TryHackMe | Inclusion](https://tryhackme.com/room/inclusion) — LFI/RFI challenge room.
- [ ] [TryHackMe | VulnNet](https://tryhackme.com/room/vulnnet1) — Full web app challenge combining multiple vulns.
- [ ] [TryHackMe | dogcat](https://tryhackme.com/room/dogcat) — LFI into RCE. Classic escalation chain.
- [ ] [TryHackMe | Juicy Details](https://tryhackme.com/room/juicydetails) — Log analysis + web exploitation.

### 🕸️ Web Challenge Rooms

- [ ] [TryHackMe | Vulnversity](https://tryhackme.com/room/vulnversity) — Recon → upload bypass → privesc. Perfect starter challenge.
- [ ] [TryHackMe | Ignite](https://tryhackme.com/room/ignite) — CMS exploitation.
- [ ] [TryHackMe | Bolt](https://tryhackme.com/room/bolt) — CMS CVE exploitation.
- [ ] [TryHackMe | NahamStore](https://tryhackme.com/room/nahamstore) — Bug bounty style web app.
- [ ] [TryHackMe | CMSpit](https://tryhackme.com/room/cmspit) — Headless CMS exploitation.
- [ ] [TryHackMe | The Marketplace](https://tryhackme.com/room/marketplace) — XSS → SSRF → privesc chain.
- [ ] [TryHackMe | Git Happens](https://tryhackme.com/room/githappens) — Exposed .git directory exploitation.
- [ ] [TryHackMe | CVE-2021-41773/42013](https://tryhackme.com/room/cve202141773) — Apache path traversal RCE.

---

## ⬆️ Phase 6 — Exploitation & Privilege Escalation

> **Who is this for?** Web hackers ready to move beyond web. Own the full system.  
> **Time estimate:** ~2 weeks  
> **Goal:** Get a shell. Escalate to root. Persist. Move laterally.

### 🐧 Linux Privilege Escalation

- [ ] [TryHackMe | Linux Privilege Escalation](https://tryhackme.com/room/linprivesc) — The definitive Linux privesc guide. Do this first.
- [ ] [TryHackMe | Linux PrivEsc](https://tryhackme.com/room/linuxprivesc) — Practice room with a live vulnerable machine.
- [ ] [TryHackMe | Linux PrivEsc Arena](https://tryhackme.com/room/linuxprivescarena) — Multi-machine arena. Grind different privesc vectors.
- [ ] [TryHackMe | Sudo Security Bypass](https://tryhackme.com/room/sudovulnsbypass) — Exploiting sudo misconfigurations.
- [ ] [TryHackMe | Sudo Buffer Overflow](https://tryhackme.com/room/sudovulnsbof) — CVE in sudo itself.
- [ ] [TryHackMe | Baron Samedit](https://tryhackme.com/room/sudovulnssamedit) — CVE-2021-3560 sudo vulnerability.
- [ ] [TryHackMe | Polkit: CVE-2021-3560](https://tryhackme.com/room/polkit) — Privilege escalation via polkit.
- [ ] [TryHackMe | Dirty Pipe: CVE-2022-0847](https://tryhackme.com/room/dirtypipe) — Kernel exploit for Linux privesc.

### 🪟 Windows Privilege Escalation

- [ ] [TryHackMe | Windows PrivEsc](https://tryhackme.com/room/windows10privesc) — Service misconfigs, registry, unquoted paths.
- [ ] [TryHackMe | Windows PrivEsc Arena](https://tryhackme.com/room/windowsprivescarena) — Multi-vector Windows escalation practice.
- [ ] [TryHackMe | DLL Hijacking](https://tryhackme.com/room/dllhijacking) — Classic Windows attack vector.

### 🕸️ Post-Exploitation

- [ ] [TryHackMe | Post-Exploitation Basics](https://tryhackme.com/room/postexploit) — What to do after you get a shell: persistence, loot.
- [ ] [TryHackMe | Linux Backdoors](https://tryhackme.com/room/linuxbackdoors) — How attackers stay in after breaching.

### 🏰 Active Directory Attacks

- [ ] [TryHackMe | Attacktive Directory](https://tryhackme.com/room/attacktivedirectory) — Kerberoasting, AS-REP roasting, pass-the-hash. The real thing.
- [ ] [TryHackMe | Post-Exploitation Basics](https://tryhackme.com/room/postexploit) — Mimikatz, BloodHound, AD enumeration.
- [ ] [TryHackMe | VulnNet: Roasted](https://tryhackme.com/room/vulnnetroasted) — AD challenge with real attack chains.
- [ ] [TryHackMe | VulnNet: Active](https://tryhackme.com/room/vulnnetactive) — Active Directory + web combined.
- [ ] [TryHackMe | Blue](https://tryhackme.com/room/blue) — EternalBlue (MS17-010). The NSA exploit made famous by WannaCry.
- [ ] [TryHackMe | Anthem](https://tryhackme.com/room/anthem) — Windows enumeration and recon.

---

## 🛡️ Phase 7 — Defense Track (SOC, DFIR, Forensics)

> **Who is this for?** Anyone targeting a Blue Team / SOC / DFIR career path.  
> **Time estimate:** ~2 weeks  
> **Goal:** Think like a defender. Hunt threats. Investigate incidents. Analyze malware.

### 📡 SOC Fundamentals

- [ ] [TryHackMe | SOC Fundamentals](https://tryhackme.com/room/socfundamentals) — What a SOC is, tiers, alert triage.
- [ ] [TryHackMe | Intro to Defensive Security](https://tryhackme.com/room/introtodefensivesecurity) — Blue team overview and toolset.
- [ ] [TryHackMe | MITRE](https://tryhackme.com/room/mitre) — ATT&CK framework. How attackers are mapped and tracked.
- [ ] [TryHackMe | Splunk](https://tryhackme.com/room/bpsplunk) — The most-used SIEM in enterprise SOCs.
- [ ] [TryHackMe | Pyramid Of Pain](https://tryhackme.com/room/pyramidofpainax) — Understanding what makes threat intel actionable.

### 🔬 Digital Forensics (DFIR)

- [ ] [TryHackMe | Intro to Digital Forensics](https://tryhackme.com/room/introdigitalforensics) — Evidence collection, chain of custody.
- [ ] [TryHackMe | Linux Server Forensics](https://tryhackme.com/room/linuxserverforensics) — Investigate a compromised Linux server.
- [ ] [TryHackMe | Forensics](https://tryhackme.com/room/forensics) — File and image forensics techniques.
- [ ] [TryHackMe | Memory Forensics](https://tryhackme.com/room/memoryforensics) — Extract passwords, processes, secrets from RAM dumps.
- [ ] [TryHackMe | Volatility](https://tryhackme.com/room/bpvolatility) — Industry-standard memory analysis framework.
- [ ] [TryHackMe | Disk Analysis & Autopsy](https://tryhackme.com/room/autopsy2ze0) — Disk forensics with Autopsy tool.

### 🦠 Malware Analysis

- [ ] [TryHackMe | History of Malware](https://tryhackme.com/room/historyofmalware) — From the first virus to modern APTs.
- [ ] [TryHackMe | MAL: Malware Introductory](https://tryhackme.com/room/malmalintroductory) — Static vs dynamic analysis, sandboxes.
- [ ] [TryHackMe | Basic Malware RE](https://tryhackme.com/room/basicmalwarere) — Reversing actual malware samples.
- [ ] [TryHackMe | MAL: Researching](https://tryhackme.com/room/malresearching) — Open-source intelligence on malware samples.
- [ ] [TryHackMe | Mobile Malware Analysis](https://tryhackme.com/room/mma) — Android APK malware investigation.
- [ ] [TryHackMe | Carnage](https://tryhackme.com/room/c2carnage) — C2 traffic analysis in PCAP files.
- [ ] [TryHackMe | REvil Corp](https://tryhackme.com/room/revilcorp) — Investigate a real ransomware incident.
- [ ] [TryHackMe | Conti](https://tryhackme.com/room/contiransomwarehgh) — Analyze the Conti ransomware attack.
- [ ] [TryHackMe | Solar, exploiting log4j](https://tryhackme.com/room/solar) — Log4Shell CVE exploitation and defense.

### 📦 PCAP & Network Analysis

- [ ] [TryHackMe | h4cked](https://tryhackme.com/room/h4cked) — Investigate a compromise through packet captures.
- [ ] [TryHackMe | Overpass 2 - Hacked](https://tryhackme.com/room/overpass2hacked) — Forensics on a hacked server. Trace every step.

---

## ⚡ Phase 8 — Advanced Specializations

> **Who is this for?** Pick your lane. Reverse engineering, buffer overflows, Wifi, steganography.  
> **Time estimate:** 3–6 weeks depending on focus  
> **Goal:** Go deep in your chosen specialty.

### 🔄 Reverse Engineering

- [ ] [TryHackMe | Intro to x86-64](https://tryhackme.com/room/introtox8664) — Assembly language basics. This is where RE starts.
- [ ] [TryHackMe | Windows x64 Assembly](https://tryhackme.com/room/win64assembly) — Windows-specific assembly.
- [ ] [TryHackMe | Reverse Engineering](https://tryhackme.com/room/reverseengineering) — Binary analysis concepts.
- [ ] [TryHackMe | Reversing ELF](https://tryhackme.com/room/reverselfiles) — Reverse engineer Linux binaries.
- [ ] [TryHackMe | JVM Reverse Engineering](https://tryhackme.com/room/jvmreverseengineering) — Java bytecode RE.
- [ ] [TryHackMe | CC: Radare2](https://tryhackme.com/room/ccradare2) — Open-source RE framework.
- [ ] [TryHackMe | CC: Ghidra](https://tryhackme.com/room/ccghidra) — NSA's free decompiler. Industry standard.
- [ ] [TryHackMe | Classic Passwd](https://tryhackme.com/room/classicpasswd) — Binary RE challenge.
- [ ] [TryHackMe | REloaded](https://tryhackme.com/room/reloaded) — Advanced binary challenges.
- [ ] [TryHackMe | Binary Heaven](https://tryhackme.com/room/binaryheaven) — Binary exploitation warm-up.
- [ ] [TryHackMe | Linux Function Hooking](https://tryhackme.com/room/linuxfunctionhooking) — Hook functions at runtime. Next-level.

### 💥 Buffer Overflow

- [ ] [TryHackMe | Buffer Overflow Prep](https://tryhackme.com/room/bufferoverflowprep) — The definitive OSCP buffer overflow training room.
- [ ] [TryHackMe | Intro To Pwntools](https://tryhackme.com/room/intropwntools) — Python library for exploit dev.
- [ ] [TryHackMe | Gatekeeper](https://tryhackme.com/room/gatekeeper) — Windows buffer overflow CTF.
- [ ] [TryHackMe | Brainpan 1](https://tryhackme.com/room/brainpan) — OSCP-style buffer overflow machine.

### 📶 Wi-Fi Hacking

- [ ] [TryHackMe | Wifi Hacking 101](https://tryhackme.com/room/wifihacking101) — WPA2 handshake capture + cracking. Aircrack-ng.

### 🕵️ Steganography

- [ ] [TryHackMe | CC: Steganography](https://tryhackme.com/room/ccstego) — Hide/find data in images and audio.
- [ ] [TryHackMe | Musical Stego](https://tryhackme.com/room/musicalstego) — Audio steganography.
- [ ] [TryHackMe | Madness](https://tryhackme.com/room/madness) — Image stego challenge.
- [ ] [TryHackMe | Cicada-3301 Vol:1](https://tryhackme.com/room/cicada3301vol1) — Classic ARG-style crypto+stego puzzle.

### 📱 Mobile Security

- [ ] [TryHackMe | Android Hacking 101](https://tryhackme.com/room/androidhacking101) — APK analysis, ADB, Android attack surface.

### 🌐 IoT & ICS Security

- [ ] [TryHackMe | Intro to IoT Pentesting](https://tryhackme.com/room/iotintro) — Attack surface of smart devices.
- [ ] [TryHackMe | Attacking ICS Plant #1](https://tryhackme.com/room/attackingics1) — Industrial control system attacks.
- [ ] [TryHackMe | Attacking ICS Plant #2](https://tryhackme.com/room/attackingics2) — Advanced ICS exploitation.
- [ ] [TryHackMe | Printer Hacking 101](https://tryhackme.com/room/printerhacking101) — Network printers are a goldmine. IPP, PRET.

### 🔍 Investigating Windows

- [ ] [TryHackMe | Investigating Windows](https://tryhackme.com/room/investigatingwindows) — Analyze a compromised Windows machine.
- [ ] [TryHackMe | Investigating Windows 2.0](https://tryhackme.com/room/investigatingwindows2) — Harder investigation scenarios.
- [ ] [TryHackMe | Investigating Windows 3.x](https://tryhackme.com/room/investigatingwindows3) — Advanced Windows incident response.
- [ ] [TryHackMe | OverlayFS - CVE-2021-3493](https://tryhackme.com/room/overlayfs) — Linux kernel privilege escalation via CVE.
- [ ] [TryHackMe | Wordpress: CVE-2021-29447](https://tryhackme.com/room/wordpresscve202129447) — XML injection in WordPress.

---

## 🏁 Phase 9 — CTF Practice

> **Grind these. This is where it all comes together.**  
> Start Easy. When Easy feels boring, go Medium. Hard is OSCP-level.

### 🟢 Easy CTFs

- [ ] [TryHackMe | Pickle Rick](https://tryhackme.com/room/picklerick) — Web + Linux. Fun starter.
- [ ] [TryHackMe | RootMe](https://tryhackme.com/room/rrootme) — Upload bypass → privesc. Classic.
- [ ] [TryHackMe | Vulnversity](https://tryhackme.com/room/vulnversity) — Full recon-to-root chain.
- [ ] [TryHackMe | Simple CTF](https://tryhackme.com/room/easyctf) — CMS exploit + sudo privesc.
- [ ] [TryHackMe | Bounty Hacker](https://tryhackme.com/room/cowboyhacker) — FTP enumeration + brute force.
- [ ] [TryHackMe | LazyAdmin](https://tryhackme.com/room/lazyadmin) — SweetRice CMS exploitation.
- [ ] [TryHackMe | Kenobi](https://tryhackme.com/room/kenobi) — Samba + ProFTPD + SUID.
- [ ] [TryHackMe | GamingServer](https://tryhackme.com/room/gamingserver) — Easy recon + LXD privesc.
- [ ] [TryHackMe | Brooklyn Nine Nine](https://tryhackme.com/room/brooklynninenine) — Steganography + SSH + sudo bypass.
- [ ] [TryHackMe | Ice](https://tryhackme.com/room/ice) — Windows exploitation with Metasploit.
- [ ] [TryHackMe | Blaster](https://tryhackme.com/room/blaster) — Windows IIS + WinPEAS.
- [ ] [TryHackMe | Startup](https://tryhackme.com/room/startup) — Upload exploit + wireshark + privesc.
- [ ] [TryHackMe | Archangel](https://tryhackme.com/room/archangel) — LFI + cron job abuse.
- [ ] [TryHackMe | Easy Peasy](https://tryhackme.com/room/easypeasyctf) — Multiple vuln types stacked.
- [ ] [TryHackMe | Year of the Rabbit](https://tryhackme.com/room/yearoftherabbit) — FTP + Brainfuck decoding.
- [ ] [TryHackMe | Wgel CTF](https://tryhackme.com/room/wgelctf) — Apache misconfig + sudo privesc.
- [ ] [TryHackMe | Lian_Yu](https://tryhackme.com/room/lianyu) — Arrow TV show themed. Stego + SSH.
- [ ] [TryHackMe | Overpass](https://tryhackme.com/room/overpass) — Password manager flaw + cron exploit.
- [ ] [TryHackMe | c4ptur3-th3-fl4g](https://tryhackme.com/room/c4ptur3th3fl4g) — Encoding + cipher challenges.
- [ ] [TryHackMe | tomghost](https://tryhackme.com/room/tomghost) — Ghostcat (CVE-2020-1938) Apache Tomcat.
- [ ] [TryHackMe | Mustacchio](https://tryhackme.com/room/mustacchio) — XXE injection.
- [ ] [TryHackMe | All in One](https://tryhackme.com/room/allinonemj) — WordPress + multiple attack paths.
- [ ] [TryHackMe | Chocolate Factory](https://tryhackme.com/room/chocolatefactory) — Willy Wonka themed. Fun and real.
- [ ] [TryHackMe | Fowsniff CTF](https://tryhackme.com/room/ctf) — OSINT + SSH + mail + motd.
- [ ] [TryHackMe | Couch](https://tryhackme.com/room/couch) — CouchDB exploitation.
- [ ] [TryHackMe | Source](https://tryhackme.com/room/source) — Webmin CVE exploitation.
- [ ] [TryHackMe | Cat Pictures](https://tryhackme.com/room/catpictures) — Port knocking + Docker escape.
- [ ] [TryHackMe | Gotta Catch'em All!](https://tryhackme.com/room/pokemon) — Pokémon themed Linux enum.
- [ ] [TryHackMe | ColddBox: Easy](https://tryhackme.com/room/colddboxeasy) — WordPress + WPScan.
- [ ] [TryHackMe | Chill Hack](https://tryhackme.com/room/chillhack) — Command injection + Docker privesc.
- [ ] [TryHackMe | GLITCH](https://tryhackme.com/room/glitch) — API fuzzing + Node.js exploit.
- [ ] [TryHackMe | Badbyte](https://tryhackme.com/room/badbyte) — SSH tunneling + port forwarding.
- [ ] [TryHackMe | Team](https://tryhackme.com/room/teamcw) — VHost + LFI + sudo abuse.
- [ ] [TryHackMe | Cyborg](https://tryhackme.com/room/cyborgt8) — Borg backup + SSH.
- [ ] [TryHackMe | CTF Collection Vol.1](https://tryhackme.com/room/ctfcollectionvol1) — Encoding, steganography, basic exploitation.

### 🟡 Medium CTFs

- [ ] [TryHackMe | Mr Robot CTF](https://tryhackme.com/room/mrrobot) — Based on the show. Wordlists, PHP shell, SUID.
- [ ] [TryHackMe | Daily Bugle](https://tryhackme.com/room/dailybugle) — Joomla SQLi + PHP upload + Yum privesc.
- [ ] [TryHackMe | Wonderland](https://tryhackme.com/room/wonderland) — Alice themed. Path hijacking + capabilities.
- [ ] [TryHackMe | Overpass 2 - Hacked](https://tryhackme.com/room/overpass2hacked) — Forensics of a compromised server.
- [ ] [TryHackMe | Overpass 3 - Hosting](https://tryhackme.com/room/overpass3hosting) — NFS + SSH key + web shell.
- [ ] [TryHackMe | The Marketplace](https://tryhackme.com/room/marketplace) — XSS → SSRF → SQL injection.
- [ ] [TryHackMe | Anonymous](https://tryhackme.com/room/anonymous) — FTP anonymous + cron job + SUID.
- [ ] [TryHackMe | Blog](https://tryhackme.com/room/blog) — WordPress + SUID wp-cli exploit.
- [ ] [TryHackMe | dogcat](https://tryhackme.com/room/dogcat) — PHP LFI + log poisoning + Docker escape.
- [ ] [TryHackMe | GoldenEye](https://tryhackme.com/room/goldeneye) — POP3 + Moodle RCE.
- [ ] [TryHackMe | CMesS](https://tryhackme.com/room/cmess) — Gila CMS + wildcard injection.
- [ ] [TryHackMe | ConvertMyVideo](https://tryhackme.com/room/convertmyvideo) — Command injection + cron.
- [ ] [TryHackMe | hackerNote](https://tryhackme.com/room/hackernote) — Username enum + brute force + GTFOBins.
- [ ] [TryHackMe | Debug](https://tryhackme.com/room/debug) — PHP deserialization.
- [ ] [TryHackMe | Bookstore](https://tryhackme.com/room/bookstoreoc) — REST API fuzzing + SSRF.
- [ ] [TryHackMe | Road](https://tryhackme.com/room/road) — Web + MongoDB + sudo.
- [ ] [TryHackMe | Watcher](https://tryhackme.com/room/watcher) — LFI + FTP + Python cron.
- [ ] [TryHackMe | Wekor](https://tryhackme.com/room/wekorra) — WordPress + SQLi + Rabbit.
- [ ] [TryHackMe | CTF Collection Vol.2](https://tryhackme.com/room/ctfcollectionvol2) — Advanced stego, crypto, exploitation.
- [ ] [TryHackMe | CMSpit](https://tryhackme.com/room/cmspit) — Cockpit CMS CVE.
- [ ] [TryHackMe | VulnNet: Node](https://tryhackme.com/room/vulnnetnode) — Node.js deserialization.
- [ ] [TryHackMe | VulnNet: Internal](https://tryhackme.com/room/vulnnetinternal) — SMB + Redis + Rsync.
- [ ] [TryHackMe | Inferno](https://tryhackme.com/room/inferno) — Dante-themed. Multi-vector.
- [ ] [TryHackMe | Revenge](https://tryhackme.com/room/revenge) — SQL injection + service exploit.
- [ ] [TryHackMe | SQHell](https://tryhackme.com/room/sqhell) — All types of SQLi in one room.
- [ ] [TryHackMe | Mnemonic](https://tryhackme.com/room/mnemonic) — FTP + brute force + Python jail.
- [ ] [TryHackMe | Startup](https://tryhackme.com/room/startup) — Upload + wireshark + privesc.
- [ ] [TryHackMe | Biohazard](https://tryhackme.com/room/biohazard) — Resident Evil themed CTF.
- [ ] [TryHackMe | Undiscovered](https://tryhackme.com/room/undiscoveredup) — VHost enum + RFI.
- [ ] [TryHackMe | broker](https://tryhackme.com/room/broker) — ActiveMQ CVE exploitation.

### 🔴 Hard CTFs

- [ ] [TryHackMe | Internal](https://tryhackme.com/room/internal) — OSCP-style. WordPress + Jenkins + port forward.
- [ ] [TryHackMe | Daily Bugle](https://tryhackme.com/room/dailybugle) — Joomla attack chain.
- [ ] [TryHackMe | Retro](https://tryhackme.com/room/retro) — Windows + CVE exploit.
- [ ] [TryHackMe | Year of the Fox](https://tryhackme.com/room/yotf) — Command injection behind auth.
- [ ] [TryHackMe | Ra](https://tryhackme.com/room/ra) — Windows AD full attack chain.
- [ ] [TryHackMe | Year of the Pig](https://tryhackme.com/room/yearofthepig) — Custom webapp + MySQL + sudo.
- [ ] [TryHackMe | Fusion Corp](https://tryhackme.com/room/fusioncorp) — AD environment.
- [ ] [TryHackMe | Year of the Jellyfish](https://tryhackme.com/room/yearofthejellyfish) — Remote services + SSH forward.
- [ ] [TryHackMe | CherryBlossom](https://tryhackme.com/room/cherryblossom) — Custom web + DB.
- [ ] [TryHackMe | Year of the Owl](https://tryhackme.com/room/yearoftheowl) — Windows + AD.
- [ ] [TryHackMe | Uranium CTF](https://tryhackme.com/room/uranium) — Email + IMAP + mail exploit.
- [ ] [TryHackMe | Shaker](https://tryhackme.com/room/shaker) — Hard reverse engineering.
- [ ] [TryHackMe | M4tr1x: Exit Denied](https://tryhackme.com/room/m4tr1xexitdenied) — Matrix-themed advanced machine.
- [ ] [TryHackMe | Crocc Crew](https://tryhackme.com/room/crocccrew) — Windows + AD full chain.
- [ ] [TryHackMe | Different CTF](https://tryhackme.com/room/adana) — Full Linux attack chain.
- [ ] [TryHackMe | VulnNet: dotjar](https://tryhackme.com/room/vulnnetdotjar) — Ghostcat + Java + sudo.

---

## 🎄 Bonus — Special Events

> **Advent of Cyber is the best free cybersecurity event on the internet. Every December.**

- [ ] [TryHackMe | Advent of Cyber 1 [2019]](https://tryhackme.com/room/25daysofchristmas) — Beginner. 25 days of hacking challenges.
- [ ] [TryHackMe | Advent of Cyber 2 [2020]](https://tryhackme.com/room/adventofcyber2) — Web, networking, scripting, RE.
- [ ] [TryHackMe | Advent of Cyber 3 (2021)](https://tryhackme.com/room/adventofcyber3) — Blue team + red team tracks.
- [ ] [TryHackMe | Advent of Cyber 2022](https://tryhackme.com/room/adventofcyber4) — Smart contracts, log analysis, ML.
- [ ] [TryHackMe | 25 Days of Cyber Security](https://tryhackme.com/room/learncyberin25days) — Alternative beginner advent.
- [ ] [TryHackMe | Cyber Scotland 2021](https://tryhackme.com/room/cyberweek2021) — Mini event rooms.

---

## 🎯 Career Path Suggestions

After completing this roadmap, here's where to aim based on what lit you up:

| You enjoyed... | Career Path | Next Certs |
|---|---|---|
| Web hacking, logic flaws | Bug Bounty / App Pentester | eJPT → OSCP → BSCP |
| Metasploit, PrivEsc, AD | Red Teamer / Pentester | eJPT → OSCP → CRTO |
| Forensics, DFIR, Malware | SOC Analyst / Incident Responder | Security+ → CySA+ → GCFE |
| Traffic analysis, detection | Threat Hunter / Blue Team | CompTIA Security+ → GCIH |
| Assembly, RE, BoF | Exploit Developer / Malware Analyst | GREM → OSCE3 |

---

## 🛠️ Tools You'll Use Most

| Tool | What It Does | Install |
|---|---|---|
| Nmap | Network scanner | `sudo apt install nmap` |
| Burp Suite | Web proxy & interceptor | [portswigger.net](https://portswigger.net/burp) |
| Metasploit | Exploitation framework | `sudo apt install metasploit-framework` |
| Hydra | Password brute-forcer | `sudo apt install hydra` |
| Gobuster / ffuf | Directory/subdomain fuzzer | `sudo apt install gobuster` |
| Wireshark / TShark | Packet analyzer | `sudo apt install wireshark` |
| SQLmap | SQL injection automation | `sudo apt install sqlmap` |
| John / Hashcat | Hash cracker | `sudo apt install john` |
| Volatility | Memory forensics | [github.com/volatilityfoundation](https://github.com/volatilityfoundation/volatility3) |
| Ghidra | Reverse engineering | [ghidra-sre.org](https://ghidra-sre.org) |

---

## 📌 Maintainer

> **This repository is maintained by [Nistal Talson | NISTALTALSON](https://github.com/NISTALTALSON)**  
> BCA Cybersecurity Student | Ethical Hacker in Training | Kerala, India  
>  
> Connect: [GitHub](https://github.com/NISTALTALSON) • [LinkedIn](https://www.linkedin.com/in/nistaltalson/)

---

## 🤝 Contributing

Found a room that should be here? Submit a PR:

1. Fork this repo
2. Add the room with: name, link, and a one-line description
3. Verify it's 100% free (no subscriber lock)
4. Submit a pull request

All contributions are credited.

---

## ⭐ Star This Repo

If this roadmap helped you, **star it**. It helps other learners find it.

> *"You don't need expensive courses. You need discipline and the right path. This is the path."*

---

<div align="center">

**Happy Hacking. Stay Ethical. Never Stop Learning.**

`hack the planet 🌍`

</div>
