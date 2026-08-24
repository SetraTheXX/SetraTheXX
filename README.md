<div align="center">

# Tuncay Ölmez

**I build developer tooling, security scanners, and local-first software — with a focus on testable, maintainable engineering.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-tuncayolmez-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/tuncayolmez)
[![npm](https://img.shields.io/badge/npm-setrathex-CB3837?style=for-the-badge&logo=npm&logoColor=white)](https://www.npmjs.com/~setrathex)
[![Email](https://img.shields.io/badge/Email-contact-22c55e?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tuncay123454@gmail.com)

</div>

---

## About

I am a Computer Programming student at Ondokuz Mayıs University in Samsun,
Türkiye. Most of my projects start as things I want to learn or use myself,
then get pushed beyond the prototype stage with tests, documentation, CI, and a
real release when they are ready.

AI is part of how I plan and write code, but it does not get the final say:
tests, runtime behavior, and manual review remain the gates before anything
ships.

## Selected work

**[next-secure-check](https://github.com/SetraTheXX/next-secure-check)** —
rule-based static security scanner for Next.js. Checks exposed secrets,
authentication and rate-limit gaps, XSS, raw SQL, command execution, and unsafe
uploads without executing scanned code or calling an LLM at scan time.

[![npm](https://img.shields.io/npm/v/next-secure-check?style=flat-square&label=npm)](https://www.npmjs.com/package/next-secure-check)

`v0.4.1 published on npm` · `20 built-in rules` · `466 tests` · `Node.js 20+`
· `bounded same-function analysis` · `Terminal / JSON / Markdown / GitHub / SARIF`

---

**[Codex Engineering Workflow Pack](https://github.com/SetraTheXX/Codex-Engineering-Workflow-Pack)** — a supervision layer for Codex, designed for engineering work that should not run unsupervised. Adds bounded scope, isolated worktrees, verification gates, independent review, recovery controls, and evidence receipts on top of AI-generated code.

[![CI](https://github.com/SetraTheXX/Codex-Engineering-Workflow-Pack/actions/workflows/ci.yml/badge.svg)](https://github.com/SetraTheXX/Codex-Engineering-Workflow-Pack/actions/workflows/ci.yml)

`v0.14.0-beta.1` · `Node.js 22+` · `npm beta CLI` · `Codex plugin` · `local MCP bridge` · `Coordinator Mode` · `versioned workflow runtime`

---

**[BioVoid](https://github.com/SetraTheXX/BioVoid)** — local research prototype for protein-structure preparation and geometry-based pocket analysis, combining a Python pipeline with a FastAPI/React front end and a bounded Mol* viewer.

`v0.1.0 public source baseline` · `Python 3.12–3.13` · `FastAPI / React` · `Mol* viewer`

*Research prototype — not a clinical, diagnostic, validated binding-prediction, or drug-development tool.*

---

**[Pagonic](https://github.com/SetraTheXX/pagonic)** — *inspect before you extract.* A Python ZIP toolkit that flags path traversal, suspicious entries, extreme compression ratios, unsupported methods, and structural archive problems before you extract anything untrusted.

`v0.3.0 public alpha` · `local installation` · `CLI` · `optional PyQt6 GUI` · `no PyPI or TestPyPI package yet`

<details>
<summary><strong>Also building</strong></summary>
<br>

- **[PortalDoctor](https://github.com/SetraTheXX/Portal-Doctor)** — read-only Rust diagnostic CLI for XDG Desktop Portal, Wayland, D-Bus, and systemd user sessions. `v0.1.0` release-preparation baseline, not tagged yet.
- **[Nihongo Learn](https://github.com/SetraTheXX/nihongo-learn)** — Japanese-learning app for Turkish speakers with kana practice, SM-2 spaced repetition, quizzes, and a 31-lesson A1 course. Usable local MVP.
- **[Portfolio source](https://github.com/SetraTheXX/setrathex-portfolio)** — source repository for a bilingual portfolio built with Next.js, TypeScript, Tailwind CSS, and Framer Motion.

</details>

---

## Open-source contributions

Four MCP/OAuth security detections — token passthrough, audience validation,
dynamic client registration, and PKCE — merged into **[Ship Safe](https://github.com/asamassekou10/ship-safe/pull/161)** after maintainer review, false-positive hardening, and regression testing.

## Stack

**Languages** — TypeScript, JavaScript, Python, Rust, C#  
**Backend & web** — Node.js, Next.js/React, FastAPI, SQLite  
**Tooling** — Git, GitHub Actions, Docker, npm  
**Currently learning** — Godot, Three.js, Tauri, and lower-level systems architecture
