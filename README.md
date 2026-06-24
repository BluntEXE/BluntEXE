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

A venue management platform for a Final Fantasy XIV community. Next.js web dashboard, Android companion app, and a C# game-client plugin that captures in-game events and syncs them to the dashboard for analytics and payroll. ~115,000 lines (109k TS · 5.7k C#), solo-built since December 2025.

- **Operations:** self-hosted Linux box, 7-container Docker Compose stack, TLS, DNS, firewall, SSH-key-only access
- **Security:** full audit (18 findings, all fixed), nonce-based CSP, rate limiting, hashed API keys, OAuth, CI vulnerability scanning
- **Reliability:** monitoring, log triage, and incident response on my own production system
- **Support:** I triage bugs from real users and ship fixes

📄 **[Engineering case study →](https://github.com/BluntEXE/ffxiv-venue-manager/blob/main/CASE_STUDY.md)**
🏗️ **[Architecture →](https://github.com/BluntEXE/ffxiv-venue-manager/blob/main/apps/web/docs/engineering/architecture.md)**
🔒 **[Security →](https://github.com/BluntEXE/ffxiv-venue-manager/blob/main/apps/web/docs/engineering/security.md)**
📈 **[Scaling →](https://github.com/BluntEXE/ffxiv-venue-manager/blob/main/apps/web/docs/engineering/scaling.md)**

---

### [Starfall Studio](https://github.com/BluntEXE/StarfallStudio)

GPose toolkit for FFXIV. Actor posing, animation, camera, and scene composition in one Dalamud plugin. ~52,000 lines of C#, v0.2.33, actively maintained.

- **Actors:** click-to-select list, world-space transform gizmo, NPC and overworld actor import into GPose
- **Appearance:** MCDF import via Penumbra + Glamourer IPC, NPC appearance import, wetness depth editor
- **Camera:** freecam (WASD + mouse look), angle/pan/FoV editor, zoom delimit, multi-camera support
- **World:** weather, time of day, sky/cloud/star editor, festival flags, environment effects
- **Formats:** Brio-compatible `.pose` files, `.starscn` scenes, `.starproj` projects

---

### [FFXIV Shout Crafter](https://shout.xivvenuemanager.com)

A public tool for FFXIV venue operators to generate `/shout` advertisement commands from Partake event URLs or Discord posts. Parses a dozen format variants (DJ slot styles, time zones, decorated venue names) using a regex pipeline, then lets operators pick which fields to import or keep. Cross-origin auth via shared session cookie lets XIV Venue Manager users save and reload shout templates. Built with Vite, React, TypeScript, and Tailwind.

---

### [XIV Admin](https://github.com/BluntEXE/xiv-admin)

Terminal admin dashboard for xivvenuemanager.com. Ops tooling for a solo-run production system. ~16,000 lines of Python.

- **Stats:** live venue/user/shift counts, auto-refresh every 30s
- **Ops:** Docker container status, log tailing, deploy trigger with streamed output
- **Monitoring:** SSL cert expiry across all subdomains, GlitchTip error feed, Resend email log
- **Health:** MinIO, Partake, Discord, Cloudflare integration pings

---

## Tech I use day-to-day

**Production stack:** Linux · Docker Compose · PostgreSQL · Redis · Nginx · Cloudflare · GitHub Actions

**Web:** TypeScript · React · Next.js · Vite · Prisma · Tailwind

**Other:** C# / .NET · Bash · SQL

**Home lab:** Proxmox VE · Pi-hole · Home Assistant · Plex / Jellyfin · evaluating UniFi

## Currently working on

- 📚 **Google Cybersecurity Professional Certificate** (Coursera, in progress - IT Support completed)
- 🔧 Maintaining [xivvenuemanager.com](https://xivvenuemanager.com) and its users
- 💼 Open to IT roles in the UK - remote or South Wales

## How to reach me

- 📧 [piranwright@protonmail.com](mailto:piranwright@protonmail.com)
- 💬 Discord: `ehno`
- 🐙 [@BluntEXE](https://github.com/BluntEXE)

<sub>The case study and engineering deep-dives in the project repo carry the depth.</sub>
