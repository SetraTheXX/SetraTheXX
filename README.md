<div align="center">

# Tuncay Ölmez

**Developer Tooling · Application Security · Local-First Systems**

I build developer-security tools that turn vague engineering risk into
**deterministic checks, inspectable evidence, and reproducible workflows.**

<br />

<a href="https://linkedin.com/in/tuncayolmez">LinkedIn</a>
  ·   <a href="https://www.npmjs.com/~setrathex">npm</a>
  ·   <a href="mailto:removed@localhost">Email</a>

<br /><br />

<a href="https://github.com/SetraTheXX/next-secure-check"><strong>next-secure-check</strong></a>
  ·   <a href="https://github.com/SetraTheXX/Portal-Doctor"><strong>PortalDoctor</strong></a>
  ·   <a href="https://github.com/SetraTheXX/pagonic"><strong>Pagonic</strong></a>

</div>

---

## About

I'm a Computer Programming student at **Ondokuz Mayıs University** in Samsun, Türkiye, focused on developer tooling, application security, and local-first systems.

I like building tools with explicit boundaries:

**scope → implementation → verification → evidence**

AI is part of my engineering workflow, but generated code is not the acceptance criterion. Tests, independent review, and reproducible runtime evidence decide what ships.

---

## Featured projects

<table>
<tr>
<td width="50%" valign="top">

### [next-secure-check](https://github.com/SetraTheXX/next-secure-check)

Deterministic security checks for **Next.js** projects.

Scan locally or in CI and produce terminal, JSON, Markdown, GitHub Summary, or SARIF evidence — without executing the scanned repository or requiring an LLM at runtime.

**Current release**
[`v0.6.0`](https://github.com/SetraTheXX/next-secure-check/releases/tag/v0.6.0) · npm · 25 rules · 600 tests

**Verification**
Secure fixture: `99/100`
Vulnerable fixture: `26 findings`

**Integrations**
`npx` · GitHub Summary · SARIF · GitHub Action [`v1.2.0`](https://github.com/SetraTheXX/next-secure-check/releases/tag/v1.2.0)

`TypeScript` `AST-assisted` `bounded flow`

<br />

[**Repository →**](https://github.com/SetraTheXX/next-secure-check)

</td>
<td width="50%" valign="top">

### [PortalDoctor](https://github.com/SetraTheXX/Portal-Doctor)

A read-only Linux diagnostic tool for **XDG Desktop Portal, Wayland, D-Bus, systemd, PipeWire, and WirePlumber** failures.

Instead of asking users to guess which desktop component is broken, PortalDoctor reconstructs and explains the routing path.

**Current release**
[`v0.2.1`](https://github.com/SetraTheXX/Portal-Doctor/releases/tag/v0.2.1) · [crates.io](https://crates.io/crates/portaldoctor) · Linux x86_64

**Boundary**
Stable releases remain read-only. Explicit probes stay development-only on `main`.

**Output**
Terminal · JSON · Markdown · [demo](https://github.com/SetraTheXX/Portal-Doctor/blob/v0.2.1/docs/assets/portaldoctor-demo.gif)

`Rust 2024` `Linux diagnostics` `read-only`

<br />

[**Repository →**](https://github.com/SetraTheXX/Portal-Doctor)

</td>
</tr>

<tr>
<td width="50%" valign="top">

### [Pagonic](https://github.com/SetraTheXX/pagonic)

Inspect ZIP archives **before extraction**.

Pagonic detects path traversal, suspicious entries, extreme compression ratios, unsupported methods, and structural errors before files are written to disk.

**Current release**
[`v0.5.1`](https://github.com/SetraTheXX/pagonic/releases/tag/v0.5.1) · [PyPI](https://pypi.org/project/pagonic/) · wheel + sdist

**Workflow**

`inspect` → `verify` → `safe-extract`

**Output**
Deterministic reports · policy gates · JSON · Markdown

`Python` `CLI` `safe extraction`

<br />

[**Repository →**](https://github.com/SetraTheXX/pagonic)

</td>
<td width="50%" valign="top">

### [Codex Engineering Workflow Pack](https://github.com/SetraTheXX/Codex-Engineering-Workflow-Pack)

A local-first control plane around Codex.

Approve scope, execute inside an isolated worktree, verify outside the model loop, require independent review, and leave behind a portable receipt.

**Current release**
[`v0.14.0`](https://github.com/SetraTheXX/Codex-Engineering-Workflow-Pack/releases/tag/v0.14.0) · npm · GitHub release

**Workflow**

`plan` → `approve` → `execute` → `verify` → `review` → `receipt`

`Node.js 22+` `Codex` `local MCP`

<br />

[**Repository →**](https://github.com/SetraTheXX/Codex-Engineering-Workflow-Pack)

</td>
</tr>
</table>

---

## Open-source contributions

I prefer narrow, reviewable upstream fixes with regression coverage.

| Project                | Contribution                                                     | Focus                                                          |
| ---------------------- | ---------------------------------------------------------------- | -------------------------------------------------------------- |
| **conftest**           | [#1413](https://github.com/open-policy-agent/conftest/pull/1413) | Apply `--ignore` to explicitly provided files                  |
| **gosec**              | [#1733](https://github.com/securego/gosec/pull/1733)             | Deterministic, bounded taint caller traversal                  |
| **codex-with-chatgpt** | [#26](https://github.com/XiaoDuoYa/codex-with-chatgpt/pull/26)   | OAuth pairing-page HTML hardening and browser security headers |
| **cargo-deny**         | [#893](https://github.com/EmbarkStudios/cargo-deny/pull/893)     | Sparse registry matching for literal IP hosts                  |
| **OWASP Noir**         | [#2657](https://github.com/owasp-noir/noir/pull/2657)            | Vercel specification analyzer functional coverage              |

<details>
<summary><strong>More merged contributions</strong></summary>

<br />

| Project       | Contribution                                                | Focus                     |
| ------------- | ----------------------------------------------------------- | ------------------------- |
| **Ship Safe** | [#161](https://github.com/asamassekou10/ship-safe/pull/161) | MCP/OAuth security checks |

</details>

---

## Other work

### BioVoid · private research prototype

Local computational research into reproducible **full-heavy-atom protein-structure analysis** and geometry-based pocket-candidate generation.

The source, datasets, and intermediate research artifacts remain private while research and independent review continue.

<details>
<summary><strong>Research boundary</strong></summary>

<br />

BioVoid produces unvalidated geometry-based pocket candidates and diagnostics.

Its outputs are **not** clinical results, diagnostic claims, validated binding predictions, drug-development results, or drug-discovery claims.

</details>

<br />

### [Nihongo Learn](https://github.com/SetraTheXX/nihongo-learn)

Japanese learning software for Turkish-speaking beginners.

Kana practice, SM-2 reviews, 31 lessons, mini stories, and N5-style exercises.

`usable local MVP`

---

## Toolbox

**Languages**

`TypeScript` · `Python` · `Rust`

**Runtime & application**

`Node.js` · `Next.js` · `React` · `FastAPI` · `SQLite`

**Engineering**

`GitHub Actions` · `Docker` · `npm` · `Linux` · `Git`

---

## Currently interested in

Developer tooling, application security, secure software supply chains, local-first AI workflows, deterministic analysis, and developer-facing security automation.

---

<div align="center">

### Build small. Verify aggressively. Leave evidence.

</div>
