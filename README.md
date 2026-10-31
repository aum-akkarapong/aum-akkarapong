<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/header-light.svg">
  <img src="assets/header-light.svg" width="100%" alt="Akkarapong — Network Engineering, Defensive Security, Full-Stack Tooling. Bangkok, Thailand.">
</picture>

<div align="center">

<a href="mailto:aumakkara@gmail.com"><img src="https://img.shields.io/badge/Email-aumakkara%40gmail.com-000000?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
<img src="https://img.shields.io/badge/Based%20in-Bangkok%2C%20TH%20·%20UTC%2B7-000000?style=for-the-badge" alt="Bangkok, Thailand">
<img src="https://img.shields.io/badge/Open%20to-Collaboration-000000?style=for-the-badge" alt="Open to collaboration">

<br>

**[About](#about)** &nbsp;·&nbsp; **[Expertise](#expertise)** &nbsp;·&nbsp; **[Projects](#projects)** &nbsp;·&nbsp; **[Stack](#tech-stack)** &nbsp;·&nbsp; **[Lab](#lab-environment)** &nbsp;·&nbsp; **[Contact](#contact)**

</div>

<br>

## About

I'm a network and security engineer who builds software that makes networks easier to understand and defend. My work moves through three layers: **designing** networks, **watching** the traffic that crosses them, and **shipping** tools that make both understandable.

Everything I build follows the same loop: **map it → capture it → automate it.**

<table>
<tr>
<td width="25%" align="center"><h3>6</h3><sub>Featured projects</sub></td>
<td width="25%" align="center"><h3>378</h3><sub>Interactive lessons authored</sub></td>
<td width="25%" align="center"><h3>1,526</h3><sub>Devices in a 3D network twin</sub></td>
<td width="25%" align="center"><h3>22</h3><sub>SOC detections shipped</sub></td>
</tr>
</table>

<br>

## Expertise

<table>
<tr>
<th width="33%" align="left">01 — Network Engineering</th>
<th width="33%" align="left">02 — Defensive Security</th>
<th width="33%" align="left">03 — Software Engineering</th>
</tr>
<tr>
<td valign="top">

- IP addressing & subnetting
- VLANs, switching & routing
- Topology design & documentation
- Fault isolation & troubleshooting

</td>
<td valign="top">

- Packet capture & PCAP analysis
- Traffic baselines & detections
- Network & host monitoring
- Isolated, authorised lab work

</td>
<td valign="top">

- TypeScript / React applications
- Python APIs & capture tooling
- 3D & data visualisation
- Docker, CI & automated tests

</td>
</tr>
</table>

<br>

## Projects

### NEXUS Network Explorer &nbsp;<sub><code>FEATURED</code></sub>

> *Explore the factory. Understand the network. See the impact.*

A browser-based digital twin that connects a four-floor factory, enterprise networking, power systems and PCB production in one interactive 3D model.

| Facility | Network | Operations | Validation |
| :-: | :-: | :-: | :-: |
| **4** floors · **8** PCB lines | **1,526** devices · **2,828** links | **142** VLANs · **749** monitored hosts | **283** automated tests |

- Follow the network from the building view down to an individual switch port, cable and VLAN
- **Pulse** dashboard unifies network health, production, servers, power and alerts
- **17** incident scenarios walk through detection, impact, failover and recovery

![React Three Fiber](https://img.shields.io/badge/React%20Three%20Fiber-000000?style=flat-square&logo=threedotjs&logoColor=white) ![Zustand](https://img.shields.io/badge/Zustand-000000?style=flat-square) ![Python](https://img.shields.io/badge/Python-000000?style=flat-square&logo=python&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-000000?style=flat-square&logo=docker&logoColor=white)

---

### Sentinel SOC &nbsp;<sub><code>FEATURED</code></sub>

> *Telemetry, detection, triage, incident response and threat intelligence in one command center.*

A self-hosted Security Operations Center and SIEM that runs with a single `docker compose up`.

| Modules | Detections | Integrations | Roles |
| :-: | :-: | :-: | :-: |
| **18** | **22** | **12** | **6** built-in · MFA |

- Redis Streams pipeline: parse → normalise → enrich → index → detect → alert, with dead-letter queue and replay
- Native JSON and **Sigma** rules mapped to **MITRE ATT&CK**; threat hunting, threat map and IOC matching
- **Approval-gated SOAR**: disruptive actions need a second person; hash-chained, tamper-evident audit log

![FastAPI](https://img.shields.io/badge/FastAPI-000000?style=flat-square&logo=fastapi&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![OpenSearch](https://img.shields.io/badge/OpenSearch-000000?style=flat-square&logo=opensearch&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-000000?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-000000?style=flat-square&logo=redis&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-000000?style=flat-square&logo=docker&logoColor=white)

---

<table>
<tr>
<td width="50%" valign="top">

### Network Traffic Analyzer

Defensive monitoring platform: live capture or PCAP upload, **L2 → L7** decoding, streaming rule-based detections and a SOC-style dashboard.

- DNS, HTTP and TLS (SNI, ALPN, cipher) parsed from cleartext only
- HTTPS is never decrypted; passive analysis only

`FastAPI` `Scapy` `PostgreSQL` `React`

</td>
<td width="50%" valign="top">

### Sentinel PC

A local, real-time Windows system monitor that never guesses: every reading carries its source and status.

- **500 ms** cadence · **12** metric cards · **24 h** history
- Guarded process & service manager with audit log
- `127.0.0.1` only · **0** telemetry

`Node.js` `PowerShell` `React` `SQLite`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Cyber Security Interactive Learning

Learn how systems are attacked, detected and defended by watching it happen: concept → animation → lab → quiz.

- **235** lessons · **19** modules · **172** animated scenes
- **19** attack simulations · **14** labs · **716** quiz questions

`React` `React Flow` `Vitest` `Playwright`

</td>
<td width="50%" valign="top">

### Network Engineer Learning Hub

*Read it. See it. Watch it happen.* A network curriculum from cables and frames to routing, security, cloud and design.

- **143** lessons · **18** tracks · **70** interactives
- **270** glossary terms · CCNA 200-301 aligned

`Next.js` `next-intl` `Shiki` `Python`

</td>
</tr>
</table>

<p align="center"><sub>Repositories are private — access available on request.</sub></p>

<br>

## Engineering Principles

| Principle | In practice |
| :-- | :-- |
| **Defensive by design** | Tools analyse passively, run in isolated labs, and gate disruptive actions behind confirmation or a second approver. |
| **Honest data** | A missing sensor reads *unavailable*, demo data is labelled *DEMO*, and live sources show as connected only after a real test. |
| **Explain, don't just display** | Every system I build tries to show *why* — the packet path, the failed uplink, the source of each number. |
| **Tested and reproducible** | Automated tests, schema-validated content and one-command Docker setups. |

<br>

## Tech Stack

**Languages**<br>
![TypeScript](https://img.shields.io/badge/TypeScript-000000?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-000000?style=flat-square&logo=javascript&logoColor=white) ![Python](https://img.shields.io/badge/Python-000000?style=flat-square&logo=python&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-000000?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-000000?style=flat-square&logo=css&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-000000?style=flat-square&logo=gnubash&logoColor=white) ![PowerShell](https://img.shields.io/badge/PowerShell-000000?style=flat-square)

**Frontend**<br>
![React](https://img.shields.io/badge/React-000000?style=flat-square&logo=react&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-000000?style=flat-square&logo=vite&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-000000?style=flat-square&logo=tailwindcss&logoColor=white) ![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white) ![React Router](https://img.shields.io/badge/React%20Router-000000?style=flat-square&logo=reactrouter&logoColor=white) ![MDX](https://img.shields.io/badge/MDX-000000?style=flat-square&logo=mdx&logoColor=white)

**Backend & Data**<br>
![Node.js](https://img.shields.io/badge/Node.js-000000?style=flat-square&logo=nodedotjs&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-000000?style=flat-square&logo=fastapi&logoColor=white) ![Pydantic](https://img.shields.io/badge/Pydantic-000000?style=flat-square&logo=pydantic&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-000000?style=flat-square&logo=sqlalchemy&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-000000?style=flat-square&logo=postgresql&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-000000?style=flat-square&logo=sqlite&logoColor=white) ![Zod](https://img.shields.io/badge/Zod-000000?style=flat-square&logo=zod&logoColor=white)

**DevOps & QA**<br>
![Docker](https://img.shields.io/badge/Docker-000000?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-000000?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-000000?style=flat-square&logo=github&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-000000?style=flat-square&logo=githubactions&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-000000?style=flat-square) ![Vitest](https://img.shields.io/badge/Vitest-000000?style=flat-square&logo=vitest&logoColor=white) ![ESLint](https://img.shields.io/badge/ESLint-000000?style=flat-square&logo=eslint&logoColor=white)

<br>

## Lab Environment

| System | Role | Used for |
| :-- | :-- | :-- |
| **Windows** | Workstation | Daily driver and dev box · PowerShell automation · system monitoring tooling |
| **Kali Linux** | Security lab | Traffic capture and analysis · recon in authorised labs · offensive tooling, defensive use |
| **Ubuntu** | Server / CLI | Linux administration · Bash scripting · Docker hosts and services |

![Wireshark](https://img.shields.io/badge/Wireshark-Protocol%20analysis-000000?style=flat-square&logo=wireshark&logoColor=white) ![Scapy](https://img.shields.io/badge/Scapy-Packet%20crafting-000000?style=flat-square) ![Packet Tracer](https://img.shields.io/badge/Packet%20Tracer-Topology%20labs-000000?style=flat-square&logo=cisco&logoColor=white) ![VirtualBox](https://img.shields.io/badge/VirtualBox-Isolated%20VMs-000000?style=flat-square&logo=virtualbox&logoColor=white)

<br>

## Contact

Open to network and security collaboration, lab write-ups and tooling. The fastest way to reach me is email.

<a href="mailto:aumakkara@gmail.com"><img src="https://img.shields.io/badge/Email-aumakkara%40gmail.com-000000?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://github.com/aum-akkarapong"><img src="https://img.shields.io/badge/GitHub-aum--akkarapong-000000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>

<br>

<p align="center"><sub>Bangkok, Thailand · UTC+7</sub></p>
