# Isaac Handysides — Cybersecurity

Self-taught penetration tester based in Abbotsford, BC. Focused on offensive security with hands-on experience across home lab environments, CTF challenges, and original vulnerability research. Working toward a career in purple team operations.

Currently studying **CompTIA Security+**.

---

## Technical Skills

| | |
|---|---|
| **Operating Systems** | Kali Linux, Pop!_OS, Windows |
| **Pentesting Tools** | Nmap, Metasploit, Hydra, John the Ripper, WPScan, Wireshark, Nikto |
| **Scripting** | Python, Bash |
| **Concepts** | Network reconnaissance, service enumeration, privilege escalation, brute force testing, log analysis, red/blue team fundamentals |
| **Platforms** | TryHackMe, VulnHub |

---

## Projects

### [Python Port Scanner](https://github.com/IHandysides/port-scanner)
Multithreaded TCP port scanner built from scratch without external dependencies. Supports custom port ranges, service banner grabbing, hostname resolution, and nmap-style output. Tested against live home lab infrastructure and Nmap's public test server.

`Python` `Sockets` `Threading` `Networking`

---

## Security Research

### [Arcadyan Router — Client-Side Password Hashing](https://github.com/IHandysides/writeups)
Original vulnerability research conducted on personally owned Telus/Arcadyan home router. Identified that the router performs MD5+SHA-512 password hashing entirely in client-side JavaScript with no server-issued nonce, making authenticated sessions vulnerable to pass-the-hash replay attacks. Full methodology, proof of concept, and remediation recommendations documented.

---

## CTF Experience

| Machine | Platform | Result |
|---|---|---|
| Mr. Robot 1 | VulnHub | Full root — enumeration, web app analysis, privilege escalation |
| ColdBox | VulnHub | All flags captured |

Writeups in progress — [github.com/IHandysides/writeups](https://github.com/IHandysides/writeups)

---

## TryHackMe

Top 30% globally — 21 rooms completed — 4 badges earned

Notable rooms: Pentesting Fundamentals, Metasploit Introduction, Red Team Engagements, Junior Security Analyst Intro, SOC Blue Team, Linux Fundamentals, Hydra, Python Basics, Governance & Regulation

[tryhackme.com/p/Handysides](https://tryhackme.com/p/Handysides)

---

## Home Lab

- Lenovo ThinkPad dedicated penetration testing machine running Kali Linux
- Authorized network assessments across two personal networks
- UPnP enumeration and SOAP-based exploitation research on home router infrastructure
- Passive network traffic analysis with Wireshark and tshark
- Custom Python tooling for network reconnaissance

---

## Certifications & Study

- CompTIA Security+ — Active study
- CompTIA Network+ — Planned
- Occupational First Aid Level 1 — Certified

---

## Contact

[handysidesisaac@gmail.com](mailto:handysidesisaac@gmail.com) · Abbotsford, BC

---

*All security research and testing is conducted on personally owned equipment or with explicit written authorization.*
