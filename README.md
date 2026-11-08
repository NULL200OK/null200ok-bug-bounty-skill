# NULL200OK — The All-in-One AI Bug Bounty Skill

> **One trigger word. One file. The complete offensive-security doctrine for your AI agent.**
> Write `NULL200OK` in any session and your AI instantly becomes a disciplined bug-bounty hunter — no links, no re-reading, no wasted context.
>
> 🆕 **v1.1 (Nov 2026):** new **Field Intelligence** section — ~150 writeup/PoC distillations from 2024–2026 research across 16 vulnerability classes, including a **Rare & Exotic Arsenal** (request smuggling, cache deception, prototype pollution, XS-leaks, cookie-prefix bypasses, parser differentials, supply chain, and more).

<p align="center">
  <img src="https://img.shields.io/badge/trigger-NULL200OK-critical?style=for-the-badge" alt="Trigger"/>
  <img src="https://img.shields.io/badge/format-SKILL.md-blueviolet?style=for-the-badge" alt="Format"/>
  <img src="https://img.shields.io/badge/skills-6%20repos%20distilled-success?style=for-the-badge" alt="Sources"/>
  <img src="https://img.shields.io/badge/license-MIT-green?style=for-the-badge" alt="License"/>
</p>

---

## 🧠 What is this?

**NULL200OK** is a single, self-contained [`SKILL.md`](SKILL.md) (~105 KB, agent-ready format) that condenses the battle-tested methodology of **6 open-source offensive-security skill repositories** — 1,300+ skill files distilled into one dense doctrine your AI agent can load in seconds.

Instead of feeding your agent 6 repos every session, you load **one file** and activate it with one word:

```
NULL200OK
```

The agent replies: **`NULL200OK :: SKILL LOADED`** — and operates as an offensive-security expert with the full doctrine: recon pipelines, 12+ vulnerability-class playbooks, exploit chaining, Web3/Immunefi methodology, WAF bypass, severity triage, and platform-calibrated reporting (HackerOne / Bugcrowd / Immunefi / YesWeHack).

## ⚡ Quick Start

### Option A — Install as an agent skill (recommended)

```bash
npx skills add NULL200OK/null200ok-bug-bounty-skill
```

Then in any session with your agent (Claude Code, Cursor, Codex, or any SKILL.md-compatible agent):

```
NULL200OK
```

### Option B — Manual load

1. Download [`SKILL.md`](SKILL.md).
2. Paste it into your agent's context (or drop it into `skills/null200ok-bughunter/SKILL.md` in your project).
3. Type `NULL200OK`.

### Built-in trigger commands

| Command | Effect |
|---|---|
| `NULL200OK` | Activate the full doctrine |
| `STATE` | Show current hunt state (target, scope, findings, next chain) |
| `RECON MODE` / `WEB MODE` / `API MODE` / `LLM MODE` / `MOBILE MODE` | Switch hunting mode |
| `PAYLOAD <class>` / `BYPASS <thing>` / `CHAIN` | Payload, bypass, and chaining doctrine |
| `REPORT MODE` / `TRIAGE THIS` | Platform-calibrated reporting & self-triage |
| `RESET` | Clear hunt state |

## 📦 What's Inside

| Section | Coverage |
|---|---|
| **Activation Protocol** | Trigger word, STATE BLOCK memory, mode commands |
| **Core Identity & Rules** | Mode-confirmation gate, "The Only Question", 17 critical rules, session discipline, evidence discipline (marker discipline, body-diff rule, multi-tool reproduction bar) |
| **Recon** | Passive/active pipelines, subdomain-enum decision trees, tool routing, framework quick-wins, scope triage & false-positive controls |
| **Vuln-Class Playbooks** | IDOR, SSRF, XSS, SQLi, JWT/auth bypass, race conditions, business logic, API/GraphQL, Kubernetes/cloud, LLM & AI agents, mobile, CI/CD |
| **Chains & Impact** | A→B cluster hunting, 12 canonical chains, impact amplification per class |
| **Web3 / Immunefi** | 10 smart-contract bug classes, 10 attacker questions, grep arsenal, Foundry PoC methodology, severity matrix, report formula |
| **Payloads & WAF** | Context-grouped payloads, polyglots, WAF bypass categories (encoding, fragmentation, headers, origin discovery) |
| **Mindset & Strategy** | Target selection, duplicate avoidance, high-value prioritization, time management |
| **Platform Intelligence** | HackerOne, Bugcrowd (VRT), Immunefi, YesWeHack (ywh-kit), Intigriti — calibrated report styles |
| **Reporting & Triage** | 7-Question Gate, Never-Submit list, CVSS reference tables, evidence hygiene |
| **Agent Doctrine (Strix)** | Counterevidence closure states, severity calibration, fix verification, family sweeps, scan modes |
| **Red Team & Infra** | Entra ID, Okta, vCenter, enterprise VPN CVE matrix, cloud IAM escalation, supply-chain recon |
| **Scope & Ethics** | Authorization-only discipline baked into the doctrine |
| **Field Intelligence (v1.1)** | ~150 writeup/PoC distillations from 2024–2026 (244 primary-source links): IDOR/BAC, XSS/sanitizer bypasses, SSRF, SQLi/NoSQLi, RCE/deserialization, file upload, auth/OTP/OAuth, race conditions, business logic, cache/CORS/headers, GraphQL/REST/WebSocket, **Rare & Exotic Arsenal** (smuggling & desync, cache deception, prototype pollution, XS-leaks, CSP, cookie attacks, parser differentials, supply chain, DNS rebinding, file-format attacks), LLM/AI agents, Web3/Immunefi, mobile, modern API |

## 🤝 Compatibility

Works with any agent that reads Markdown instructions:

- Claude Code / Claude Desktop (as a project skill)
- Cursor, Codex CLI, OpenCode, Windsurf
- Any LLM chat UI (paste the file + type `NULL200OK`)
- CI pipelines (headless agents)

## 🙏 Sources & Credits

This skill is a **condensed distillation** for personal agent use. All methodology credit belongs to these excellent open-source projects — star them all:

| Source | Focus |
|---|---|
| [elementalsouls/Claude-BugHunter](https://github.com/elementalsouls/Claude-BugHunter) | 83 hunt-* skills from 681 disclosed HackerOne reports + deterministic engine |
| [0xN0RMXL/BugBountySkills](https://github.com/0xN0RMXL/BugBountySkills) | 615-file knowledge vault: recon, payloads, WAF, mindset, platforms |
| [awarexone/Agentic-Bug-Hunter](https://github.com/awarexone/Agentic-Bug-Hunter) | Executable hunting loop: Recon → Learn → Hunt → Validate → Report |
| [murrtada/bug-bounty-agent-skills](https://github.com/murrtada/bug-bounty-agent-skills) | 93 agent-agnostic skills + YesWeHack (ywh) kit |
| [awarexone/web3-bug-bounty-hunting-ai-skills](https://github.com/awarexone/web3-bug-bounty-hunting-ai-skills) | Web3/Immunefi doctrine from 2,749 disclosed reports |
| [usestrix/strix](https://github.com/usestrix/strix) | Autonomous AI pentesting agent — counterevidence & severity doctrine |

All six are MIT or Apache-2.0 licensed; this condensation is attributed accordingly and released under MIT.

## ⚠️ Disclaimer

**Authorized testing only.** This skill encodes scope discipline as a hard rule: hunt only within written scope, never attack systems without explicit permission, never conduct DoS/brute-force/social-engineering unless the program explicitly allows it. You are responsible for complying with the laws of your jurisdiction and the rules of every platform. Provided "as is" with no warranty or liability for misuse.

## 📄 License

MIT — see [LICENSE](LICENSE).
