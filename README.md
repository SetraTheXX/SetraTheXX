<div align="center">

# Tuncay Ölmez

### Developer Tooling · Application Security · Local-First Systems

I build tools that turn vague engineering risk into evidence you can inspect:
deterministic findings, bounded workflows, and read-only diagnostics.

[LinkedIn](https://linkedin.com/in/tuncayolmez) ·
[npm](https://www.npmjs.com/~setrathex) ·
[Email](mailto:tuncay123454@gmail.com)

</div>

---

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
      <h3>next-secure-check</h3>
      Catches common Next.js security mistakes before deployment without executing the target repository or calling an LLM at scan time. Produces deterministic findings for local review, CI, and SARIF-compatible code scanning.
      <br /><br />
      <strong>Current:</strong> <code>v0.4.1</code> on npm · <code>20 rules</code> · <code>466 tests</code><br />
      <code>TypeScript</code> <code>AST-assisted</code> <code>SARIF 2.1.0</code>
      <br /><br />
      <a href="https://github.com/SetraTheXX/next-secure-check"><strong>View repository →</strong></a>
    </td>
    <td width="50%" valign="top">
      <h3>Codex Engineering Workflow Pack</h3>
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
      <h3>PortalDoctor</h3>
      Reconstructs XDG portal routing and checks D-Bus and systemd reachability so Linux desktop-integration failures become actionable findings. Read-only by design, with no telemetry or runtime AI.
      <br /><br />
      <strong>Status:</strong> <code>v0.1.0 release-preparation baseline</code> · not tagged<br />
      <code>Rust 2024</code> <code>terminal + JSON</code> <code>read-only</code> <code>15 findings</code>
      <br /><br />
      <a href="https://github.com/SetraTheXX/Portal-Doctor"><strong>View repository →</strong></a>
    </td>
    <td width="50%" valign="top">
      <h3>Pagonic</h3>
      Inspects ZIP archives for path traversal, suspicious entries, extreme compression ratios, unsupported methods, and structural errors before extraction. Available as a Python library and CLI from a local checkout.
      <br /><br />
      <strong>Current:</strong> <code>v0.3.0 alpha</code> · local installation · no PyPI release yet<br />
      <code>Python</code> <code>CLI</code> <code>safe extraction</code> <code>JSON + Markdown</code>
      <br /><br />
      <a href="https://github.com/SetraTheXX/pagonic"><strong>View repository →</strong></a>
    </td>
  </tr>
</table>

## Open-source contributions

Contributed four conservative MCP/OAuth security detections to Ship Safe. The
work was merged after maintainer review, false-positive hardening, regression
testing, and multi-language validation.

| Project | Pull request | Focus |
| --- | --- | --- |
| Ship Safe | [#161](https://github.com/asamassekou10/ship-safe/pull/161) | MCP/OAuth security checks |

<details>
<summary><strong>View contribution details</strong></summary>
<br />

- **Token passthrough** — detects unsafe upstream token forwarding.
- **Audience validation** — checks that tokens are intended for the receiving service.
- **Dynamic client registration** — flags unsafe or overly permissive registration flows.
- **PKCE handling** — checks that public-client authorization flows enforce the expected protection.

</details>

## More work

| Project | What it explores | Current state |
| --- | --- | --- |
| **[BioVoid](https://github.com/SetraTheXX/BioVoid)** | A local computational research prototype combining deterministic full-heavy-atom structure preparation, geometry-based pocket-candidate detection, a quality-gated experimental NMA layer, and interactive Mol\* inspection. | `v0.1.0 public source baseline` |
| **[Nihongo Learn](https://github.com/SetraTheXX/nihongo-learn)** | Japanese learning for Turkish-speaking beginners: kana, SM-2 reviews, 31 lessons, mini stories, and N5-style practice. | `usable local MVP` |

> **Scientific boundary:** BioVoid is a research prototype. It is not a
> clinical, diagnostic, validated binding-prediction, or drug-development
> system.

## Toolbox

**Languages:** TypeScript, JavaScript, Python, Rust, C#<br />
**Backend & web:** Node.js, Next.js/React, FastAPI, SQLite<br />
**Tooling:** Git, GitHub Actions, Docker, npm<br />
**Currently exploring:** Godot/C#, Three.js, Tauri, game systems, and lower-level software architecture

## About me

I am a Computer Programming student at Ondokuz Mayıs University in Samsun,
Türkiye. Most of my projects begin as something I want to understand or use,
then move beyond the demo stage through tests, documentation, CI, explicit
limitations, and reproducible verification.

AI-assisted tools are part of my planning and implementation workflow, but they
do not get the final say. Runtime behavior, automated checks, manual review, and
honest evidence remain the release gates.

<div align="center">

[LinkedIn](https://linkedin.com/in/tuncayolmez) ·
[npm](https://www.npmjs.com/~setrathex) ·
[Email](mailto:tuncay123454@gmail.com)

</div>
