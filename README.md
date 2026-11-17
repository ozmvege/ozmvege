## Hi, I'm Özen Ucan

**Cloud Infrastructure · Endpoint & Security Engineering · Full-Stack Systems**

*I build systems and test where they break* — from Zero-Trust Azure & Oracle Cloud architectures and validated Microsoft Intune lab platforms to full-stack web applications and offensive security tooling.

Training as a *Fachinformatiker für Systemintegration (IHK)* while building [**ByteExam**](https://byteexam.app) and ranking in the **Top 1% on TryHackMe**.

[![Portfolio](https://img.shields.io/badge/Portfolio-oezen--ucan.dev-111827?style=flat-square&logo=cloudflareworkers&logoColor=F38020)](https://oezen-ucan.dev)
[![ByteExam](https://img.shields.io/badge/Building-ByteExam-2563EB?style=flat-square)](https://byteexam.app)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-Top_1%25-212C42?style=flat-square&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/oez)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-oezen--ucan-0A66C2?style=flat-square)](https://www.linkedin.com/in/oezen-ucan)
[![Email](https://img.shields.io/badge/Email-ozenucan.99%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ozenucan.99@gmail.com)

---

### Featured Projects

#### [ByteExam](https://byteexam.app) — IHK IT Exam Prep & Micro-Learning Platform *(private repo · live)*

Full-stack web and mobile platform preparing IT trainees across all four IHK specialist tracks (**FIAE, FISI, FIDP, FIDV**) for AP1 and AP2.

- **Engineering:** Blueprint-weighted timed exam simulations, 10 deterministic question types with instant feedback, XP/streaks/topic mastery, JSON-validated learning field sync, and an admin review workflow, paired with an Expo / React Native mobile app.
- **Stack:** `Next.js 16` · `React 19` · `TypeScript` · `Tailwind CSS v4` · `PostgreSQL` · `Prisma` · `Zod` · `OAuth + TOTP 2FA` · `Expo`

#### [Azure Bicep Lab](https://github.com/ozmvege/azure-bicep-lab) — Zero-Trust Web Platform · [Live Docs](https://ozmvege.github.io/azure-bicep-lab/)

Production-shaped Azure platform written completely in Bicep where Application Gateway WAF v2 is the sole public entry point and every security control ships with a verification command trying to break it.

- **Architecture:** 20 Bicep modules across 7 domains at subscription scope (`@export()` types, user-defined functions, `az.getSecret()` `.bicepparam`), Hub-and-Spoke VNet, 6 Private Endpoints, 4 Private DNS Zones, Managed Identity & key-free storage, 3 custom Deny Azure Policies, Deployment Stacks, and OIDC CI/CD (`PSRule for Azure` + offline `bicep test` assertions).
- **Stack:** `Azure Bicep` · `Application Gateway WAF v2` · `Private Link` · `Azure Policy` · `Deployment Stacks` · `PowerShell` · `Bash` · `GitHub Actions (OIDC)`

#### [MD-102 Lab Platform](https://github.com/ozmvege/md-102-study-guide) — Endpoint & Intune Curriculum · [Live Platform](https://ozmvege.github.io/md-102-study-guide/)

61-lab curriculum across 13 modules (55 hands-on, 6 walkthroughs · ~49 hours) delivering **83/83 (100%)** machine-checked coverage of the MD-102 exam skills outline.

- **Engineering:** Build-time curriculum & objective validation (`node tools/build.mjs --validate`), 20/5 E5 seat-budget enforcement, 3 Hyper-V Gen 2 VMs (vTPM / Secure Boot) + Android emulator topology, and dynamic tenant-prefix rewriting that works offline directly from `index.html`.
- **Stack:** `Microsoft Intune` · `Microsoft 365 E5` · `Windows Autopilot` · `Cloud PKI` · `Defender for Endpoint` · `PowerShell` · `JavaScript`

#### [OCI Production Stack](https://github.com/ozmvege/OCI-LoadBalancer-SSL-DNS-WAF-NGINX) — Oracle Cloud Infrastructure · [Precursor App](https://github.com/ozmvege/flask-project)

Hardened Flask deployment on Oracle Cloud built around real operational constraints: encrypted edge ingress, elastic scaling, and zero public SSH exposure on application nodes.

- **Architecture:** VCN segmentation, Layer-7 Load Balancer with TLS termination, WAF & DNS Zone, NGINX reverse proxy over Gunicorn, Custom Images, Instance Pools with metric-based autoscaling, and OCI Bastion access.
- **Stack:** `Oracle Cloud (OCI)` · `Layer-7 Load Balancer` · `WAF` · `Bastion` · `NGINX` · `Gunicorn` · `Flask` · `Linux`

---

### Security Tooling & Supporting Repositories

| Repository | Focus | Summary | Stack |
| :--- | :--- | :--- | :--- |
| [**AV-FingerprintCheck**](https://github.com/ozmvege/AV-FingerprintCheck) | Endpoint Security | Enumerates running AV/EDR processes via Windows WMI (`win32_process`) | `C#` · `.NET` |
| [**PythonPortScanner**](https://github.com/ozmvege/PythonPortScanner) | Network Recon | Full-range TCP port scanner (`1–65535`) highlighting common HTTP ports | `Python` · `Sockets` |
| [**day16**](https://github.com/ozmvege/day16) | Security Scripting | Automation script for TryHackMe *Advent of Cyber 2* (Day 16) | `Python` |
| [**CapstroneFrontend**](https://github.com/ozmvege/CapstroneFrontend) | Web Frontend | React SPA with booking & ordering workflows ([Live Demo](https://ozmvege.github.io/CapstroneFrontend/)) | `React 19` · `Tailwind CSS` · `Formik` |
| [**flask-project**](https://github.com/ozmvege/flask-project) | Web / Backend | Flask web app with session auth & SQLite — precursor to the OCI build | `Python` · `Flask` · `SQLite` |
| [**fw-collectoil**](https://github.com/ozmvege/fw-collectoil) | Field Utility | Lightweight JavaScript utility for collecting resources in the field | `JavaScript` |

---

### Certifications & Security Practice

- **Microsoft 365 Certified: Endpoint Administrator Associate (MD-102)** — *Microsoft*
- **Oracle Cloud Infrastructure 2024 Certified Security Professional** — *Oracle (2024)*
- **OCI Architect Associate · OCI Generative AI · OCI Foundations Associate** — *Oracle (2023–2024)*
- **LPI Linux Essentials** — *Linux Professional Institute*
- **Meta Front-End Developer Professional Certificate** — *Meta · Coursera*
- **TryHackMe — Top 1% Global Ranking** ([`tryhackme.com/p/oez`](https://tryhackme.com/p/oez)) — *Enumeration & recon, web exploitation, Linux privilege escalation, and turning offensive findings into WAF, TLS, Bastion, and Private Link hardening.*

---

### Tech & Tooling

**Cloud & Infrastructure**

![Microsoft Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat-square)
![Azure Bicep](https://img.shields.io/badge/Azure_Bicep-005BA1?style=flat-square)
![Oracle Cloud OCI](https://img.shields.io/badge/Oracle_Cloud_OCI-F80000?style=flat-square)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white)
![NGINX](https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Endpoint, Security & Automation**

![Microsoft Intune](https://img.shields.io/badge/Microsoft_Intune-0078D4?style=flat-square)
![TryHackMe](https://img.shields.io/badge/TryHackMe-212C42?style=flat-square&logo=tryhackme&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)

**Languages & Scripting**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C# .NET](https://img.shields.io/badge/C%23_.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Web, Mobile & Data**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)

---

### GitHub Activity

<p align="center">
  <a href="https://github.com/ozmvege">
    <picture>
      <source
        media="(prefers-color-scheme: dark)"
        srcset="https://github-stats-extended.vercel.app/api?username=ozmvege&show_icons=true&include_all_commits=true&hide_rank=true&theme=dark_github&border_radius=6"
      />
      <img
        height="185"
        src="https://github-stats-extended.vercel.app/api?username=ozmvege&show_icons=true&include_all_commits=true&hide_rank=true&theme=light_github&border_radius=6"
        alt="ozmvege GitHub Stats"
      />
    </picture>
  </a>
  <a href="https://github.com/ozmvege">
    <picture>
      <source
        media="(prefers-color-scheme: dark)"
        srcset="https://github-stats-extended.vercel.app/api/top-langs/?username=ozmvege&layout=compact&langs_count=8&card_width=320&size_weight=0.5&count_weight=0.5&theme=dark_github&border_radius=6"
      />
      <img
        height="185"
        src="https://github-stats-extended.vercel.app/api/top-langs/?username=ozmvege&layout=compact&langs_count=8&card_width=320&size_weight=0.5&count_weight=0.5&theme=light_github&border_radius=6"
        alt="ozmvege Top Languages"
      />
    </picture>
  </a>
</p>

<p align="center">
  <a href="https://github.com/ozmvege">
    <picture>
      <source
        media="(prefers-color-scheme: dark)"
        srcset="https://streak-stats.demolab.com/?user=ozmvege&background=0D1117&border=3D444D&stroke=3D444D&ring=4493F8&fire=4493F8&currStreakNum=F0F6FC&sideNums=4493F8&currStreakLabel=9198A1&sideLabels=9198A1&dates=9198A1&border_radius=6"
      />
      <img
        src="https://streak-stats.demolab.com/?user=ozmvege&background=FFFFFF&border=D1D9E0&stroke=D1D9E0&ring=0969DA&fire=0969DA&currStreakNum=1F2328&sideNums=0969DA&currStreakLabel=59636E&sideLabels=59636E&dates=59636E&border_radius=6"
        alt="ozmvege Contribution Streak"
      />
    </picture>
  </a>
</p>

<p align="center">
  <sub>Stats reflect public repositories via <em>GitHub Stats Extended</em> · Contribution streak includes private repository activity.</sub>
</p>
