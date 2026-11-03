<div align="center">

# 🔐 Free TryHackMe Hacking Roadmap
### 471 Free Rooms. 11 Phases. Zero Paywalls. One Path From Zero to Hacker.

[![Stars](https://img.shields.io/github/stars/NISTALTALSON/free-tryhackme-rooms?style=for-the-badge&logo=github&color=gold)](https://github.com/NISTALTALSON/free-tryhackme-rooms/stargazers)
[![Forks](https://img.shields.io/github/forks/NISTALTALSON/free-tryhackme-rooms?style=for-the-badge&logo=github)](https://github.com/NISTALTALSON/free-tryhackme-rooms/fork)
[![Rooms](https://img.shields.io/badge/Free%20Rooms-471-brightgreen?style=for-the-badge)](#-table-of-contents)
[![Last Commit](https://img.shields.io/github/last-commit/NISTALTALSON/free-tryhackme-rooms?style=for-the-badge)](https://github.com/NISTALTALSON/free-tryhackme-rooms/commits/main)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-ff69b4?style=for-the-badge)](#-contributing)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

> **"Everyone deserves to learn hacking. This roadmap is your cheat code."**

**⭐ Star this repo so you can find it later — then start at [Phase 0](#-phase-0--start-here).**

</div>

---

## 🧠 Why This Exists

Most free TryHackMe lists are flat category dumps. This one is a **structured roadmap**: every phase builds on the last, has a time estimate and a goal, and ends in a career path with next certs.

- 🗺️ **Phased path** — Phase 0 to Phase 10, beginner to specialist
- ⏱️ **Time estimates** — know what you're signing up for
- ✅ **Checklists** — fork it and tick rooms off
- 🧹 **Deduplicated** — each room appears once
- 🚫 **Premium watch** — rooms that left the free tier are listed [below](#-no-longer-free)
- 🎯 **Career map** — red team, blue team, bug bounty, RE

No subscription. No courses to buy. Just grind.

---

## 🧭 Pick Your Path

| I want to be... | Go through | Time |
|---|---|---|
| Total beginner | Phase 0 → 1 → 2 | ~3 weeks |
| Pentester / Red Team | Phase 3 → 4 → 5 → 6 | ~2 months |
| Bug bounty hunter | Phase 3 → 5 (all of it) → 9 Easy/Medium | ~6 weeks |
| SOC analyst / Blue Team | Phase 1 → 7 → 9 forensics-style rooms | ~6 weeks |
| Reverse engineer / malware analyst | Phase 2 → 8 (RE + BoF) → 7 malware | ~2 months |
| Cloud / DevSecOps | Phase 1 → 3 → 10 | ~3 weeks |

## 📅 12-Week Plan (1–2 hours a day)

| Weeks | Focus |
|---|---|
| 1–2 | Phases 0–1: platform, Linux, Windows, networking |
| 3 | Phase 2: scripting and crypto |
| 4 | Phase 3: Nmap, Burp, Metasploit, Hydra |
| 5 | Phase 4: recon and OSINT |
| 6–7 | Phase 5: web hacking and OWASP |
| 8–9 | Phase 6: privesc and Active Directory |
| 10 | Phase 7 or 10: pick blue team or cloud |
| 11–12 | Phase 9: CTFs — Easy, then Medium |

---

## 📋 Table of Contents

| Phase | Rooms |
|---|---|
| [Phase 0 — Start Here](#-phase-0--start-here) | 8 |
| [Phase 1 — Core Foundations](#-phase-1--core-foundations) | 22 |
| [Phase 2 — Scripting & Cryptography](#-phase-2--scripting--cryptography) | 16 |
| [Phase 3 — Hacking Methodology & Tools](#-phase-3--hacking-methodology--tools) | 28 |
| [Phase 4 — Reconnaissance & OSINT](#-phase-4--reconnaissance--osint) | 12 |
| [Phase 5 — Web Application Hacking](#-phase-5--web-application-hacking) | 41 |
| [Phase 6 — Exploitation & Privilege Escalation](#-phase-6--exploitation--privilege-escalation) | 26 |
| [Phase 7 — Defense Track (SOC, DFIR, Forensics)](#-phase-7--defense-track-soc-dfir-forensics) | 52 |
| [Phase 8 — Advanced Specializations](#-phase-8--advanced-specializations) | 47 |
| [Phase 9 — CTF Practice](#-phase-9--ctf-practice) | 202 |
| [Phase 10 — Cloud, Containers & DevSecOps](#-phase-10--cloud-containers--devsecops) | 7 |
| [Bonus — Special Events](#-bonus--special-events) | 10 |
| **Total** | **471** |

> ⚠️ **Note:** TryHackMe moves rooms behind the paywall from time to time. If a room asks for a subscription, skip it and [tell us](https://github.com/NISTALTALSON/free-tryhackme-rooms/issues).

---

## ☑️ Progress Tracker

Fork this repo and tick the checkboxes as you go. Share your progress with `#FreeTHMRoadmap`.

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


### 🆕 More Foundations

- [ ] [TryHackMe | Linux File System Analysis](https://tryhackme.com/room/linuxfilesystemanalysis) — Understand where evidence and misconfigs hide on Linux.
- [ ] [TryHackMe | Linux Process Analysis](https://tryhackme.com/room/linuxprocessanalysis) — Inspect running processes like an analyst.
- [ ] [TryHackMe | Intro to Logs](https://tryhackme.com/room/introtologs) — Why logs matter and how to read them.
- [ ] [TryHackMe | Hosted Hypervisors](https://tryhackme.com/room/hostedhypervisors) — Virtualisation basics for your home lab.
- [ ] [TryHackMe | Hypervisor Internals](https://tryhackme.com/room/hypervisorinternals) — How hypervisors work under the hood.
- [ ] [TryHackMe | How Websites Work](https://tryhackme.com/room/howwebsiteswork) — Front-end vs back-end, the base for web hacking.
- [ ] [TryHackMe | Careers in Cyber](https://tryhackme.com/room/careersincyber) — Pick a lane before you grind.
- [ ] [TryHackMe | Security Principles](https://tryhackme.com/room/securityprinciples) — Core security concepts every beginner needs.

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


### 🔐 More Crypto

- [ ] [TryHackMe | Breaking RSA](https://tryhackme.com/room/breakrsa) — Attack weak RSA implementations.
- [ ] [TryHackMe | Introduction to Cryptography](https://tryhackme.com/room/cryptographyintro) — Clean intro before the heavy rooms.
- [ ] [TryHackMe | Introduction to CryptOps](https://tryhackme.com/room/introductiontocryptops) — Crypto operations in practice.

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


### 🆕 More Tools & Methodology

- [ ] [TryHackMe | Burp Suite: The Basics](https://tryhackme.com/room/burpsuitebasics) — Set up and drive Burp Suite. Do this before Repeater.
- [ ] [TryHackMe | Content Discovery](https://tryhackme.com/room/contentdiscovery) — Find hidden files and directories on web apps.
- [ ] [TryHackMe | Snyk Open Source](https://tryhackme.com/room/snykopensource) — Find vulnerable dependencies.
- [ ] [TryHackMe | Snyk Code](https://tryhackme.com/room/snykcode) — Static analysis for your own code.
- [ ] [TryHackMe | Phishing: HiddenEye](https://tryhackme.com/room/phishinghiddeneye) — See how phishing kits work (for defence).
- [ ] [TryHackMe | REmux The Tmux](https://tryhackme.com/room/tmuxremux) — More tmux practice.
- [ ] [TryHackMe | Offensive Security Intro](https://tryhackme.com/room/offensivesecurityintro) — Hack your first machine.
- [ ] [TryHackMe | Defensive Security Intro](https://tryhackme.com/room/defensivesecurityintro) — Meet the blue team side.

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


### 🆕 Modern Web Attacks

- [ ] [TryHackMe | OWASP Top 10 - 2021](https://tryhackme.com/room/owasptop102021) — Updated Top 10 with newer categories.
- [ ] [TryHackMe | Web Application Security](https://tryhackme.com/room/introwebapplicationsecurity) — Structured web security intro.
- [ ] [TryHackMe | XSS](https://tryhackme.com/room/axss) — Reflected, stored and DOM XSS.
- [ ] [TryHackMe | CSRF](https://tryhackme.com/room/csrfV2) — Cross-site request forgery end to end.
- [ ] [TryHackMe | NoSQL Injection](https://tryhackme.com/room/nosqlinjectiontutorial) — Break MongoDB-style backends.
- [ ] [TryHackMe | Advanced SQL Injection](https://tryhackme.com/room/advancedsqlinjection) — Beyond UNION: blind and out-of-band.
- [ ] [TryHackMe | File Inclusion, Path Traversal](https://tryhackme.com/room/filepathtraversal) — LFI, RFI and traversal in one room.
- [ ] [TryHackMe | SSRF](https://tryhackme.com/room/ssrfhr) — Make servers fetch what they should not.
- [ ] [TryHackMe | OWASP Broken Access Control](https://tryhackme.com/room/owaspbrokenaccesscontrol) — IDOR and privilege flaws.
- [ ] [TryHackMe | HTTP Request Smuggling](https://tryhackme.com/room/httprequestsmuggling) — Desync front-end and back-end.
- [ ] [TryHackMe | HTTP/2 Request Smuggling](https://tryhackme.com/room/http2requestsmuggling) — Smuggling over HTTP/2.
- [ ] [TryHackMe | Race Conditions](https://tryhackme.com/room/raceconditions) — Exploit timing bugs.
- [ ] [TryHackMe | Microservices Architectures](https://tryhackme.com/room/microservicearchitectures) — Understand modern app attack surface.
- [ ] [TryHackMe | APIWizards Breach](https://tryhackme.com/room/apiwizardsbreach) — API-focused breach scenario.

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
- [ ] [TryHackMe | VulnNet: Roasted](https://tryhackme.com/room/vulnnetroasted) — AD challenge with real attack chains.
- [ ] [TryHackMe | VulnNet: Active](https://tryhackme.com/room/vulnnetactive) — Active Directory + web combined.
- [ ] [TryHackMe | Blue](https://tryhackme.com/room/blue) — EternalBlue (MS17-010). The NSA exploit made famous by WannaCry.
- [ ] [TryHackMe | Anthem](https://tryhackme.com/room/anthem) — Windows enumeration and recon.


### 🆕 More Active Directory & Windows

- [ ] [TryHackMe | Active Directory Basics](https://tryhackme.com/room/winadbasics) — Learn AD before you attack it.
- [ ] [TryHackMe | Breaching Active Directory](https://tryhackme.com/room/breachingad) — Get your first AD foothold.
- [ ] [TryHackMe | USTOUN](https://tryhackme.com/room/ustoun) — AD challenge machine.
- [ ] [TryHackMe | Enterprise](https://tryhackme.com/room/enterprise) — Full AD enterprise-style box.
- [ ] [TryHackMe | RazorBlack](https://tryhackme.com/room/raz0rblack) — AD enumeration and roasting.
- [ ] [TryHackMe | Blueprint](https://tryhackme.com/room/blueprint) — Windows web app to SYSTEM.
- [ ] [TryHackMe | Iron Corp](https://tryhackme.com/room/ironcorp) — Hard Windows/AD chain.
- [ ] [TryHackMe | Relevant](https://tryhackme.com/room/relevant) — OSCP-style Windows box.

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


### 🆕 More Blue Team, SOC & Threat Hunting

- [ ] [TryHackMe | Junior Security Analyst Intro](https://tryhackme.com/room/jrsecanalystintrouxo) — What a junior SOC analyst does day to day.
- [ ] [TryHackMe | Threat Intelligence for SOC](https://tryhackme.com/room/threatintelligenceforsoc) — Use CTI in alert triage.
- [ ] [TryHackMe | Splunk: Exploring SPL](https://tryhackme.com/room/splunkexploringspl) — Write Splunk searches.
- [ ] [TryHackMe | ParrotPost: Phishing Analysis](https://tryhackme.com/room/parrotpost) — Analyse phishing emails.
- [ ] [TryHackMe | Intro to Detection Engineering](https://tryhackme.com/room/introtodetectionengineering) — Turn threats into detections.
- [ ] [TryHackMe | Threat Hunting: Introduction](https://tryhackme.com/room/introductiontothreathunting) — Hypothesis-driven hunting.
- [ ] [TryHackMe | Threat Hunting: Foothold](https://tryhackme.com/room/threathuntingfoothold) — Hunt for initial access.
- [ ] [TryHackMe | Intro to Threat Emulation](https://tryhackme.com/room/threatemulationintro) — Emulate adversaries safely.
- [ ] [TryHackMe | Unified Kill Chain](https://tryhackme.com/room/unifiedkillchain) — Map attacks end to end.
- [ ] [TryHackMe | Cyber Kill Chain](https://tryhackme.com/room/cyberkillchainzmt) — Lockheed model explained.
- [ ] [TryHackMe | IR Playbooks](https://tryhackme.com/room/irplaybooks) — Incident response playbooks.
- [ ] [TryHackMe | IR Philosophy and Ethics](https://tryhackme.com/room/irphilosophyethics) — The mindset behind IR.
- [ ] [TryHackMe | Legal Considerations in DFIR](https://tryhackme.com/room/dfirprocesslegalconsiderations) — Evidence and legality.
- [ ] [TryHackMe | Identification & Scoping](https://tryhackme.com/room/identificationandscoping) — Scope an incident.
- [ ] [TryHackMe | Forensic Imaging](https://tryhackme.com/room/forensicimaging) — Acquire disk images properly.
- [ ] [TryHackMe | Intro to Cold System Forensics](https://tryhackme.com/room/introtocoldsystemforensics) — Forensics on powered-off systems.
- [ ] [TryHackMe | Windows Applications Forensics](https://tryhackme.com/room/windowsapplications) — Artefacts from Windows apps.
- [ ] [TryHackMe | Linux Incident Surface](https://tryhackme.com/room/linuxincidentsurface) — Where to look on a compromised Linux box.
- [ ] [TryHackMe | Windows Incident Surface](https://tryhackme.com/room/winincidentsurface) — Where to look on a compromised Windows box.
- [ ] [TryHackMe | Registry Persistence Detection](https://tryhackme.com/room/registrypersistencedetection) — Catch registry persistence.
- [ ] [TryHackMe | Servidae: Log Analysis in ELK](https://tryhackme.com/room/servidae) — Hunt through logs in ELK.
- [ ] [TryHackMe | Digital Forensics Case B4DM755](https://tryhackme.com/room/caseb4dm755) — Full forensic case.
- [ ] [TryHackMe | Eviction](https://tryhackme.com/room/eviction) — Threat intel investigation.
- [ ] [TryHackMe | Threat Intel & Containment](https://tryhackme.com/room/intelcreationandcontainment) — Create intel and contain threats.
- [ ] [TryHackMe | Hunt Me I: Payment Collectors](https://tryhackme.com/room/paymentcollectors) — Threat hunting scenario.
- [ ] [TryHackMe | Hunt Me II: Typo Squatters](https://tryhackme.com/room/typosquatters) — Threat hunting scenario.
- [ ] [TryHackMe | Boogeyman 1](https://tryhackme.com/room/boogeyman1) — Email attack investigation.
- [ ] [TryHackMe | Unattended](https://tryhackme.com/room/unattended) — Investigate a Windows incident.
- [ ] [TryHackMe | ISO27001](https://tryhackme.com/room/iso27001) — Compliance fundamentals.
- [ ] [TryHackMe | Security Engineer Intro](https://tryhackme.com/room/securityengineerintro) — What security engineers build.

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


### 🆕 CVEs, Exploits & Misc Labs

- [ ] [TryHackMe | PaperCut: CVE-2023-27350](https://tryhackme.com/room/papercut) — Print server RCE.
- [ ] [TryHackMe | Moniker Link (CVE-2024-21413)](https://tryhackme.com/room/monikerlink) — Outlook moniker flaw.
- [ ] [TryHackMe | Confluence CVE-2023-22515](https://tryhackme.com/room/confluence202322515) — Broken access control to admin.
- [ ] [TryHackMe | GitLab CVE-2023-7028](https://tryhackme.com/room/gitlabcve20237028) — Account takeover via password reset.
- [ ] [TryHackMe | CVE-2023-38408](https://tryhackme.com/room/cve202338408) — OpenSSH agent forwarding RCE.
- [ ] [TryHackMe | Looney Tunables](https://tryhackme.com/room/looneytunes) — glibc privesc.
- [ ] [TryHackMe | Meltdown Explained](https://tryhackme.com/room/meltdownexplained) — CPU side-channel basics.
- [ ] [TryHackMe | Bypass Disable Functions](https://tryhackme.com/room/bypassdisablefunctions) — PHP hardening bypass.
- [ ] [TryHackMe | DNS Manipulation](https://tryhackme.com/room/dnsmanipulation) — Abuse DNS.
- [ ] [TryHackMe | Git and Crumpets](https://tryhackme.com/room/gitandcrumpets) — Git-based challenge.
- [ ] [TryHackMe | Hip Flask](https://tryhackme.com/room/hipflask) — Flask exploitation.
- [ ] [TryHackMe | Introduction to Django](https://tryhackme.com/room/django) — Learn the framework you will hack.
- [ ] [TryHackMe | Introduction to Flask](https://tryhackme.com/room/flask) — Learn the framework you will hack.
- [ ] [TryHackMe | Jupyter 101](https://tryhackme.com/room/jupyter101) — Notebook security basics.
- [ ] [TryHackMe | The find command](https://tryhackme.com/room/thefindcommand) — Master find for privesc and forensics.
- [ ] [TryHackMe | Windows Reversing Intro](https://tryhackme.com/room/windowsreversingintro) — Start Windows RE.
- [ ] [TryHackMe | Intro To Pwntools](https://tryhackme.com/room/introtopwntools) — Exploit dev scripting library.

---

## 🏁 Phase 9 — CTF Practice

> **Grind these. This is where it all comes together.**  
> Start Easy. When Easy feels boring, go Medium. Hard is OSCP-level.

### 🟢 Easy CTFs

- [ ] [TryHackMe | Pickle Rick](https://tryhackme.com/room/picklerick) — Web + Linux. Fun starter.
- [ ] [TryHackMe | RootMe](https://tryhackme.com/room/rrootme) — Upload bypass → privesc. Classic.
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
- [ ] [TryHackMe | Overpass 3 - Hosting](https://tryhackme.com/room/overpass3hosting) — NFS + SSH key + web shell.
- [ ] [TryHackMe | Anonymous](https://tryhackme.com/room/anonymous) — FTP anonymous + cron job + SUID.
- [ ] [TryHackMe | Blog](https://tryhackme.com/room/blog) — WordPress + SUID wp-cli exploit.
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
- [ ] [TryHackMe | VulnNet: Node](https://tryhackme.com/room/vulnnetnode) — Node.js deserialization.
- [ ] [TryHackMe | VulnNet: Internal](https://tryhackme.com/room/vulnnetinternal) — SMB + Redis + Rsync.
- [ ] [TryHackMe | Inferno](https://tryhackme.com/room/inferno) — Dante-themed. Multi-vector.
- [ ] [TryHackMe | Revenge](https://tryhackme.com/room/revenge) — SQL injection + service exploit.
- [ ] [TryHackMe | Mnemonic](https://tryhackme.com/room/mnemonic) — FTP + brute force + Python jail.
- [ ] [TryHackMe | Biohazard](https://tryhackme.com/room/biohazard) — Resident Evil themed CTF.
- [ ] [TryHackMe | Undiscovered](https://tryhackme.com/room/undiscoveredup) — VHost enum + RFI.
- [ ] [TryHackMe | broker](https://tryhackme.com/room/broker) — ActiveMQ CVE exploitation.

### 🔴 Hard CTFs

- [ ] [TryHackMe | Internal](https://tryhackme.com/room/internal) — OSCP-style. WordPress + Jenkins + port forward.
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


### 🟢 More Easy CTFs

- [ ] [TryHackMe | Basic Pentesting](https://tryhackme.com/room/basicpentestingjt) — Classic first boot2root.
- [ ] [TryHackMe | UltraTech](https://tryhackme.com/room/ultratech1) — Web enumeration to root.
- [ ] [TryHackMe | Library](https://tryhackme.com/room/bsidesgtlibrary) — Easy Linux machine.
- [ ] [TryHackMe | Thompson](https://tryhackme.com/room/bsidesgtthompson) — Tomcat machine.
- [ ] [TryHackMe | Anonforce](https://tryhackme.com/room/bsidesgtanonforce) — FTP and crypto.
- [ ] [TryHackMe | Dav](https://tryhackme.com/room/bsidesgtdav) — WebDAV machine.
- [ ] [TryHackMe | Develpy](https://tryhackme.com/room/bsidesgtdevelpy) — Python-based box.
- [ ] [TryHackMe | Jack-of-All-Trades](https://tryhackme.com/room/jackofalltrades) — Stego, web and privesc.
- [ ] [TryHackMe | Ninja Skills](https://tryhackme.com/room/ninjaskills) — Linux find practice.
- [ ] [TryHackMe | The Cod Caper](https://tryhackme.com/room/thecodcaper) — Linux forensics-style CTF.
- [ ] [TryHackMe | Tony the Tiger](https://tryhackme.com/room/tonythetiger) — Java deserialisation.
- [ ] [TryHackMe | Smag Grotto](https://tryhackme.com/room/smaggrotto) — Web, PCAP and cron.
- [ ] [TryHackMe | kiba](https://tryhackme.com/room/kiba) — Kibana exploitation.
- [ ] [TryHackMe | Poster](https://tryhackme.com/room/poster) — PostgreSQL and Metasploit.
- [ ] [TryHackMe | Lunizz CTF](https://tryhackme.com/room/lunizzctfnd) — Easy Linux CTF.
- [ ] [TryHackMe | Atlas](https://tryhackme.com/room/atlas) — Easy Linux machine.
- [ ] [TryHackMe | KoTH Food CTF](https://tryhackme.com/room/kothfoodctf) — King of the Hill practice.
- [ ] [TryHackMe | Pyrat](https://tryhackme.com/room/pyrat) — Python-based challenge.
- [ ] [TryHackMe | Cheese CTF](https://tryhackme.com/room/cheesectfv10) — Fun multi-step box.
- [ ] [TryHackMe | U.A. High School](https://tryhackme.com/room/yueiua) — Anime-themed CTF.
- [ ] [TryHackMe | Joomify](https://tryhackme.com/room/joomify) — Joomla exploitation.
- [ ] [TryHackMe | Publisher](https://tryhackme.com/room/publisher) — SPIP exploitation.
- [ ] [TryHackMe | W1seGuy](https://tryhackme.com/room/w1seguy) — XOR crypto challenge.
- [ ] [TryHackMe | mKingdom](https://tryhackme.com/room/mkingdom) — Web to root.
- [ ] [TryHackMe | CyberLens](https://tryhackme.com/room/cyberlensp6) — Web exploit box.
- [ ] [TryHackMe | TryHack3M: Bricks Heist](https://tryhackme.com/room/tryhack3mbricksheist) — WordPress incident.
- [ ] [TryHackMe | Creative](https://tryhackme.com/room/creative) — Easy web box.
- [ ] [TryHackMe | Dreaming](https://tryhackme.com/room/dreaming) — Easy Linux box.
- [ ] [TryHackMe | Hijack](https://tryhackme.com/room/hijack) — Cookie and NFS abuse.
- [ ] [TryHackMe | Compiled](https://tryhackme.com/room/compiled) — Reverse engineering starter.
- [ ] [TryHackMe | Super Secret TIp](https://tryhackme.com/room/supersecrettip) — Web challenge.
- [ ] [TryHackMe | Lesson Learned?](https://tryhackme.com/room/lessonlearned) — SQLi practice.
- [ ] [TryHackMe | Red](https://tryhackme.com/room/redisl33t) — LFI and privesc.
- [ ] [TryHackMe | Cat Pictures 2](https://tryhackme.com/room/catpictures2) — Follow-up to Cat Pictures.
- [ ] [TryHackMe | Flip](https://tryhackme.com/room/flip) — Crypto bit-flipping.
- [ ] [TryHackMe | Valley!](https://tryhackme.com/room/valleype) — Easy Linux box.
- [ ] [TryHackMe | Capture!](https://tryhackme.com/room/capture) — Brute force with captcha.
- [ ] [TryHackMe | Opacity](https://tryhackme.com/room/opacity) — Easy Linux box.
- [ ] [TryHackMe | Bugged](https://tryhackme.com/room/bugged) — IoT and MQTT room.
- [ ] [TryHackMe | Psycho Break](https://tryhackme.com/room/psychobreak) — Stego and web.
- [ ] [TryHackMe | AttackerKB](https://tryhackme.com/room/attackerkb) — Learn to research exploits.

### 🟡 More Medium CTFs

- [ ] [TryHackMe | Backtrack](https://tryhackme.com/room/backtrack) — Multi-step Linux box.
- [ ] [TryHackMe | Extracted](https://tryhackme.com/room/extractedroom) — Forensics-style challenge.
- [ ] [TryHackMe | The London Bridge](https://tryhackme.com/room/thelondonbridge) — SSRF to root.
- [ ] [TryHackMe | Breakme](https://tryhackme.com/room/breakmenu) — WordPress and privesc.
- [ ] [TryHackMe | Block](https://tryhackme.com/room/blockroom) — Windows forensics and AD.
- [ ] [TryHackMe | New York Flankees](https://tryhackme.com/room/thenewyorkflankees) — Web exploitation.
- [ ] [TryHackMe | Airplane](https://tryhackme.com/room/airplane) — Linux box.
- [ ] [TryHackMe | Profiles](https://tryhackme.com/room/profilesroom) — Web box.
- [ ] [TryHackMe | Clocky](https://tryhackme.com/room/clocky) — Web and crypto.
- [ ] [TryHackMe | Hack Smarter Security](https://tryhackme.com/room/hacksmartersecurity) — Windows box.
- [ ] [TryHackMe | Kitty](https://tryhackme.com/room/kitty) — SQLi box.
- [ ] [TryHackMe | Umbrella](https://tryhackme.com/room/umbrella) — Docker-based box.
- [ ] [TryHackMe | AVenger](https://tryhackme.com/room/avenger) — Bypass Windows Defender.
- [ ] [TryHackMe | WhyHackMe](https://tryhackme.com/room/whyhackme) — Web to root.
- [ ] [TryHackMe | Stealth](https://tryhackme.com/room/stealth) — Evade defences.
- [ ] [TryHackMe | Athena](https://tryhackme.com/room/4th3n4) — Linux box.
- [ ] [TryHackMe | Crylo](https://tryhackme.com/room/crylo4a) — Crypto challenge.
- [ ] [TryHackMe | Forgotten Implant](https://tryhackme.com/room/forgottenimplant) — C2 implant analysis.
- [ ] [TryHackMe | Weasel](https://tryhackme.com/room/weasel) — Windows box.
- [ ] [TryHackMe | Prioritise](https://tryhackme.com/room/prioritise) — SQLi box.
- [ ] [TryHackMe | StuxCTF](https://tryhackme.com/room/stuxctf) — Multi-step CTF.
- [ ] [TryHackMe | Boiler CTF](https://tryhackme.com/room/boilerctf2) — Joomla and privesc.
- [ ] [TryHackMe | HA Joker CTF](https://tryhackme.com/room/jokerctf) — Linux box.
- [ ] [TryHackMe | Break it](https://tryhackme.com/room/breakit) — Linux box.
- [ ] [TryHackMe | Willow](https://tryhackme.com/room/willow) — Crypto and privesc.
- [ ] [TryHackMe | Nax](https://tryhackme.com/room/nax) — Nagios exploitation.
- [ ] [TryHackMe | Mindgames](https://tryhackme.com/room/mindgames) — Brainfuck and privesc.
- [ ] [TryHackMe | 0day](https://tryhackme.com/room/0day) — Shellshock.
- [ ] [TryHackMe | Deja Vu](https://tryhackme.com/room/dejavu) — Web exploitation.
- [ ] [TryHackMe | KoTH Hackers](https://tryhackme.com/room/kothhackers) — King of the Hill practice.
- [ ] [TryHackMe | harder](https://tryhackme.com/room/harder) — Web box.
- [ ] [TryHackMe | HaskHell](https://tryhackme.com/room/haskhell) — Haskell-based box.
- [ ] [TryHackMe | Break Out The Cage](https://tryhackme.com/room/breakoutthecage1) — Linux box.
- [ ] [TryHackMe | The Impossible Challenge](https://tryhackme.com/room/theimpossiblechallenge) — Crypto puzzles.
- [ ] [TryHackMe | Looking Glass](https://tryhackme.com/room/lookingglass) — SSH and crypto.
- [ ] [TryHackMe | Recovery](https://tryhackme.com/room/recovery) — Incident investigation.
- [ ] [TryHackMe | Ghizer](https://tryhackme.com/room/ghizerctf) — Multi-step Linux box.
- [ ] [TryHackMe | WWBuddy](https://tryhackme.com/room/wwbuddy) — Web box.
- [ ] [TryHackMe | The Blob Blog](https://tryhackme.com/room/theblobblog) — Web and crypto.
- [ ] [TryHackMe | Cooctus Stories](https://tryhackme.com/room/cooctusadventures) — Linux box.
- [ ] [TryHackMe | One Piece](https://tryhackme.com/room/ctfonepiece65) — Anime-themed CTF.
- [ ] [TryHackMe | toc2](https://tryhackme.com/room/toc2) — Linux box.
- [ ] [TryHackMe | NerdHerd](https://tryhackme.com/room/nerdherd) — Linux box.
- [ ] [TryHackMe | The Server From Hell](https://tryhackme.com/room/theserverfromhell) — Ports and privesc.
- [ ] [TryHackMe | Jacob the Boss](https://tryhackme.com/room/jacobtheboss) — JBoss exploitation.
- [ ] [TryHackMe | Unbaked Pie](https://tryhackme.com/room/unbakedpie) — Pickle deserialisation.
- [ ] [TryHackMe | battery](https://tryhackme.com/room/battery) — Linux box.
- [ ] [TryHackMe | Madeye's Castle](https://tryhackme.com/room/madeyescastle) — Multi-step Linux box.
- [ ] [TryHackMe | En-pass](https://tryhackme.com/room/enpass) — Web box.
- [ ] [TryHackMe | Sustah](https://tryhackme.com/room/sustah) — Rate-limit bypass.
- [ ] [TryHackMe | Tokyo Ghoul](https://tryhackme.com/room/tokyoghoul666) — Anime-themed CTF.
- [ ] [TryHackMe | VulnNet: dotpy](https://tryhackme.com/room/vulnnetdotpy) — Python-based VulnNet.
- [ ] [TryHackMe | pyLon](https://tryhackme.com/room/pylonzf) — Python box.
- [ ] [TryHackMe | The Great Escape](https://tryhackme.com/room/thegreatescape) — Docker escape.
- [ ] [TryHackMe | SafeZone](https://tryhackme.com/room/safezone) — Web box.
- [ ] [TryHackMe | Sweettooth Inc.](https://tryhackme.com/room/sweettoothinc) — Multi-step box.
- [ ] [TryHackMe | Red Team OPSEC](https://tryhackme.com/room/opsec) — Operational security for red teams.
- [ ] [TryHackMe | Super-Spam](https://tryhackme.com/room/superspamr) — Web box.
- [ ] [TryHackMe | That's The Ticket](https://tryhackme.com/room/thatstheticket) — XSS to privesc.
- [ ] [TryHackMe | Red Stone One Carat](https://tryhackme.com/room/redstoneonecarat) — Linux box.
- [ ] [TryHackMe | Cold VVars](https://tryhackme.com/room/coldvvars) — Linux box.
- [ ] [TryHackMe | Metamorphosis](https://tryhackme.com/room/metamorphosis) — Linux box.
- [ ] [TryHackMe | Fortress](https://tryhackme.com/room/fortress) — Multi-stage challenge.
- [ ] [TryHackMe | CyberCrafted](https://tryhackme.com/room/cybercrafted) — Minecraft-themed box.

### 🔴 More Hard CTFs

- [ ] [TryHackMe | CERTain Doom](https://tryhackme.com/room/certaindoom) — Hard challenge.
- [ ] [TryHackMe | Capture Returns](https://tryhackme.com/room/capturereturns) — Hard brute force.
- [ ] [TryHackMe | Chrome](https://tryhackme.com/room/chrome) — Hard Windows box.
- [ ] [TryHackMe | Reset](https://tryhackme.com/room/resetui) — Windows AD box.
- [ ] [TryHackMe | Motunui](https://tryhackme.com/room/motunui) — Hard challenge.
- [ ] [TryHackMe | Spring](https://tryhackme.com/room/spring) — Spring framework exploitation.
- [ ] [TryHackMe | Borderlands](https://tryhackme.com/room/borderlands) — Hard web box.
- [ ] [TryHackMe | hc0n Christmas CTF](https://tryhackme.com/room/hc0nchristmasctf) — Event CTF.
- [ ] [TryHackMe | Jeff](https://tryhackme.com/room/jeff) — Hard Linux box.
- [ ] [TryHackMe | Racetrack Bank](https://tryhackme.com/room/racetrackbank) — Race conditions.
- [ ] [TryHackMe | Dave's Blog](https://tryhackme.com/room/davesblog) — Hard web box.
- [ ] [TryHackMe | Carpe Diem 1](https://tryhackme.com/room/carpediem1) — Hard Linux box.
- [ ] [TryHackMe | For Business Reasons](https://tryhackme.com/room/forbusinessreasons) — Hard box.
- [ ] [TryHackMe | Anonymous Playground](https://tryhackme.com/room/anonymousplayground) — Binary and crypto.
- [ ] [TryHackMe | Misguided Ghosts](https://tryhackme.com/room/misguidedghosts) — Hard box.
- [ ] [TryHackMe | Theseus](https://tryhackme.com/room/theseus) — Hard box.
- [ ] [TryHackMe | Year of the Dog](https://tryhackme.com/room/yearofthedog) — Hard Linux box.
- [ ] [TryHackMe | You're in a cave](https://tryhackme.com/room/inacave) — Hard challenge.
- [ ] [TryHackMe | envizon](https://tryhackme.com/room/envizon) — Hard box.
- [ ] [TryHackMe | GameBuzz](https://tryhackme.com/room/gamebuzz) — Hard box.
- [ ] [TryHackMe | Rocket](https://tryhackme.com/room/rocket) — Hard web box.
- [ ] [TryHackMe | Squid Game](https://tryhackme.com/room/squidgameroom) — Hard box.
- [ ] [TryHackMe | EnterPrize](https://tryhackme.com/room/enterprize) — Hard box.
- [ ] [TryHackMe | Frosteau Busy with Vim](https://tryhackme.com/room/busyvimfrosteau) — Insane-rated challenge.

---

## ☁️ Phase 10 — Cloud, Containers & DevSecOps

> **Who is this for?** Anyone heading into DevSecOps, cloud security or platform security.
> **Time estimate:** ~1 week
> **Goal:** Understand containers, Kubernetes and IaC security before attackers do.

- [ ] [TryHackMe | Intro to Docker](https://tryhackme.com/room/introtodockerk8pdqk) — Containers from zero.
- [ ] [TryHackMe | Intro to IaC](https://tryhackme.com/room/introtoiac) — Infrastructure as Code basics.
- [ ] [TryHackMe | SDLC](https://tryhackme.com/room/sdlc) — Secure development lifecycle.
- [ ] [TryHackMe | K8s Runtime Security](https://tryhackme.com/room/k8sruntimesecurity) — Detect threats inside clusters.
- [ ] [TryHackMe | K8s Best Security Practices](https://tryhackme.com/room/k8sbestsecuritypractices) — Lock down Kubernetes.
- [ ] [TryHackMe | Cluster Hardening](https://tryhackme.com/room/clusterhardening) — Harden a cluster.
- [ ] [TryHackMe | Kubernetes Chall TDI 2020](https://tryhackme.com/room/kuberneteschalltdi2020) — Kubernetes CTF.

---

## 🎄 Bonus — Special Events

> **Advent of Cyber is the best free cybersecurity event on the internet. Every December.**

- [ ] [TryHackMe | Advent of Cyber 1 [2019]](https://tryhackme.com/room/25daysofchristmas) — Beginner. 25 days of hacking challenges.
- [ ] [TryHackMe | Advent of Cyber 2 [2020]](https://tryhackme.com/room/adventofcyber2) — Web, networking, scripting, RE.
- [ ] [TryHackMe | Advent of Cyber 3 (2021)](https://tryhackme.com/room/adventofcyber3) — Blue team + red team tracks.
- [ ] [TryHackMe | Advent of Cyber 2022](https://tryhackme.com/room/adventofcyber4) — Smart contracts, log analysis, ML.
- [ ] [TryHackMe | 25 Days of Cyber Security](https://tryhackme.com/room/learncyberin25days) — Alternative beginner advent.
- [ ] [TryHackMe | Cyber Scotland 2021](https://tryhackme.com/room/cyberweek2021) — Mini event rooms.


- [ ] [TryHackMe | Advent of Cyber 2023](https://tryhackme.com/room/adventofcyber2023) — Blue and red tracks.
- [ ] [TryHackMe | Advent of Cyber 2024](https://tryhackme.com/room/adventofcyber2024) — Latest advent rooms covered here.
- [ ] [TryHackMe | Advent of Cyber '23 Side Quest](https://tryhackme.com/room/adventofcyber23sidequest) — Hard hidden challenges.
- [ ] [TryHackMe | Hacker of the Hill #1](https://tryhackme.com/room/hackerofthehill) — King of the Hill event.
- [ ] [TryHackMe | Learn and win prizes](https://tryhackme.com/room/tickets1) — Event rooms.
- [ ] [TryHackMe | Learn and win prizes #2](https://tryhackme.com/room/tickets2) — Event rooms.

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


## 🚫 No Longer Free

Reported by the community as moved behind the paywall. Skipped on purpose.

- ~~Linux Fundamentals Part 2~~ — [`linuxfundamentalspart2`](https://tryhackme.com/room/linuxfundamentalspart2)
- ~~Linux Fundamentals Part 3~~ — [`linuxfundamentalspart3`](https://tryhackme.com/room/linuxfundamentalspart3)
- ~~Intro to LAN~~ — [`introtolan`](https://tryhackme.com/room/introtolan)
- ~~Probe~~ — [`probe`](https://tryhackme.com/room/probe)
- ~~The Witch's Cauldron~~ — [`cauldron`](https://tryhackme.com/room/cauldron)
- ~~Bulletproof Penguin~~ — [`bppenguin`](https://tryhackme.com/room/bppenguin)
- ~~Grep~~ — [`greprtp`](https://tryhackme.com/room/greprtp)
- ~~Snapped Phish-ing Line~~ — [`snappedphishingline`](https://tryhackme.com/room/snappedphishingline)
- ~~LookBack~~ — [`lookback`](https://tryhackme.com/room/lookback)
- ~~Confidential~~ — [`confidential`](https://tryhackme.com/room/confidential)

Found another? [Open an issue](https://github.com/NISTALTALSON/free-tryhackme-rooms/issues).

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

If this roadmap helped you, **star it**. It's the only way other learners find it.

[![Star History Chart](https://api.star-history.com/svg?repos=NISTALTALSON/free-tryhackme-rooms&type=Date)](https://star-history.com/#NISTALTALSON/free-tryhackme-rooms&Date)

### 📣 Share it

[Share on X](https://twitter.com/intent/tweet?text=Free%20TryHackMe%20roadmap%3A%20470%2B%20rooms%2C%20phased%20from%20zero%20to%20hacker%2C%20no%20paywall&url=https%3A%2F%2Fgithub.com%2FNISTALTALSON%2Ffree-tryhackme-rooms) • [Share on LinkedIn](https://www.linkedin.com/sharing/share-offsite/?url=https%3A%2F%2Fgithub.com%2FNISTALTALSON%2Ffree-tryhackme-rooms) • [Share on Reddit](https://www.reddit.com/submit?url=https%3A%2F%2Fgithub.com%2FNISTALTALSON%2Ffree-tryhackme-rooms&title=Free%20TryHackMe%20roadmap)

### 👥 Contributors

[![Contributors](https://contrib.rocks/image?repo=NISTALTALSON/free-tryhackme-rooms)](https://github.com/NISTALTALSON/free-tryhackme-rooms/graphs/contributors)

> *"You don't need expensive courses. You need discipline and the right path. This is the path."*

---

<div align="center">

**Happy Hacking. Stay Ethical. Never Stop Learning.**

`hack the planet 🌍`

</div>
