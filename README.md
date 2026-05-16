<h1 align="center">Hi, I'm Piran 👋</h1>

<p align="center"><em>Known as <strong>Ehno</strong> in the FFXIV community</em></p>

<p align="center">
  <em>Self-taught full-stack builder · IT Support candidate · UK</em>
</p>

<p align="center">
  <a href="https://xivvenuemanager.com">
    <img alt="Live site" src="https://img.shields.io/badge/live-xivvenuemanager.com-success">
  </a>
  <img alt="Location" src="https://img.shields.io/badge/UK-Wales-blue">
  <img alt="Status" src="https://img.shields.io/badge/seeking-IT_Roles-orange">
</p>

---

## About me

3+ years in regulated banking (Quality Analyst, Fraud Advisor), remote and hybrid. I build full-stack software in my own time - designed, deployed, and operated by me, which means I'm also the one debugging it at 2am when it breaks. I'm moving into IT full-time: infrastructure, networking, software, or hardware.

## Projects

### [XIV Venue Manager](https://github.com/BluntEXE/ffxiv-venue-manager) · [xivvenuemanager.com](https://xivvenuemanager.com)

A venue management platform for a Final Fantasy XIV community. Next.js web dashboard paired with a C# game-client plugin that captures in-game events and syncs them to the dashboard for analytics and payroll. ~24,400 lines, solo-built since December 2025.

- **Operations:** self-hosted Linux box, 7-container Docker Compose stack, TLS, DNS, firewall, SSH-key-only access
- **Security:** full audit (18 findings, all fixed), nonce-based CSP, rate limiting, hashed API keys, OAuth, CI vulnerability scanning
- **Reliability:** monitoring, log triage, and incident response on my own production system
- **Support:** I triage bugs from real users and ship fixes

📄 **[Engineering case study →](https://github.com/BluntEXE/ffxiv-venue-manager/blob/main/CASE_STUDY.md)**
🏗️ **[Architecture →](https://github.com/BluntEXE/ffxiv-venue-manager/blob/main/apps/web/docs/engineering/architecture.md)**
🔒 **[Security →](https://github.com/BluntEXE/ffxiv-venue-manager/blob/main/apps/web/docs/engineering/security.md)**
📈 **[Scaling →](https://github.com/BluntEXE/ffxiv-venue-manager/blob/main/apps/web/docs/engineering/scaling.md)**

---

### [FFXIV Shout Crafter](https://shout.xivvenuemanager.com)

A public tool for FFXIV venue operators to generate `/shout` advertisement commands from Partake event URLs or Discord posts. Parses a dozen format variants (DJ slot styles, time zones, decorated venue names) using a regex pipeline, then lets operators pick which fields to import or keep. Cross-origin auth via shared session cookie lets XIV Venue Manager users save and reload shout templates. Built with Vite, React, TypeScript, and Tailwind.

---

## Tech I use day-to-day

**Production stack:** Linux · Docker Compose · PostgreSQL · Redis · Nginx · Cloudflare · GitHub Actions

**Web:** TypeScript · React · Next.js · Vite · Prisma · Tailwind

**Other:** C# / .NET · Bash · SQL

**Home lab:** Proxmox VE · Pi-hole · Home Assistant · Plex / Jellyfin · evaluating UniFi

## Currently working on

- 📚 **Google IT Support Professional Certificate** (then CompTIA A+, Network+, Security+)
- 🔧 Maintaining [xivvenuemanager.com](https://xivvenuemanager.com) and its users
- 💼 Open to IT roles in the UK - remote or South Wales

## How to reach me

- 📧 [piranwright@protonmail.com](mailto:piranwright@protonmail.com)
- 💬 Discord: `ehno`
- 🐙 [@BluntEXE](https://github.com/BluntEXE)

<sub>The case study and engineering deep-dives in the project repo carry the depth.</sub>
