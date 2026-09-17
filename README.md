<h1 align="center">Samiul Alam Sumel</h1>
<h3 align="center">Product Engineer for Real-World Operations</h3>

<p align="center">
12+ years running port &amp; maritime logistics operations — now building the software that runs them.
</p>

<p align="center">
<a href="https://sasumel.pages.dev/"><img src="https://img.shields.io/badge/Portfolio-sasumel.pages.dev-0A66C2?style=flat-square" alt="Portfolio"/></a>
<a href="https://linkedin.com/in/samiul-alam-sumel"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:sa.sumel91@gmail.com"><img src="https://img.shields.io/badge/Email-sa.sumel91%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
<img src="https://img.shields.io/badge/Open%20to-Remote%20Work%20Worldwide-2ea44f?style=flat-square" alt="Open to remote work"/>
</p>

---

### About

I spend my working life inside a seaport in Bangladesh — 12+ years in wharfrent billing, cargo and vehicle tracking, demurrage calculation, and coordinating with C&F agents. Somewhere along the way I started building the software that the job actually needed and nobody was going to build for us, and kept going.

I'm self-taught, and I build production tools using modern AI-assisted workflows (Claude Code) rather than writing everything by hand from scratch — I design the systems, make the architecture and correctness calls, and validate every output before it ships. The tools below are in daily use by real port staff and C&F agents; that's the part I'd put in front of anyone evaluating this profile.

Most developers learn software first. I learned the operation first — which means I start from the actual workflow and business rules, not just the technology.

```
PROBLEM → REQUIREMENT → BUSINESS RULES → SYSTEM → SOFTWARE → REAL USERS
```

---

### 🚢 What I've Shipped Into Production

These run daily at the port I work at — no demo data, real usage.

<table>
<tr>
<td width="33%" valign="top">

**[Port Billing Calculator (portbill)](https://portbill.pages.dev/)**
🟢 LIVE — DAILY USE

Advance wharfrent calculator for C&F agents: slab-based charges, VAT/levy, inside/outside cargo split, print-ready A4 output.

[Source](https://github.com/samiulAsumel/portbill) · [Case study](https://sasumel.pages.dev/projects/portbill.html)

</td>
<td width="33%" valign="top">

**[CarView — Car Balance Tracker](https://carview.pages.dev/)**
🟢 LIVE — DAILY USE

Daily vehicle position and balance tracking for the whole Traffic Department — replaced one person's private Excel file with a shared, version-controlled system, plus a 7-chart analytics dashboard.

[Source](https://github.com/samiulAsumel/carview) · [Case study](https://sasumel.pages.dev/projects/carview.html)

</td>
<td width="33%" valign="top">

**[OT Bill Management System](https://otbill.pages.dev/)**
🟢 LIVE — DAILY USE

Auto-calculates overtime bills from employee profiles (hourly rate, cumulative date-wise OT) — turned a fully manual, multi-step process into one data-entry point.

[Source](https://github.com/samiulAsumel/otbill) · [Case study](https://sasumel.pages.dev/projects/otbill.html)

</td>
</tr>
</table>

### 🛠️ Real Products

Shipped and live — real products, just not tied to Mongla Port's daily coworker workflows.

| Project | Status | What it does |
|---|---|---|
| **[Client Intake Form](https://clif91.pages.dev/)** | 🟢 Live — daily use | Turns a scattered email/chat back-and-forth into one structured sheet that becomes the actual scope of the quotation. |
| **[SalahSync](https://salahsync.pages.dev/)** | 🟢 Live — daily use | Set one anchor — Fajr time and office hours — and the rest of the day's schedule, prayer to sleep, recalculates itself. |
| **[World Kitchen Atlas](https://kitchenatlas.pages.dev/)** | 🟢 Live | A culinary encyclopedia that rates its own confidence per dish instead of presenting uncertain food history as fact. |

### 🤖 Product Engineering (AI-Focused)

| Project | Stack | Notes |
|---|---|---|
| **[Outreach Copilot](https://outreach-copilot.pages.dev/)** | TypeScript, Workers AI, D1 | AI-drafted cold outreach from a saved resume and a target company — email, LinkedIn, WhatsApp, or cover letter. Every send stays manual. |
| **[JARVIS](https://github.com/samiulAsumel/jarvis)** | FastAPI, Multi-LLM Routing, NixOS | Self-hosted personal AI assistant with multi-model routing (Groq, OpenRouter, Claude, Gemini, local Ollama), voice I/O, and persistent memory. Public source, no demo. |

### 🧪 Engineering Labs / Practice

Self-directed Bash automation practice — not job-critical production work, listed for transparency.

[`auto-deploy-pipeline`](https://github.com/samiulAsumel/auto-deploy-pipeline) · [`auto-ssl-manager`](https://github.com/samiulAsumel/auto-ssl-manager) · [`log-analyzer-alert`](https://github.com/samiulAsumel/log-analyzer-alert)

### 🏗️ Practice / Architecture Exercises

Self-directed projects demonstrating architecture and full-stack range beyond the day job:

- **pcs-port-system** — enterprise port-community-system backend architecture (FastAPI, PostgreSQL, Kafka, Kubernetes/EKS, Terraform) — a design exercise, not a deployed system.
- **deskora** — desk & meeting-room booking marketplace (React Router SSR, Hono API, Cloudflare D1 + Durable Objects for concurrency-safe booking locks).
- **smart-port-billing-infra** — RHEL 9 server infrastructure automation covering the RHCSA EX200 skill set (LVM, SELinux, firewalld, SSH hardening, Podman, ACLs, log monitoring).

---

### ⚙️ Skills, Honestly Tiered

*Proven through shipped projects, working knowledge, and current active learning — not one undifferentiated list.*

**Product Engineering**
- Proven: `HTML5 (Semantic)` `CSS3` `JavaScript (ES6+)` `DOM & Events` `ES Modules` `React (Hooks, Context)`
- Working knowledge: `Tailwind CSS` `React Router` `React Hook Form` `TanStack Query` `Next.js App Router` `REST APIs` `JWT / Firebase Auth` `Stripe`

**Domain Systems**
- Port Billing & Tariff Systems · Wharfrent/VAT/Levy Calculation · Cargo & Vessel Tracking · Workflow Automation · C&F Agent Workflows · Business-Rule Modeling
- Proven through `portbill`, `carview` & `otbill` — all three still in daily use.

**Cloud & Deployment**
- Proven: `Cloudflare Pages` `Cloudflare Workers` `PWA Development`
- Working knowledge: `Firebase Hosting` `Netlify`

**Linux & Automation**
- `Bash Scripting` `Linux Administration (Ubuntu)` `systemd` `Cron & Timers` `Monitoring & Alerting Scripts`
- Proven through `auto-deploy-pipeline`, `auto-ssl-manager` & `log-analyzer-alert`.

**Data**
- Proven: `Cloudflare D1` `Excel Export` `Chart.js Analytics`
- Working knowledge: `MongoDB (Atlas)` `Aggregation Pipeline`

**Development Workflow**
- `Git & GitHub (Branching, PRs)` `AI-Assisted Development (Claude Code)`

**Currently learning:** `TypeScript` `Node / Express (depth)` `Testing` `Docker` `CI/CD` `AI Product Engineering` — see the [Engineering Roadmap](https://sasumel.pages.dev/#roadmap).

---

### 🧭 How I Build

> A job starts with a conversation, not a keyboard.

1. **Working from requirements** — talk first, build second. Before any design or code, I go through what the person or team actually needs, who touches the workflow, and where it breaks down.
2. **Automate the manual step** — find the part of a running process still done by hand (a paper form, a shared spreadsheet, a repeated recalculation) and replace it with a deployed tool the whole team can use.
3. **Solve the problem, not just the request** — if the stated request doesn't fully solve it, I say so before building it anyway.
4. **AI is the accelerator, engineering is the responsibility** — AI gets me from a written requirement to working code faster. It doesn't decide what the product should do, doesn't know the business rules (slab charges, VAT, levy, cumulative OT), and doesn't validate itself — every rule and edge case is manually tested against reality before anything ships.

---

### 🧑‍💼 Background

**Senior Outdoor Assistant — Traffic Department, Revenue Branch**, Mongla Port Authority — *Nov 2017–Present*
Wharfrent billing, cargo & vehicle tracking, revenue reporting — the source of `portbill`, `carview`, and `otbill`.

**Junior Outdoor Assistant — Port & Terminal Operations**, Mongla Port Authority — *Nov 2013–Nov 2017*
Foundation of a 12-year uninterrupted career at Bangladesh's second-largest international seaport.

**Currently:** open to remote and freelance work at the intersection of logistics/operations domain expertise and full-stack product engineering.

---

### 📫 Let's Connect

<p align="left">
<a href="https://sasumel.pages.dev/"><img src="https://img.shields.io/badge/Portfolio-sasumel.pages.dev-000000?style=for-the-badge" alt="Portfolio"/></a>
<a href="https://linkedin.com/in/samiul-alam-sumel"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:sa.sumel91@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

- 📍 Mongla, Bangladesh — no time zone constraints, available worldwide
- 💼 Open to: Product Engineer · Port/Logistics-Tech · Full-Stack Developer · Freelance & Contract
- 📧 sa.sumel91@gmail.com

<p align="center"><sub>Every project above is live and its source is public — open any of them and judge for yourself.</sub></p>
