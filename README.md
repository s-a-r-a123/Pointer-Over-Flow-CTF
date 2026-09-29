# 🏴‍☠️ POCTF 2026 — CTF Writeups

A collection of my **POCTF 2026** challenge writeups, covering the techniques, enumeration steps, vulnerabilities, tools, and solutions used throughout the competition.

> **CTF:** Pointer Overflow CTF 2026 (POCTF 2026)
> **Website:** https://pointeroverflowctf.com/
> **Year:** 2026

---

## 📌 About

**POCTF (Pointer Overflow CTF)** is a Capture The Flag competition featuring challenges across multiple cybersecurity categories.

This repository documents my approach to solving the challenges, including:

* 🔐 Cryptography
* 💥 Binary Exploitation / Pwn
* 🔬 Digital Forensics
* 🧩 Miscellaneous Challenges
* 🕵️ OSINT (Open-Source Intelligence)
* ⚙️ Reverse Engineering
* 🖼️ Steganography
* 🌐 Web Exploitation

The goal of these writeups is not only to record the flags, but also to explain **how the vulnerability was identified and how the solution was developed**.

---

## 🛠️ Tools & Technologies

Some of the tools and technologies used throughout the challenges include:

| Category            | Tools                                     |
| ------------------- | ----------------------------------------- |
| Web                 | Burp Suite, curl, Browser DevTools        |
| Recon               | Nmap, Gobuster, ffuf, DNS tools           |
| Linux               | Kali Linux, Bash                          |
| Scripting           | Python, PowerShell                        |
| Crypto              | CyberChef, Python                         |
| Forensics           | Wireshark, Binwalk, ExifTool              |
| Reverse Engineering | Ghidra, strings, objdump, GDB             |
| Pwn                 | pwntools, GDB                             |
| OSINT               | Search engines, DNS tools, public sources |
| Cloud               | AWS CLI, cloud APIs                       |
| Mobile              | JADX, APKTool, adb                        |

---

## 🧠 Writeup Format

Each challenge writeup generally follows this structure:

````text
# Challenge Name

## 📋 Challenge Description

Original challenge description or a short summary.

## 🔍 Enumeration

Initial reconnaissance and interesting observations.

## 🧩 Analysis

Analysis of the application, binary, file, protocol, or vulnerability.

## 💥 Exploitation

Commands, scripts, payloads, or techniques used to exploit the challenge.

## 🚩 Flag

```text
POCTF{...}
````

## 📝 Takeaways

What the challenge taught me and the important concepts involved.

````

---

## ⚠️ Spoilers

These writeups contain **complete solutions and flags**.

If you're currently playing POCTF 2026, be aware that opening the challenge directories may reveal the solution.

**Spoiler warning:** 🚨 Proceed at your own risk!

---

## 🎯 Goals

This repository is intended to:

- Document my POCTF 2026 journey.
- Keep track of techniques and vulnerabilities I encounter.
- Build a personal cybersecurity reference.
- Help others understand the underlying concepts.
- Practice writing clear and reproducible CTF solutions.

---

## 📚 What You'll Find Here

Each writeup aims to explain the **reasoning behind the solution**, rather than simply providing the final flag.

Typical flow:

```text
Recon
  ↓
Enumeration
  ↓
Identify Interesting Behavior
  ↓
Analyze Vulnerability
  ↓
Develop Exploit / Solution
  ↓
Capture Flag
  ↓
Document Findings
````

---

## 🤝 Contributions

This repository primarily contains my own solutions and notes.

If you notice an error, have a better approach, or want to suggest an improvement, feel free to open an **Issue** or **Pull Request**.

---

## 📜 Disclaimer

All techniques documented here are intended for:

* Capture The Flag competitions
* Authorized security testing
* Educational purposes
* Security research in controlled environments

Do **not** use these techniques against systems without explicit authorization.

---

## ⭐ Support

If these writeups help you learn something, consider giving the repository a ⭐.

Happy hacking! 🔥

**— POCTF 2026**
