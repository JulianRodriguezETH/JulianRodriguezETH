[README.md](https://github.com/user-attachments/files/33781241/README.md)
# Julian Andres Rodriguez Garcia

**Systems Engineer · Python Backend · Linux · Security · Founder of Aeis LLC**

I build software for sensitive data and my own products, and I document how I build it.
I care about work that leaves reviewable evidence: running code, tests, documentation,
and labs anyone can reproduce.

---

## Current work

**Software Engineer — SAM, medical billing audit for a public hospital**

- A local, deterministic, *fail-closed* system that audits healthcare invoices against
  Colombian regulations (Res. 2284/2023, Res. 1885/2024, RIPS and electronic invoices)
  before they are filed, and then manages payer objections (glosas) and collections.
- Modular architecture in Python 3.12: a shared core of immutable types, one facade per
  module, and a local API that orchestrates them. Pydantic `frozen` + `extra="forbid"`,
  `mypy --strict`, money as `Decimal` end to end.
- Security by design: no AI in the decision path, identity derived from the JWT, API bound to
  `127.0.0.1` only, every finding cites its legal source, and input files (ZIP, XML, PDF)
  are treated as hostile.
   <!-- add your merged PRs: "Decompressed-size limit against ZIP bombs (#12)",
  "Per-invoice duplicate control in batch processing (#15)", etc. -->

**Founder — [Aeis LLC](https://aeisone.com)**

- **Aeis 1** — AI chord progression generator for DAW producers.
- **Aeis 1.1** — vocal chain preset generator: a from-scratch engine with a YAML preset
  library and server-side free/pro separation.
- **The Beauty App** — iOS marketplace for independent beauty professionals: bookings,
  Mapbox search, Firestore data, and geolocation with Capacitor.
  <!-- add the App Store link -->

---

## Projects

- **homelab** — my home server run like a small production system:
  Proxmox, encrypted Debian VMs, a MikroTik firewall, backups with restore tests, and
  everything documented as code. <!-- link when published -->

<!-- Each new project: what it does, how it does it, and what made it hard or interesting. -->

---

## Toolkit

**Backend**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![uv](https://img.shields.io/badge/uv-DE5FE9?style=for-the-badge&logo=uv&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-555555?style=for-the-badge)

**Mobile & web**

![Capacitor](https://img.shields.io/badge/Capacitor-119EFF?style=for-the-badge&logo=capacitor&logoColor=white)
![Firebase](https://img.shields.io/badge/Firestore-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Mapbox](https://img.shields.io/badge/Mapbox-000000?style=for-the-badge&logo=mapbox&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)

**Operations**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white)
![tmux](https://img.shields.io/badge/tmux-1BB91F?style=for-the-badge&logo=tmux&logoColor=white)

**Security**

![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![gitleaks](https://img.shields.io/badge/gitleaks-555555?style=for-the-badge)
![pip-audit](https://img.shields.io/badge/pip--audit-555555?style=for-the-badge)
![SSH](https://img.shields.io/badge/SSH-555555?style=for-the-badge)
![ufw](https://img.shields.io/badge/ufw-555555?style=for-the-badge)
![Signed commits](https://img.shields.io/badge/Signed_commits-555555?style=for-the-badge)

---

## Education & certifications

- Systems Engineering, Universidad Autonoma de Bucaramanga - final year, expected Dec. 2026
  <!-- each certification with issue date and validity, e.g.:
     CompTIA Security+ (SY0-701) — issued Mon YYYY, valid through Mon YYYY -->

---

## Writing & talks

Upcoming
<!-- Talks, labs or notes already confirmed or in progress, with date. Example: - **Mon DD, YYYY** — Event or place: *Talk title* (format, duration) - **In progress** — `ai-dev-sandbox`: how to work with an AI coding agent inside an isolated VM -->

<!-- Move each item here once it happens, newest first, with date and link. -->

---

## Find me online

[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/julianr1eth)
