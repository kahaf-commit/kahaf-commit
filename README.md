# Penetration Testing — Writeups & Walkthroughs

A documented record of hands-on penetration testing work: methodology-driven writeups covering Active Directory exploitation, web application security, and red team infrastructure — built to reflect real-world engagement standards, not just CTF completions.

**Author:** MD Jubair Hossain — Penetration Tester
**Portfolio:** [Medium](https://medium.com/@muhammadjubairsec) · [LinkedIn](https://www.linkedin.com/in/jubairbd)
**Focus areas:** Active Directory Security · Web Application Pentesting · Red Team Infrastructure (C2) · Vulnerability Chaining

---

## Why this repo

Certifications validate knowledge; this repo validates *application*. Every writeup here follows a consistent, engagement-style methodology — recon, exploitation, impact, and remediation — the same structure expected in a professional penetration test report. This is meant to demonstrate readiness for practical, exam-style assessments (e.g. CPENT) as much as it documents a learning path.

---

## Index

### 🗂️ Active Directory
| Writeup | What it covers |
|---|---|
| [AD Enumeration & Attack Path Mapping with BloodHound](./Active-Directory/AD-Enumeration-BloodHound.md) | Full enumeration-to-privilege-escalation flow in a lab AD environment using BloodHound CE; identifying attack paths via ACL abuse and Kerberos misconfigurations. |
| [Exploiting Active Directory — TryHackMe](./Active-Directory/THM-Exploiting-AD.md) | Structured walkthrough connecting enumeration, lateral movement, and privilege escalation techniques into a single attack chain. |

### 🕸️ Web Application Security
| Writeup | What it covers |
|---|---|
|  [Web Application Pentest](./Web%dApplication%dPentest/Web%dApplication%dPentest.md) | Methodology and findings from web application penetration testing exercises, including vulnerability identification and exploitation. | |

### 🎯 Red Team / C2 Infrastructure
| Writeup | What it covers |
|---|---|
| [AdaptixC2 — Installation, Configuration & Operational Notes](./Red-Team/AdaptixC2-Setup.md) | Building and configuring a C2 framework in an isolated lab, understanding listener/agent architecture relevant to red team infrastructure. |

### 🧩 CTF & Guided Labs (TryHackMe / HackTheBox)
| Writeup | What it covers |
|---|---|
| [Room & machine writeups](./TryHackMe/) | Individual room/machine walkthroughs — enumeration methodology, exploitation steps, and takeaways per target. |

---

## Methodology used across every writeup

1. **Scope & Objective** — target, environment, and goal
2. **Reconnaissance & Enumeration** — tooling, service discovery, attack surface mapping
3. **Exploitation** — step-by-step technical execution with reasoning, not just commands
4. **Privilege Escalation / Lateral Movement** (where applicable)
5. **Impact** — what access or data exposure the chain achieves
6. **Remediation** — concrete, actionable fixes a defender would implement
7. **Lessons Learned / Notes for future engagements**

This mirrors the recon → exploitation → reporting structure used in real penetration test engagements and practical certification exams.

## Toolset

`BloodHound CE` · `Nmap` · `Burp Suite` · `Impacket` · `CrackMapExec` · `Mimikatz` · `AdaptixC2` · `Docker` (lab environments)

## Related work

- Setup guides and technical deep-dives are also published on Medium, including BloodHound CE deployment on Kali via Docker and AdaptixC2 configuration.
- Active on TryHackMe working through Active Directory and red team learning paths.

## Scope & Ethics

All work documented here was performed in authorized lab environments, CTF platforms (TryHackMe, HackTheBox), or self-hosted infrastructure built specifically for this purpose. Nothing in this repository reflects unauthorized access to third-party systems.

---

📫 **Contact:** [LinkedIn](https://www.linkedin.com/in/jubairbd)
