# Hi, I'm Phillip

```text
┌──────────────────────────────────────────────────────────────┐
│                                                              │
│   Phillip — building small tools that earn their keep       │
│                                                              │
│   🛠  CLI utilities    📊  Data pipelines                   │
│   🤖  Local LLM tools   🐍  Python (mostly)                 │
│   🔒  Windows security  🪟  PowerShell on the side           │
│                                                              │
└──────────────────────────────────────────────────────────────┘
```

Melbourne, Australia. I learn by building — small, focused tools that solve a real problem I have, then I open-source the ones that don't depend on private data.

## What I'm building

| | |
|---|---|
| 🛠 **CLI tools** | Small, focused, well-tested Python utilities |
| 📊 **Data engineering** | CSV/SQLite/JSON pipelines, schema validation, type inference |
| 🤖 **Local LLM tooling** | Log analyzers, rate-limit proxies, MCP helpers |
| 🪟 **Windows automation** | Security hardening, scheduled tasks, multi-terminal workspaces |
| 🇦🇺 **Australian public data** | AFL/NRL fixtures, results, ladders |

I keep my betting infrastructure private (that's my day job), but everything else is fair game.

## Featured projects

### 🤖 Local AI & dev tooling

- **[agentdeck](https://github.com/phillza/agentdeck)** — a minimal multi-terminal workspace in your browser. xterm.js + WebSocket + aiohttp, ~250 lines. Ships a Windows watchdog and a torture-test helper for the renderer.
- **[llm-log-summarizer](https://github.com/phillza/llm-log-summarizer)** — `logsum` CLI. Point it at a log file, get back a markdown report. Uses Ollama by default, so no API key required.
- **[fireworks-proxy](https://github.com/phillza/fireworks-proxy)** — local HTTP proxy that queues concurrent Kimi CLI requests behind RPS and TPM budgets, so you stop hitting Fireworks AI's adaptive 429s.

### 📊 Data & pipelines

- **[csv-vault](https://github.com/phillza/csv-vault)** — `csv-vault` CLI. CSV ↔ SQLite with type inference, schema validation, and deduplication. No pandas.
- **[ausport-fixtures](https://github.com/phillza/ausport-fixtures)** — `ausport` CLI. AFL/NRL fixtures, results, and ladders from the public Squiggle API.
- **[data-plan-tracker](https://github.com/phillza/data-plan-tracker)** — Streamlit + SQLite app for tracking SIMs, mobile plans, proxies, VPNs, and recurring software expenses. Desktop/email/Telegram renewal alerts.

### 🔒 Windows security

- **[windows-security-hardening](https://github.com/phillza/windows-security-hardening)** — 16 PowerShell scripts, 24-check no-admin validator, and three-tier drift detection (quick hash, JSON diff, deep validation). CIS Controls v8 + Microsoft Security Baselines.

## Stack

- **Languages:** Python (primary) · TypeScript · PowerShell · SQL
- **Local AI:** Ollama · Kimi CLI · Fireworks AI
- **Daily drivers:** Claude Code, Codex CLI

## Why I open-source

I learn by building, and the best feedback loop is a real user. If any of my repos help you, an issue or a star is a great way to say thanks.

## Reach me

- Issues on any of the repos above
- GitHub: [@phillza](https://github.com/phillza)

---

<sub>Last updated 2026-06-17.</sub>
