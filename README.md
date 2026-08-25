<div align="center">

# Samiul Alam Sumel

**Port Operations Technologist + Product Engineer**

*12+ years running port and maritime logistics operations — now building the software that runs them*

[![Portfolio](https://img.shields.io/badge/Portfolio-sasumel.pages.dev-0A66C2?style=flat-square)](https://sasumel.pages.dev/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Samiul_Alam_Sumel-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/samiul-alam-sumel/)
[![Email](https://img.shields.io/badge/Email-sa.sumel91%40gmail.com-333?style=flat-square&logo=gmail&logoColor=white)](mailto:sa.sumel91@gmail.com)

</div>

---

## About

I spend my working life inside a seaport in Bangladesh — 12+ years in wharfrent billing, cargo and vehicle tracking, demurrage calculation, and coordinating with C&F agents. Somewhere along the way I started building the software that the job actually needed and nobody was going to build for us, and kept going.

I'm self-taught, and I build production tools using modern AI-assisted workflows (Claude Code) rather than writing everything by hand from scratch — I design the systems, make the architecture and correctness calls, and validate every output before it ships. The tools below are in daily use by real port staff and C&F agents; that's the part I'd put in front of anyone evaluating this profile.

## What I've shipped into production

These run daily at the port I work at — no demo data, real usage:

- **PortBill** — advance wharfrent calculator for C&F agents: slab-based charges, VAT/levy, inside/outside cargo split, print-ready A4 output.
- **OT Bill Management System** — auto-calculates overtime bills from employee profiles (hourly rate, cumulative date-wise OT), A4 print-ready output.
- **Car Balance Tracker** — daily vehicle position and balance tracking tool.

## Technical builds & practice projects

Self-directed projects demonstrating architecture and full-stack range beyond the day job — clearly labeled where they're practice/portfolio work rather than live products:

- **[pcs-port-system](https://github.com/samiulAsumel/pcs-port-system)** — enterprise port-community-system backend architecture: FastAPI, PostgreSQL, Kafka, Kubernetes (EKS), Terraform. A self-directed exercise in enterprise backend/infra design, not a deployed system.
- **[deskora](https://github.com/samiulAsumel/deskora)** — desk & meeting-room booking marketplace: React Router SSR, Hono API, Cloudflare D1 + Durable Objects for concurrency-safe booking locks.
- **[smart-port-billing-infra](https://github.com/samiulAsumel/smart-port-billing-infra)** — RHEL 9 server infrastructure automation covering the full RHCSA EX200 skill set: LVM, SELinux, firewalld, SSH hardening, Podman, ACLs, log monitoring.
- **[world-kitchen-atlas](https://github.com/samiulAsumel/world-kitchen-atlas)** — a global culinary encyclopedia with client-side search and a light/dark theme.

## Stack

`JavaScript` · `TypeScript` · `Python` · `FastAPI` · `React` · `Cloudflare Workers/Pages/D1` · `PostgreSQL` · `Kafka` · `Linux (RHEL 9)` · `Bash` · `Terraform` · `Kubernetes`

Standard pattern for my production tools: JSON-backed data in a private GitHub repo behind a Cloudflare Worker proxy, deployed on Cloudflare Pages/Workers.

## Currently

Open to remote and freelance work at the intersection of logistics/operations domain expertise and full-stack product engineering — building tools for teams that need someone who understands both the operational problem and how to ship the software for it.
