<div align="center">

# Tuncay Ölmez

### Developer Tooling · Application Security · Local-First Systems

I build tools that turn vague engineering risk into evidence you can inspect:
deterministic findings, bounded workflows, and read-only diagnostics.

<p>
  <a href="https://linkedin.com/in/tuncayolmez"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.17.0/icons/linkedin/linkedin-original.svg" height="26" alt="LinkedIn" title="LinkedIn" /></a>&nbsp;&nbsp;
  <a href="https://www.npmjs.com/~setrathex"><img src="https://cdn.simpleicons.org/npm/CB3837" height="26" alt="npm" title="npm" /></a>&nbsp;&nbsp;
  <a href="mailto:tuncay123454@gmail.com"><img src="https://cdn.simpleicons.org/gmail/EA4335" height="26" alt="Email" title="Email" /></a>
</p>

</div>

---

## About me

I am a Computer Programming student at Ondokuz Mayıs University in Samsun,
Türkiye. Most of my projects begin as something I want to understand or use,
then move beyond the demo stage through tests, documentation, CI, explicit
limitations, and reproducible verification.

AI-assisted tools are part of my planning and implementation workflow, but they
do not get the final say. Runtime behavior, automated checks, manual review, and
honest evidence remain the release gates.

---

## Featured projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>next-secure-check</h3>
      A deterministic, Next.js-focused security sanity check for pre-deploy review and CI. It surfaces common risk patterns with bounded, explainable evidence without executing the scanned repository or using an LLM at runtime.
      <br /><br />
      <strong>Current:</strong> <code>v0.5.0</code> on npm · <code>20 rules</code> · <code>513 tests</code><br />
      <strong>Ships with:</strong> compact <code>--summary</code> output · SARIF · <a href="https://github.com/SetraTheXX/next-secure-check/releases/tag/v1.1.0">Action <code>v1.1.0</code></a><br />
      <strong>Next:</strong> <code>v0.6</code> request-boundary coverage<br />
      <code>TypeScript</code> <code>AST-assisted</code> <code>bounded flow</code>
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
      <strong>Current:</strong> <code>v0.1.0</code> · GitHub Release + crates.io<br />
      <code>Rust 2024</code> <code>terminal + JSON</code> <code>read-only</code> <code>15 findings</code>
      <br /><br />
      <a href="https://github.com/SetraTheXX/Portal-Doctor"><strong>View repository →</strong></a>
    </td>
    <td width="50%" valign="top">
      <h3>Pagonic</h3>
      Inspects ZIP archives for path traversal, suspicious entries, extreme compression ratios, unsupported methods, and structural errors before extraction. Provides deterministic reports and policy gates as a Python library and CLI from a local checkout or GitHub release artifact.
      <br /><br />
      <strong>Current:</strong> <code>v0.5.0 alpha</code> · <a href="https://github.com/SetraTheXX/pagonic/releases/tag/v0.5.0">GitHub release</a> · wheel + sdist · no PyPI/TestPyPI package yet<br />
      <code>Python</code> <code>CLI</code> <code>safe extraction</code> <code>JSON + Markdown</code>
      <br /><br />
      <a href="https://github.com/SetraTheXX/pagonic"><strong>View repository →</strong></a>
    </td>
  </tr>
</table>

## Merged open-source contributions

| Project | Pull request | Focus |
| --- | --- | --- |
| Ship Safe | [#161](https://github.com/asamassekou10/ship-safe/pull/161) | MCP/OAuth security checks |
| OWASP Noir | [#2657](https://github.com/owasp-noir/noir/pull/2657) | Vercel specification analyzer functional coverage |
| cargo-deny | [#893](https://github.com/EmbarkStudios/cargo-deny/pull/893) | Sparse registry matching for literal IP hosts |

## More work

| Project | What it explores | Current state |
| --- | --- | --- |
| **[BioVoid](https://github.com/SetraTheXX/BioVoid)** | A local computational research prototype combining deterministic full-heavy-atom structure preparation, geometry-based pocket-candidate detection, a quality-gated experimental NMA layer, and interactive Mol\* inspection. | `v0.1.0 public source baseline` |
| **[Nihongo Learn](https://github.com/SetraTheXX/nihongo-learn)** | Japanese learning for Turkish-speaking beginners: kana, SM-2 reviews, 31 lessons, mini stories, and N5-style practice. | `usable local MVP` |

> **Scientific boundary:** BioVoid is a research prototype. It is not a
> clinical, diagnostic, validated binding-prediction, or drug-development
> system.

## Toolbox

**Core**

<p>
  <img src="https://skillicons.dev/icons?i=ts,py,rust&perline=3&theme=dark" alt="TypeScript, Python, and Rust" />
</p>

**Runtime & application stack**

<p>
  <img src="https://skillicons.dev/icons?i=nodejs,nextjs,react,fastapi,sqlite&perline=5&theme=dark" alt="Node.js, Next.js, React, FastAPI, and SQLite" />
</p>

**Engineering tooling**

<p>
  <img src="https://skillicons.dev/icons?i=githubactions,docker,npm&perline=3&theme=dark" alt="GitHub Actions, Docker, and npm" />
</p>
