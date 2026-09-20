<div align="center">

# Tuncay Ölmez

### Developer Tooling · Application Security · Local-First Systems

I build developer-security tools and local-first workflows that turn vague engineering risk into **deterministic checks, inspectable evidence, and reproducible systems**.

<br />

<a href="https://linkedin.com/in/tuncayolmez">
  <img src="https://img.shields.io/badge/LinkedIn-Tuncay%20Ölmez-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="https://www.npmjs.com/~setrathex">
  <img src="https://img.shields.io/badge/npm-setrathex-CB3837?style=for-the-badge&logo=npm&logoColor=white" alt="npm" />
</a>
<a href="mailto:removed@localhost">
  <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>

<br /><br />

<a href="https://github.com/SetraTheXX/next-secure-check"><strong>next-secure-check</strong></a>
 ·  <a href="https://github.com/SetraTheXX/Portal-Doctor"><strong>PortalDoctor</strong></a>
 ·  <a href="https://github.com/SetraTheXX/pagonic"><strong>Pagonic</strong></a>
 ·  <a href="https://github.com/SetraTheXX/Codex-Engineering-Workflow-Pack"><strong>CEWP</strong></a>

</div>

---

## About

I'm a **Computer Programming student at Ondokuz Mayıs University** in Samsun, Türkiye, focused on developer tooling, application security, local-first systems, and AI-assisted software engineering.

I prefer systems with explicit boundaries and evidence-backed outcomes:

**scope → implementation → verification → review → evidence**

AI helps me move faster, but generated code is never the acceptance criterion. Tests, reproducible runtime evidence, and independent review decide what ships.

---

## Featured projects

<table>
<tr>
<td width="50%" valign="top">

### 🛡️ [next-secure-check](https://github.com/SetraTheXX/next-secure-check)

Deterministic security checks for **Next.js** projects.

Scan locally or in CI and produce actionable security evidence without executing the scanned repository or requiring an LLM at runtime.

<br />

<a href="https://github.com/SetraTheXX/next-secure-check/releases/tag/v0.6.0">
<img src="https://img.shields.io/badge/release-v0.6.0-2ea44f?style=flat-square" alt="release" />
</a>
<img src="https://img.shields.io/badge/rules-25-blue?style=flat-square" alt="25 rules" />
<img src="https://img.shields.io/badge/tests-600-blue?style=flat-square" alt="600 tests" />
<img src="https://img.shields.io/badge/runtime%20LLM-none-success?style=flat-square" alt="No runtime LLM" />

<br /><br />

**Outputs**
Terminal · JSON · Markdown · GitHub Summary · SARIF

**Proof**
Secure fixture `99/100` · vulnerable fixture `26 findings`

**Use**
`npx` one-off scans · CI · GitHub Action [`v1.2.0`](https://github.com/SetraTheXX/next-secure-check/releases/tag/v1.2.0)

<br />

`TypeScript` `AST-assisted` `bounded flow` `SARIF`

<br /><br />

[**View repository →**](https://github.com/SetraTheXX/next-secure-check)

</td>
<td width="50%" valign="top">

### 🐧 [PortalDoctor](https://github.com/SetraTheXX/Portal-Doctor)

A read-only Linux diagnostic tool for **XDG Desktop Portal, Wayland, D-Bus, systemd, PipeWire, and WirePlumber** failures.

Instead of asking users to guess which desktop component failed, PortalDoctor reconstructs and explains the routing path.

<br />

<a href="https://github.com/SetraTheXX/Portal-Doctor/releases/tag/v0.2.1">
<img src="https://img.shields.io/badge/release-v0.2.1-2ea44f?style=flat-square" alt="release" />
</a>
<a href="https://crates.io/crates/portaldoctor">
<img src="https://img.shields.io/badge/crates.io-portaldoctor-orange?style=flat-square&logo=rust" alt="crates.io" />
</a>
<img src="https://img.shields.io/badge/stable-read--only-success?style=flat-square" alt="read only" />

<br /><br />

**Boundary**
Stable releases are read-only. Explicit active probes remain development-only on `main`.

**Output**
Terminal · JSON · Markdown

**Demo**
[Terminal flow →](https://github.com/SetraTheXX/Portal-Doctor/blob/v0.2.1/docs/assets/portaldoctor-demo.gif)

<br />

`Rust 2024` `Wayland` `D-Bus` `Linux diagnostics`

<br /><br />

[**View repository →**](https://github.com/SetraTheXX/Portal-Doctor)

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 📦 [Pagonic](https://github.com/SetraTheXX/pagonic)

Inspect ZIP archives **before extraction**.

Pagonic detects path traversal, suspicious entries, extreme compression ratios, unsupported methods, and structural errors before files are written.

<br />

<a href="https://github.com/SetraTheXX/pagonic/releases/tag/v0.5.1">
<img src="https://img.shields.io/badge/release-v0.5.1-2ea44f?style=flat-square" alt="release" />
</a>
<a href="https://pypi.org/project/pagonic/">
<img src="https://img.shields.io/badge/PyPI-pagonic-3775A9?style=flat-square&logo=pypi&logoColor=white" alt="PyPI" />
</a>
<img src="https://img.shields.io/badge/extraction-policy%20gated-success?style=flat-square" alt="policy gated" />

<br /><br />

**Workflow**

`inspect` → `verify` → `safe-extract`

**Detects**

Path traversal · suspicious entries · extreme compression ratios · unsupported methods · malformed structures

**Output**

Deterministic reports · policy gates · JSON · Markdown

<br />

`Python` `CLI` `ZIP security` `safe extraction`

<br /><br />

[**View repository →**](https://github.com/SetraTheXX/pagonic)

</td>
<td width="50%" valign="top">

### ⚙️ [Codex Engineering Workflow Pack](https://github.com/SetraTheXX/Codex-Engineering-Workflow-Pack)

A local-first control plane around Codex.

Approve scope, execute inside an isolated worktree, verify outside the model loop, require independent review, and leave behind a portable receipt.

<br />

<a href="https://github.com/SetraTheXX/Codex-Engineering-Workflow-Pack/releases/tag/v0.14.0">
<img src="https://img.shields.io/badge/release-v0.14.0-2ea44f?style=flat-square" alt="release" />
</a>
<img src="https://img.shields.io/badge/runtime-Node.js%2022+-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
<img src="https://img.shields.io/badge/workflow-local--first-blueviolet?style=flat-square" alt="local first" />

<br /><br />

**Workflow**

`plan` → `approve` → `execute` → `verify` → `review` → `receipt`

**Design**

Explicit scope · isolated execution · external verification · independent review · portable receipts

<br />

`Node.js 22+` `Codex` `local MCP` `worktrees`

<br /><br />

[**View repository →**](https://github.com/SetraTheXX/Codex-Engineering-Workflow-Pack)

</td>
</tr>
</table>

---

## Open-source contributions

I prefer **small, reviewable upstream fixes with regression coverage**.

| Project                |                           Pull request                           | Focus                                                          |
| :--------------------- | :--------------------------------------------------------------: | -------------------------------------------------------------- |
| **conftest**           | [#1413](https://github.com/open-policy-agent/conftest/pull/1413) | Apply `--ignore` to explicitly provided files                  |
| **gosec**              |       [#1733](https://github.com/securego/gosec/pull/1733)       | Deterministic, bounded taint caller traversal                  |
| **codex-with-chatgpt** |  [#26](https://github.com/XiaoDuoYa/codex-with-chatgpt/pull/26)  | OAuth pairing-page HTML hardening and browser security headers |
| **cargo-deny**         |   [#893](https://github.com/EmbarkStudios/cargo-deny/pull/893)   | Sparse registry matching for literal IP hosts                  |
| **OWASP Noir**         |       [#2657](https://github.com/owasp-noir/noir/pull/2657)      | Vercel specification analyzer functional coverage              |

<details>
<summary><strong>More merged contributions</strong></summary>

<br />

| Project       |                         Pull request                        | Focus                     |
| :------------ | :---------------------------------------------------------: | ------------------------- |
| **Ship Safe** | [#161](https://github.com/asamassekou10/ship-safe/pull/161) | MCP/OAuth security checks |

</details>

---

## Tech stack

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=ts,py,rust,nodejs,nextjs,react,fastapi,sqlite,docker,githubactions,npm,linux,git&theme=dark&perline=13" />
  <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=ts,py,rust,nodejs,nextjs,react,fastapi,sqlite,docker,githubactions,npm,linux,git&theme=light&perline=13" />
  <img src="https://skillicons.dev/icons?i=ts,py,rust,nodejs,nextjs,react,fastapi,sqlite,docker,githubactions,npm,linux,git&theme=dark&perline=13" alt="Technology stack" />
</picture>

<br />

**Languages**
TypeScript · Python · Rust

**Runtime & application**
Node.js · Next.js · React · FastAPI · SQLite

**Engineering**
Linux · Git · GitHub Actions · Docker · npm

</div>

---

## Other work

### 🧬 BioVoid

**Private research prototype**

A local computational research project exploring reproducible **full-heavy-atom protein-structure analysis** and geometry-based pocket-candidate generation.

Source code, datasets, and intermediate research artifacts remain private while research and independent review continue.

<details>
<summary><strong>Scientific boundary</strong></summary>

<br />

BioVoid produces unvalidated geometry-based pocket candidates and diagnostics.

Its outputs are not clinical results, diagnostic claims, validated binding predictions, drug-development results, or drug-discovery claims.

</details>

<br />

### 🇯🇵 [Nihongo Learn](https://github.com/SetraTheXX/nihongo-learn)

Japanese learning software designed for Turkish-speaking beginners.

Kana practice · SM-2 reviews · 31 lessons · mini stories · N5-style exercises

<img src="https://img.shields.io/badge/state-usable%20local%20MVP-blue?style=flat-square" alt="usable local MVP" />

---

## Current interests

`Developer Tooling`
 
`Application Security`
 
`Secure Software Supply Chains`
 
`Local-First AI`
 
`Deterministic Analysis`
 
`Security Automation`

---

<div align="center">

### Build deliberately. Verify independently. Leave evidence.

<sub>Developer tooling · application security · local-first engineering</sub>

</div>
