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

**[About](#about)** &nbsp;·&nbsp; **[Projects](#projects)** &nbsp;·&nbsp; **[Interests](#interests)** &nbsp;·&nbsp; **[Toolkit](#toolkit)** &nbsp;·&nbsp; **[Contact](#contact)**

</div>

<br>

<a id="about"></a>
<img src="assets/sec-about.svg" width="100%" alt="01 — About me">

I'm Akkarapong, based in Bangkok, focused on **network engineering** and **defensive security**.

I learn by building. The projects below are how I work through questions like how traffic moves through a network, how a SOC turns raw events into alerts, and how to explain a routing decision clearly. Each one is working software with its own tests and documentation, and this profile tracks that work as it grows.

| Quick facts | |
| :-- | :-- |
| **Focus** | Network engineering · defensive security · security tooling |
| **Core stack** | TypeScript · Python · React · FastAPI · Docker |
| **Lab** | Windows workstation · Kali Linux security lab · Ubuntu server |
| **Approach** | Map it → capture it → automate it |

<br>

<a id="projects"></a>
<img src="assets/sec-projects.svg" width="100%" alt="02 — Projects">

Personal projects, each with its own documentation. Select a card to open the repository.

<p align="center">
<a href="https://github.com/aum-akkarapong/nexus-network-explorer"><img src="assets/card-nexus.svg" width="49%" alt="NEXUS Network Explorer — 3D digital twin of a factory network. View repository."></a>
<a href="https://github.com/aum-akkarapong/sentinel-soc"><img src="assets/card-soc.svg" width="49%" alt="Sentinel SOC — self-hosted SOC and SIEM. View repository."></a>
</p>
<p align="center">
<a href="https://github.com/aum-akkarapong/Network-Traffic-Analyzer"><img src="assets/card-nta.svg" width="49%" alt="Network Traffic Analyzer — packet capture, decoding and detection. View repository."></a>
<a href="https://github.com/aum-akkarapong/sentinel-pc"><img src="assets/card-sentinel-pc.svg" width="49%" alt="Sentinel PC — local Windows system monitor. View repository."></a>
</p>
<p align="center">
<a href="https://github.com/aum-akkarapong/cyber-security-interactive-learning"><img src="assets/card-cyber.svg" width="49%" alt="Cyber Security Interactive Learning — interactive security curriculum. View repository."></a>
<a href="https://github.com/aum-akkarapong/network-engineer-learning-hub"><img src="assets/card-nethub.svg" width="49%" alt="Network Engineer Learning Hub — interactive networking curriculum. View repository."></a>
</p>

<details>
<summary><b>Project highlights</b> — key details from each project</summary>

<br>

| Project | Highlights |
| :-- | :-- |
| **NEXUS Network Explorer** | Trace the network from a building view down to a single switch port, cable and VLAN · 17 incident scenarios walk through detection, impact, failover and recovery · 283 automated tests |
| **Sentinel SOC** | Event pipeline (parse → normalise → enrich → detect → alert) on Redis Streams · Sigma rules mapped to MITRE ATT&CK · disruptive SOAR actions require a second approver · tamper-evident audit log |
| **Network Traffic Analyzer** | One ingestion pipeline for live capture and PCAP files · DNS, HTTP and TLS metadata parsed from cleartext only · HTTPS is never decrypted |
| **Sentinel PC** | Unsupported sensors show *unavailable* instead of a guessed value · process and service actions are re-checked, confirmed and audited · runs on `127.0.0.1` only |
| **Cyber Security Learning** | 235 lessons in 19 modules · 172 animated scenes · 14 guided labs · content validated against schemas at build time |
| **Network Engineer Learning Hub** | 143 lessons in 18 tracks · tools for subnetting, VLSM, OSPF, BGP and ACLs · aligned with CCNA 200-301 topics |

</details>

<br>

<a id="interests"></a>
<img src="assets/sec-interests.svg" width="100%" alt="03 — Interests">

The areas I keep returning to, and the projects where they show up:

| Area | What draws me to it | Explored in |
| :-- | :-- | :-- |
| **Network visibility** | Understanding how infrastructure is actually connected — topology, VLANs and the path down to an individual port. | NEXUS · Traffic Analyzer |
| **Traffic analysis & detection** | Reading packets and turning raw telemetry into alerts that are explainable and worth acting on. | Traffic Analyzer · Sentinel SOC |
| **SOC operations** | The analyst workflow end to end: triage, investigation, incident response and controlled automation. | Sentinel SOC · Cyber Security Learning |
| **Explaining systems visually** | Networks and attacks are sequences of events, so step-through animations explain them better than text alone. | Cyber Security Learning · Network Hub |
| **Transparent, local-first tools** | Software that runs on your own machine, sends nothing out, and is clear about where every number comes from. | Sentinel PC |

**How I build**

| Principle | In practice |
| :-- | :-- |
| **Defensive by design** | Analysis is passive, lab work stays isolated and authorised, and disruptive actions need confirmation or a second approver. |
| **Honest data** | Missing sensors read *unavailable*, demo data is labelled as demo, and live sources show as connected only after a real test. |
| **Explain, don't just display** | Show the reason behind a result — the packet path, the failed uplink, the source of a reading. |
| **Tested and reproducible** | Automated tests, schema-validated content and one-command Docker setups. |

<br>

<a id="toolkit"></a>
<img src="assets/sec-toolkit.svg" width="100%" alt="04 — Toolkit">

| Category | Tools |
| :-- | :-- |
| **Languages** | ![TypeScript](https://img.shields.io/badge/TypeScript-000000?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-000000?style=flat-square&logo=javascript&logoColor=white) ![Python](https://img.shields.io/badge/Python-000000?style=flat-square&logo=python&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-000000?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-000000?style=flat-square&logo=css&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-000000?style=flat-square&logo=gnubash&logoColor=white) ![PowerShell](https://img.shields.io/badge/PowerShell-000000?style=flat-square) |
| **Frontend** | ![React](https://img.shields.io/badge/React-000000?style=flat-square&logo=react&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-000000?style=flat-square&logo=vite&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-000000?style=flat-square&logo=tailwindcss&logoColor=white) ![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white) ![React Router](https://img.shields.io/badge/React%20Router-000000?style=flat-square&logo=reactrouter&logoColor=white) ![MDX](https://img.shields.io/badge/MDX-000000?style=flat-square&logo=mdx&logoColor=white) |
| **Backend & Data** | ![Node.js](https://img.shields.io/badge/Node.js-000000?style=flat-square&logo=nodedotjs&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-000000?style=flat-square&logo=fastapi&logoColor=white) ![Pydantic](https://img.shields.io/badge/Pydantic-000000?style=flat-square&logo=pydantic&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-000000?style=flat-square&logo=sqlalchemy&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-000000?style=flat-square&logo=postgresql&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-000000?style=flat-square&logo=sqlite&logoColor=white) ![Zod](https://img.shields.io/badge/Zod-000000?style=flat-square&logo=zod&logoColor=white) |
| **DevOps & QA** | ![Docker](https://img.shields.io/badge/Docker-000000?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-000000?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-000000?style=flat-square&logo=github&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-000000?style=flat-square&logo=githubactions&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-000000?style=flat-square) ![Vitest](https://img.shields.io/badge/Vitest-000000?style=flat-square&logo=vitest&logoColor=white) ![ESLint](https://img.shields.io/badge/ESLint-000000?style=flat-square&logo=eslint&logoColor=white) |
| **Network & Security** | ![Wireshark](https://img.shields.io/badge/Wireshark-000000?style=flat-square&logo=wireshark&logoColor=white) ![Scapy](https://img.shields.io/badge/Scapy-000000?style=flat-square) ![Packet Tracer](https://img.shields.io/badge/Packet%20Tracer-000000?style=flat-square&logo=cisco&logoColor=white) ![VirtualBox](https://img.shields.io/badge/VirtualBox-000000?style=flat-square&logo=virtualbox&logoColor=white) |

**Lab environment**

| System | Role | Used for |
| :-- | :-- | :-- |
| **Windows** | Workstation | Daily development · PowerShell automation · system monitoring tools |
| **Kali Linux** | Security lab | Traffic capture and analysis · reconnaissance in authorised labs only |
| **Ubuntu** | Server / CLI | Linux administration · Bash scripting · Docker hosts and services |

<br>

<a id="contact"></a>
<img src="assets/sec-contact.svg" width="100%" alt="05 — Get in touch">

I'm open to collaborating on network and security projects, lab write-ups and tooling. For questions about any of the projects above, email is the best way to reach me.

<a href="mailto:aumakkara@gmail.com"><img src="https://img.shields.io/badge/Email-aumakkara%40gmail.com-000000?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://github.com/aum-akkarapong"><img src="https://img.shields.io/badge/GitHub-aum--akkarapong-000000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>

<br>

<p align="center"><sub>Bangkok, Thailand · UTC+7</sub></p>
