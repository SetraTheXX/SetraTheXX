<div align="center">

# Tuncay Ölmez

### Developer Tooling · Application Security · Local-First Systems

I build deterministic developer-security tools and local-first workflows that turn
vague engineering risk into evidence you can inspect.

**Open to open-source collaboration, developer-tooling discussions, and selected freelance work.**

<p>
  <a href="https://linkedin.com/in/tuncayolmez">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.17.0/icons/linkedin/linkedin-original.svg" height="28" alt="LinkedIn" title="LinkedIn" />
  </a>
  &nbsp;&nbsp;&nbsp;
  <a href="https://www.npmjs.com/~setrathex">
    <img src="https://cdn.simpleicons.org/npm/CB3837" height="30" alt="npm" title="npm" />
  </a>
</p>

</div>

---

## About me

I’m a Computer Programming student at Ondokuz Mayıs University in Samsun,
Türkiye. I turn practical engineering problems into small tools with clear
boundaries, reproducible output, and a path from local use to CI.

My work is mostly centered on developer tooling, application security,
local-first systems, and AI-assisted engineering workflows.

AI helps me move faster; tests, review, and reproducible runtime evidence decide
what ships.

---

## Featured projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>
        <a href="https://github.com/SetraTheXX/next-secure-check">next-secure-check</a>
      </h3>
      Deterministic security checks for Next.js projects. Scan before deploy or in CI and get clear terminal, JSON, Markdown, GitHub Summary, or SARIF evidence without executing the scanned repository or using an LLM at runtime.
      <br /><br />
      <strong>Release:</strong> <a href="https://github.com/SetraTheXX/next-secure-check/releases/tag/v0.6.0"><code>v0.6.0</code></a> on npm · <code>25 rules</code> · <code>600 tests</code><br />
      <strong>Try:</strong> <code>npx</code> one-off scans · <code>--summary</code> · SARIF · <a href="https://github.com/SetraTheXX/next-secure-check/releases/tag/v1.2.0">Action <code>v1.2.0</code></a> via <code>@v1</code><br />
      <strong>Proof:</strong> secure fixture <code>99/100</code> · vulnerable fixture <code>26 findings</code>
      <br /><br />
      <code>TypeScript</code> <code>AST-assisted</code> <code>bounded flow</code>
      <br /><br />
      <a href="https://github.com/SetraTheXX/next-secure-check"><strong>View repository →</strong></a>
    </td>
    <td width="50%" valign="top">
      <h3>
        <a href="https://github.com/SetraTheXX/Portal-Doctor">PortalDoctor</a>
      </h3>
      A read-only Linux diagnostic tool for XDG Desktop Portal, Wayland, D-Bus, systemd, PipeWire, and WirePlumber failures. It explains the routing path instead of asking users to guess.
      <br /><br />
      <strong>Release:</strong> <a href="https://github.com/SetraTheXX/Portal-Doctor/releases/tag/v0.2.1"><code>v0.2.1</code></a> · <a href="https://crates.io/crates/portaldoctor">crates.io</a> · Linux x86_64 binary<br />
      <strong>Stable behavior:</strong> the published release is read-only; active probes are still isolated to development work on <code>main</code><br />
      <strong>Demo:</strong> <a href="https://github.com/SetraTheXX/Portal-Doctor/blob/v0.2.1/docs/assets/portaldoctor-demo.gif">terminal flow</a> · JSON + Markdown
      <br /><br />
      <code>Rust 2024</code> <code>Linux diagnostics</code> <code>read-only</code>
      <br /><br />
      <a href="https://github.com/SetraTheXX/Portal-Doctor"><strong>View repository →</strong></a>
    </td>
  </tr>

  <tr>
    <td width="50%" valign="top">
      <h3>
        <a href="https://github.com/SetraTheXX/pagonic">Pagonic</a>
      </h3>
      Inspect ZIP archives before extraction. Pagonic detects path traversal, suspicious entries, extreme compression ratios, unsupported methods, and structural errors before files are written.
      <br /><br />
      <strong>Release:</strong> <a href="https://github.com/SetraTheXX/pagonic/releases/tag/v0.5.1"><code>v0.5.1</code></a> · <a href="https://pypi.org/project/pagonic/">PyPI</a> · wheel + sdist<br />
      <strong>Flow:</strong> <code>inspect</code> → <code>verify</code> → <code>safe-extract</code><br />
      <strong>Output:</strong> deterministic reports · policy gates · JSON + Markdown
      <br /><br />
      <code>Python</code> <code>CLI</code> <code>safe extraction</code>
      <br /><br />
      <a href="https://github.com/SetraTheXX/pagonic"><strong>View repository →</strong></a>
    </td>
    <td width="50%" valign="top">
      <h3>
        <a href="https://github.com/SetraTheXX/Codex-Engineering-Workflow-Pack">Codex Engineering Workflow Pack</a>
      </h3>
      A local-first control plane around Codex: approve scope, execute in an isolated worktree, verify outside the model loop, require independent review, and leave a portable receipt.
      <br /><br />
      <strong>Release:</strong> <a href="https://github.com/SetraTheXX/Codex-Engineering-Workflow-Pack/releases/tag/v0.14.0"><code>v0.14.0</code></a> · npm stable · GitHub stable release<br />
      <strong>Flow:</strong> <code>plan</code> → <code>approve</code> → <code>execute</code> → <code>verify</code> → <code>review</code> → <code>receipt</code>
      <br /><br />
      <code>Node.js 22+</code> <code>Codex plugin</code> <code>local MCP</code>
      <br /><br />
      <a href="https://github.com/SetraTheXX/Codex-Engineering-Workflow-Pack"><strong>View repository →</strong></a>
    </td>
  </tr>
</table>

---

## Merged open-source contributions

I prefer narrow, reviewable fixes with regression coverage. These are merged upstream.

| Project                | Pull request                                                     | Focus                                                          |
| ---------------------- | ---------------------------------------------------------------- | -------------------------------------------------------------- |
| **conftest**           | [#1413](https://github.com/open-policy-agent/conftest/pull/1413) | Apply `--ignore` to explicitly provided files                  |
| **gosec**              | [#1733](https://github.com/securego/gosec/pull/1733)             | Deterministic, bounded taint caller traversal                  |
| **codex-with-chatgpt** | [#26](https://github.com/XiaoDuoYa/codex-with-chatgpt/pull/26)   | OAuth pairing-page HTML hardening and browser security headers |
| **cargo-deny**         | [#893](https://github.com/EmbarkStudios/cargo-deny/pull/893)     | Sparse registry matching for literal IP hosts                  |
| **OWASP Noir**         | [#2657](https://github.com/owasp-noir/noir/pull/2657)            | Vercel specification analyzer functional coverage              |

<details>
<summary><strong>View more contributions</strong></summary>

<br />

| Project       | Pull request                                                | Focus                     |
| ------------- | ----------------------------------------------------------- | ------------------------- |
| **Ship Safe** | [#161](https://github.com/asamassekou10/ship-safe/pull/161) | MCP/OAuth security checks |

</details>

---

## Private work

Some of my larger ongoing systems remain private while their implementation,
research, and review cycles continue.

| Project       | Focus                                                                                                                                                                 |
| ------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **RedNode**   | Local-first security workstation for authorized engagements, built around explicit scope, typed execution, evidence, and verification boundaries.                     |
| **HuntForge** | Bug-bounty-oriented web/API security workspace covering scope, approvals, bounded validation, evidence, triage, retesting, and reporting.                             |
| **BorsaLab**  | Local-first BIST research workstation for explainable screening, reproducible backtesting, strategy research, portfolio discipline, events, and fundamental analysis. |
| **BioVoid**   | Computational research prototype for reproducible protein-structure analysis and geometry-based pocket-candidate generation.                                          |

<details>
<summary><strong>BioVoid scientific boundary</strong></summary>

<br />

BioVoid produces unvalidated geometry-based pocket candidates and diagnostics.

Its outputs are not clinical or diagnostic results, validated binding predictions,
drug-development results, or drug-discovery claims. Source, datasets, and
intermediate research artifacts remain private while research and independent
review continue.

</details>

---

## More work

### [Nihongo Learn](https://github.com/SetraTheXX/nihongo-learn)

Japanese learning for Turkish-speaking beginners: kana practice, SM-2 reviews,
31 lessons, mini stories, and N5-style practice.

`TypeScript` `language learning` `usable local MVP`

---

## Toolbox

### Core

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=ts,py,rust&theme=dark&perline=3" />
  <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=ts,py,rust&theme=light&perline=3" />
  <img src="https://skillicons.dev/icons?i=ts,py,rust&theme=dark&perline=3" alt="TypeScript, Python, and Rust" />
</picture>

### Runtime & application stack

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=nodejs,nextjs,react,fastapi,sqlite&theme=dark&perline=5" />
  <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=nodejs,nextjs,react,fastapi,sqlite&theme=light&perline=5" />
  <img src="https://skillicons.dev/icons?i=nodejs,nextjs,react,fastapi,sqlite&theme=dark&perline=5" alt="Node.js, Next.js, React, FastAPI, and SQLite" />
</picture>

### Engineering tooling

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=git,githubactions,docker,npm,linux&theme=dark&perline=5" />
  <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=git,githubactions,docker,npm,linux&theme=light&perline=5" />
  <img src="https://skillicons.dev/icons?i=git,githubactions,docker,npm,linux&theme=dark&perline=5" alt="Git, GitHub Actions, Docker, npm, and Linux" />
</picture>

---

<div align="center">

Open to collaboration or freelance work around developer tooling, application security,
local-first systems, and engineering automation.

<a href="https://linkedin.com/in/tuncayolmez"><strong>Reach me on LinkedIn →</strong></a>

</div>
