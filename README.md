<p align="center">
  <img src="./assets/profile-header.svg" alt="Tuncay Ölmez — developer tooling, application security, and local-first systems" width="100%" />
</p>
<p align="center">
  <a href="https://linkedin.com/in/tuncayolmez"><img src="https://img.shields.io/badge/LinkedIn-tuncayolmez-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://www.npmjs.com/~setrathex"><img src="https://img.shields.io/badge/npm-setrathex-CB3837?style=flat-square&logo=npm&logoColor=white" alt="npm" /></a>
  <a href="mailto:tuncay123454@gmail.com"><img src="https://img.shields.io/badge/Email-contact-334155?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<p align="center">
  I build tools that turn vague engineering risk into evidence you can inspect:<br />
  deterministic findings, bounded workflows, and read-only diagnostics.
</p>

## What I build

<table>
  <tr>
    <td width="33%" valign="top">
      <strong>Detect risk early</strong><br /><br />
      Static security analysis, SARIF reporting, archive inspection, and safe-extraction gates before deployment or file writes.
    </td>
    <td width="33%" valign="top">
      <strong>Control complex execution</strong><br /><br />
      Explicit scope, isolated worktrees, bounded operations, deterministic verification, recovery, and independent review.
    </td>
    <td width="33%" valign="top">
      <strong>Keep the evidence local</strong><br /><br />
      Rust, Python, TypeScript, SQLite, and system diagnostics designed to work without unnecessary cloud dependencies.
    </td>
  </tr>
</table>

## Featured projects

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/SetraTheXX/next-secure-check"><img src="./assets/next-secure-check.svg" alt="next-secure-check" width="100%" /></a>
      <br /><br />
      Catches common Next.js security mistakes before deployment without executing the target repository or calling an LLM at scan time. Produces deterministic findings for local review, CI, and SARIF-compatible code scanning.
      <br /><br />
      <strong>Current:</strong> <code>v0.4.1</code> on npm · <code>20 rules</code> · <code>466 tests</code><br />
      <code>TypeScript</code> <code>AST-assisted</code> <code>SARIF 2.1.0</code>
      <br /><br />
      <a href="https://github.com/SetraTheXX/next-secure-check"><strong>View repository →</strong></a>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/SetraTheXX/Codex-Engineering-Workflow-Pack"><img src="./assets/cewp.svg" alt="Codex Engineering Workflow Pack" width="100%" /></a>
      <br /><br />
      Adds an engineering control plane around Codex: approved scope, isolated execution, operation budgets, verification outside the model loop, independent review, recovery, and portable evidence receipts.
      <br /><br />
      <strong>Current:</strong> <code>v0.14.0-beta.1</code> · npm beta<br />
      <code>Node.js 22+</code> <code>Codex plugin</code> <code>local MCP</code>
      <br /><br />
      <a href="https://github.com/SetraTheXX/Codex-Engineering-Workflow-Pack"><strong>View repository →</strong></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/SetraTheXX/Portal-Doctor"><img src="./assets/portaldoctor.svg" alt="PortalDoctor" width="100%" /></a>
      <br /><br />
      Reconstructs XDG portal routing and checks D-Bus and systemd reachability so Linux desktop-integration failures become actionable findings. Read-only by design, with no telemetry or runtime AI.
      <br /><br />
      <strong>Status:</strong> <code>v0.1.0 release-preparation baseline</code> · not tagged<br />
      <code>Rust 2024</code> <code>terminal + JSON</code> <code>read-only</code> <code>15 findings</code>
      <br /><br />
      <a href="https://github.com/SetraTheXX/Portal-Doctor"><strong>View repository →</strong></a>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/SetraTheXX/pagonic"><img src="./assets/pagonic.svg" alt="Pagonic" width="100%" /></a>
      <br /><br />
      Inspects ZIP archives for path traversal, suspicious entries, extreme compression ratios, unsupported methods, and structural errors before extraction. Available as a Python library and CLI from a local checkout.
      <br /><br />
      <strong>Current:</strong> <code>v0.3.0 alpha</code> · local installation · no PyPI release yet<br />
      <code>Python</code> <code>CLI</code> <code>safe extraction</code> <code>JSON + Markdown</code>
      <br /><br />
      <a href="https://github.com/SetraTheXX/pagonic"><strong>View repository →</strong></a>
    </td>
  </tr>
</table>

## Open-source contribution

<table>
  <tr>
    <td valign="top">
      <a href="https://github.com/asamassekou10/ship-safe/pull/161"><img src="https://img.shields.io/badge/Merged-Ship%20Safe%20%23161-2ea44f?style=for-the-badge&logo=github&logoColor=white" alt="Ship Safe pull request 161 merged" /></a>
      <br /><br />
      <strong>MCP/OAuth security checks for Ship Safe</strong><br />
      Contributed four conservative detections covering upstream token passthrough, audience validation, dynamic client registration, and PKCE handling. The work was merged after maintainer review, false-positive hardening, regression testing, and multi-language validation.
      <br /><br />
      <a href="https://github.com/asamassekou10/ship-safe/pull/161"><strong>Read the merged pull request →</strong></a>
    </td>
  </tr>
</table>

## More work

| Project | What it explores | Current state |
| --- | --- | --- |
| **[BioVoid](https://github.com/SetraTheXX/BioVoid)** | Reproducible protein-structure preparation and geometry-based pocket-candidate analysis through a local FastAPI/React application. | `v0.1.0 public source baseline` |
| **[Nihongo Learn](https://github.com/SetraTheXX/nihongo-learn)** | Japanese learning for Turkish-speaking beginners: kana, SM-2 reviews, 31 lessons, mini stories, and N5-style practice. | `usable local MVP` |

> **Scientific boundary:** BioVoid is a research prototype. It is not a clinical, diagnostic, validated binding-prediction, or drug-development system.

## Toolbox

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=111827" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt="C#" />
</p>

<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Next.js-111827?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" />
</p>

<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/npm-CB3837?style=flat-square&logo=npm&logoColor=white" alt="npm" />
</p>

<p>
  <strong>Currently exploring:</strong> Godot/C#, Three.js, Tauri, game systems, and lower-level software architecture.
</p>

## About me

I am a Computer Programming student at Ondokuz Mayıs University in Samsun,
Türkiye. Most of my projects begin as something I want to understand or use,
then move beyond the demo stage through tests, documentation, CI, explicit
limitations, and reproducible verification.

AI-assisted tools are part of my planning and implementation workflow, but they
do not get the final say. Runtime behavior, automated checks, manual review, and
honest evidence remain the release gates.

<p align="center">
  <a href="https://linkedin.com/in/tuncayolmez"><strong>LinkedIn</strong></a>
  &nbsp;·&nbsp;
  <a href="https://www.npmjs.com/~setrathex"><strong>npm</strong></a>
  &nbsp;·&nbsp;
  <a href="mailto:tuncay123454@gmail.com"><strong>Email</strong></a>
</p>
