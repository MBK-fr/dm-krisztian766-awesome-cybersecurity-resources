# Awesome Cybersecurity Resources [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![Made with Markdown](https://img.shields.io/badge/made%20with-Markdown-1f425f.svg)](https://commonmark.org)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: CC0](https://img.shields.io/badge/License-CC0-lightgrey.svg)](LICENSE)

A curated collection of tools, websites, and learning resources for OSINT, penetration testing, malware analysis, privacy, and general IT security. Useful for beginners and seasoned practitioners alike — continuously updated as tools and trends evolve.

> ⚠️ **Responsible use:** many tools on this list are intended for authorized testing only (pentest engagements, your own lab, CTFs). Always follow applicable laws and ethical guidelines.

## Contents

- [OSINT Tools](#osint-tools)
- [Vulnerability & Exploit Databases](#vulnerability--exploit-databases)
- [WHOIS & DNS Tools](#whois--dns-tools)
- [Network & Web Application Testing Tools](#network--web-application-testing-tools)
- [Cloud Security](#cloud-security)
- [Container & Kubernetes Security](#container--kubernetes-security)
- [Mobile Security](#mobile-security)
- [Malware Analysis & Sandboxes](#malware-analysis--sandboxes)
- [Data Breach & Leak Search](#data-breach--leak-search)
- [Dark Web Tools](#dark-web-tools)
- [Password Cracking & Wordlists](#password-cracking--wordlists)
- [Digital Forensics](#digital-forensics)
- [Threat Intelligence](#threat-intelligence)
- [Pentesting & CTF Platforms](#pentesting--ctf-platforms)
- [Social Engineering & Red Team Tools](#social-engineering--red-team-tools)
- [Bug Bounty Platforms](#bug-bounty-platforms)
- [Security-Focused Distros](#security-focused-distros)
- [Privacy Tools](#privacy-tools)
- [Encryption & Secure Storage](#encryption--secure-storage)
- [News, Blogs & Communities](#news-blogs--communities)
- [Learning Resources](#learning-resources)
- [Other Useful Resources](#other-useful-resources)

## OSINT Tools
1. [IntelTechniques](https://inteltechniques.com) - Collection of OSINT tools and search engines.
2. [OSINTCurio.us](https://osintcurio.us) - OSINT techniques and resource roundups.
3. [Maltego](https://www.maltego.com) - OSINT and link-analysis tool for building relationship graphs.
4. [Shodan](https://www.shodan.io) - Search engine for internet-connected devices.
5. [Censys](https://search.censys.io) - Search engine for internet assets and exposed vulnerabilities.
6. [Recon-ng](https://github.com/lanmaster53/recon-ng) - Web reconnaissance framework for OSINT gathering.
7. [GHDB (Google Hacking Database)](https://www.exploit-db.com/google-hacking-database) - Searchable database of Google dorks.
8. [theHarvester](https://github.com/laramies/theHarvester) - Gathers emails, subdomains, and hosts from open sources.
9. [SpiderFoot](https://www.spiderfoot.net) - Automated OSINT reconnaissance platform.
10. [Sherlock](https://github.com/sherlock-project/sherlock) - Finds usernames across hundreds of social platforms.

## Vulnerability & Exploit Databases
1. [CVE Details](https://www.cvedetails.com) - Detailed information on CVE-coded vulnerabilities.
2. [NVD (National Vulnerability Database)](https://nvd.nist.gov) - The official U.S. government vulnerability database.
3. [Exploit-DB](https://www.exploit-db.com) - Offensive Security's public archive of exploits and shellcode.
4. [Packet Storm Security](https://packetstormsecurity.com) - Exploits, advisories, and security articles.
5. [Vulmon](https://vulmon.com) - Searchable exploit/vulnerability database with vulnerability tracking.
6. [GitHub Advisory Database](https://github.com/advisories) - Known vulnerabilities in open-source packages.
7. [CISA Known Exploited Vulnerabilities](https://www.cisa.gov/known-exploited-vulnerabilities-catalog) - Official catalog of vulnerabilities exploited in the wild.

## WHOIS & DNS Tools
1. [Whois.domaintools](https://whois.domaintools.com) - Detailed WHOIS info, DNS history, and IP data.
2. [Who.is](https://who.is) - Simple WHOIS lookup showing domain ownership and registration details.
3. [ViewDNS.info](https://viewdns.info) - Bundle of OSINT tools: WHOIS lookup, reverse DNS, traceroute, and more.
4. [SecurityTrails](https://securitytrails.com) - Historical DNS and domain data for research.
5. [DNSDumpster](https://dnsdumpster.com) - Free DNS recon and mapping tool.

## Network & Web Application Testing Tools
1. [Nmap](https://nmap.org) - The most widely used network port and service discovery scanner.
2. [Wireshark](https://www.wireshark.org) - Packet analyzer for inspecting network traffic.
3. [Burp Suite](https://portswigger.net/burp) - Web application testing proxy and toolkit.
4. [OWASP ZAP](https://www.zaproxy.org) - Open-source web application vulnerability scanner.
5. [Nikto](https://github.com/sullo/nikto) - Command-line web server vulnerability scanner.
6. [SQLmap](https://sqlmap.org) - Automated SQL injection detection and exploitation tool.
7. [Metasploit Framework](https://www.metasploit.com) - Penetration testing framework for developing and running exploits.

## Cloud Security
1. [Prowler](https://github.com/prowler-cloud/prowler) - Open-source security assessment tool for AWS, Azure, and GCP.
2. [ScoutSuite](https://github.com/nccgroup/ScoutSuite) - Multi-cloud security auditing tool.
3. [Pacu](https://github.com/RhinoSecurityLabs/pacu) - AWS exploitation framework for offensive security testing.
4. [CloudSploit](https://github.com/aquasecurity/cloudsploit) - Cloud security configuration scanner.

## Container & Kubernetes Security
1. [Trivy](https://github.com/aquasecurity/trivy) - Vulnerability and misconfiguration scanner for containers, IaC, and repos.
2. [kube-bench](https://github.com/aquasecurity/kube-bench) - Checks Kubernetes clusters against CIS benchmark best practices.
3. [Falco](https://falco.org) - Runtime security tool for detecting anomalous container/Kubernetes behavior.
4. [Docker Bench for Security](https://github.com/docker/docker-bench-security) - Checks Docker deployments against security best practices.

## Mobile Security
1. [MobSF (Mobile Security Framework)](https://github.com/MobSF/Mobile-Security-Framework-MobSF) - Automated static/dynamic analysis for Android, iOS, and Windows apps.
2. [Frida](https://frida.re) - Dynamic instrumentation toolkit for reverse engineering mobile and desktop apps.
3. [Objection](https://github.com/sensepost/objection) - Runtime mobile exploration toolkit built on Frida, no jailbreak/root required.
4. [Drozer](https://github.com/WithSecureLabs/drozer) - Security testing framework for Android apps and devices.
5. [Apktool](https://apktool.org) - Reverse-engineers Android APKs into near-original source and resource files.
6. [JADX](https://github.com/skylot/jadx) - Decompiles Android DEX/APK files into readable Java source.

## Malware Analysis & Sandboxes
1. [VirusTotal](https://www.virustotal.com) - Scans files and URLs against dozens of antivirus engines.
2. [Hybrid Analysis](https://www.hybrid-analysis.com) - Detailed behavioral analysis of files and URLs.
3. [URLScan.io](https://urlscan.io) - Scans and maps websites, showing related domains and requests.
4. [Any.Run](https://any.run) - Interactive, cloud-based malware sandbox.
5. [MalwareBazaar](https://bazaar.abuse.ch) - Repository of malware samples and IOCs.
6. [Joe Sandbox](https://www.joesandbox.com) - Deep automated malware and file analysis.
7. [Cuckoo Sandbox](https://cuckoosandbox.org) - Open-source, self-hosted malware sandbox system.

## Data Breach & Leak Search
1. [Have I Been Pwned](https://haveibeenpwned.com) - Checks if an email address has appeared in a data breach.
2. [Dehashed](https://www.dehashed.com) - Searchable database of leaked credentials and data.
3. [Snusbase](https://www.snusbase.com) - Paid tool for searching leaked data by email or username.
4. [Intelligence X](https://intelx.io) - Search engine for leaks, documents, and domain data.

## Dark Web Tools
1. [Tor Project](https://www.torproject.org) - The primary tool for anonymous browsing and dark web access.
2. [Ahmia](https://ahmia.fi) - Search engine for onion sites on the Tor network.
3. [OnionSearch](https://github.com/megadose/OnionSearch) - Queries multiple onion search engines at once.
4. [OnionScan](https://github.com/s-rah/onionscan) - Scans Tor hidden services for operational-security misconfigurations.
5. [Dark.fail](https://dark.fail) - Verifies canonical, non-phishing onion links for well-known dark web services.

## Password Cracking & Wordlists
1. [Hashcat](https://hashcat.net/hashcat) - GPU-accelerated password recovery tool.
2. [John the Ripper](https://www.openwall.com/john) - Classic, versatile password-cracking tool.
3. [SecLists](https://github.com/danielmiessler/SecLists) - Collection of wordlists, payloads, and fuzzing lists for pentesters.
4. [CrackStation](https://crackstation.net) - Free online hash-cracking service.

## Digital Forensics
1. [Autopsy](https://www.autopsy.com) - Open-source digital forensics platform.
2. [Volatility](https://volatilityfoundation.org) - Framework for analyzing memory (RAM) dumps.
3. [SANS DFIR Posters & Cheat Sheets](https://www.sans.org/posters) - Incident response and forensics reference sheets.

## Threat Intelligence
1. [MITRE ATT&CK Navigator](https://mitre-attack.github.io/attack-navigator) - Interactive matrix for mapping adversary tactics and techniques.
2. [AlienVault OTX (Open Threat Exchange)](https://otx.alienvault.com) - Community-driven threat intelligence sharing platform.
3. [Abuse.ch](https://abuse.ch) - Trackers for malware, botnets, and malicious URLs (Feodo, URLhaus, ThreatFox).
4. [Talos Intelligence](https://talosintelligence.com) - Cisco's threat intelligence research and reputation lookup.

## Pentesting & CTF Platforms
1. [Hack The Box](https://www.hackthebox.com) - Interactive pentesting labs and challenges.
2. [TryHackMe](https://tryhackme.com) - Guided learning platform for beginners and advanced users alike.
3. [OverTheWire](https://overthewire.org) - Linux-based wargames and challenges.
4. [PicoCTF](https://picoctf.org) - Free, beginner-friendly CTF platform by Carnegie Mellon University.
5. [PortSwigger Web Security Academy](https://portswigger.net/web-security) - Free, hands-on web security training.

## Social Engineering & Red Team Tools
1. [Gophish](https://getgophish.com) - Open-source phishing simulation framework for security awareness testing.
2. [Social-Engineer Toolkit (SET)](https://github.com/trustedsec/social-engineer-toolkit) - Framework for simulating social engineering attacks.
3. [Cobalt Strike](https://www.cobaltstrike.com) - Commercial adversary simulation and red team command-and-control platform.
4. [Evilginx](https://github.com/kgretzky/evilginx2) - Man-in-the-middle phishing framework for bypassing 2FA in authorized engagements.

## Bug Bounty Platforms
1. [HackerOne](https://www.hackerone.com) - Bug bounty programs and a community of ethical hackers.
2. [Bugcrowd](https://www.bugcrowd.com) - Bug bounty platform connecting companies and researchers.
3. [Intigriti](https://www.intigriti.com) - EU-based bug bounty platform.
4. [YesWeHack](https://www.yeswehack.com) - European bug bounty and vulnerability disclosure platform.

## Security-Focused Distros
1. [Kali Linux](https://www.kali.org) - The most popular Linux distribution built for penetration testing.
2. [Parrot Security OS](https://www.parrotsec.org) - Distro focused on pentesting, forensics, and development.
3. [Tails OS](https://tails.boum.org) - Amnesic operating system designed for anonymity.

## Privacy Tools
1. [ProtonMail](https://proton.me/mail) - End-to-end encrypted email service.
2. [Mullvad VPN](https://mullvad.net) - Anonymous, no-logs VPN service.
3. [Signal](https://signal.org) - End-to-end encrypted messaging app.
4. [DuckDuckGo](https://duckduckgo.com) - Privacy-focused search engine.

## Encryption & Secure Storage
1. [VeraCrypt](https://www.veracrypt.fr) - Strong disk and file encryption software.
2. [LUKS (Linux Unified Key Setup)](https://en.wikipedia.org/wiki/Linux_Unified_Key_Setup) - Full-disk encryption standard for Linux.
3. [Cryptomator](https://cryptomator.org) - Encrypted cloud storage for your files.
4. [Bitwarden](https://bitwarden.com) - Open-source password manager.
5. [KeePassXC](https://keepassxc.org) - Offline password manager.

## News, Blogs & Communities
1. [The Hacker News](https://thehackernews.com) - Daily cybersecurity news.
2. [Krebs on Security](https://krebsonsecurity.com) - In-depth security journalism by Brian Krebs.
3. [BleepingComputer](https://www.bleepingcomputer.com) - Malware, ransomware, and vulnerability news.
4. [r/netsec](https://www.reddit.com/r/netsec) - Technical infosec community on Reddit.

## Learning Resources
1. [TCM Security Academy](https://academy.tcm-sec.com) - Practical, hands-on pentesting courses.
2. [Cybrary](https://www.cybrary.it) - Free and paid IT security training.
3. [OWASP Top 10](https://owasp.org/www-project-top-ten) - The official list of critical web application security risks.
4. [IppSec (YouTube)](https://www.youtube.com/ippsec) - Detailed video walkthroughs of Hack The Box machines.

## Other Useful Resources
1. [PrivacyGuides](https://www.privacyguides.org) - Privacy recommendations and guides.
2. [r/privacy (Reddit)](https://www.reddit.com/r/privacy) - Privacy and anonymous browsing tips.
3. [MITRE ATT&CK](https://attack.mitre.org) - Knowledge base of adversary tactics and techniques.

## Contributing

New link suggestions are welcome! Open a Pull Request, or file an Issue for a broken/outdated link. Please make sure new entries are relevant, actively maintained, and include a short description. See `CONTRIBUTING.md` for details.

Released under CC0 1.0 Universal, see `LICENSE`.
