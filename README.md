# Home Lab

My personal security home lab for practicing web, API, and network testing in a safe, isolated environment. I use it to build skills for bug bounty hunting (HackerOne, in-scope programs only) and CTFs.

## What's in the lab

| Target | Type | Purpose |
|---|---|---|
| OWASP Juice Shop | Vulnerable web app | Practice web app vulnerabilities (XSS, injection, broken auth, etc.) |
| crAPI | Vulnerable API | Practice API testing (BOLA, broken auth, excessive data exposure) |
| Metasploitable 2 | Vulnerable VM | Practice network scanning, service enumeration, and exploitation |

All targets run on an **Ubuntu server** on my MSI Cyborg 15 laptop.

## Hardware

- **Lab host:** MSI Cyborg 15 (i7, 16GB DDR5, RTX 5060)
- **Desktop:** Custom-built gaming PC (i7, 16GB DDR4, GTX 1070), used for gaming and other projects

## Docs

- [Lab setup](docs/lab-setup.md): how the lab is built and how to start/stop each target

## Safety

Everything here is intentionally vulnerable. Targets are run only on my own isolated network and are never exposed to the internet. Bug bounty testing is limited to in-scope programs.

## Skills practiced

- Windows administration 
- Linux administration (Ubuntu)
- Network and service enumeration
- Web and API vulnerability testing
- Documentation and note-taking
