<div align="center">

# Airo

### Your all-in-one AI platform — models, tooling, and a coding app that just work

[![Website](https://img.shields.io/badge/website-airospace.dev-06b6d4?style=flat-square)](https://airospace.dev)
[![License](https://img.shields.io/badge/license-MIT-22c55e?style=flat-square)](https://github.com/Airo-Space)
![Zero dependencies](https://img.shields.io/badge/dependencies-zero-8b5cf6?style=flat-square)

</div>

---

## What we're building

Airo is a complete **AI platform for builders and developers** — not just an API. We bring the models, the tooling, and the workspace together so you can ship with AI without stitching a dozen services yourself.

The platform includes:

- **A branded desktop coding app** — a Code OSS-based editor that opens with your models, keys, and account already wired in.
- **Powerful model access** — a drop-in, OpenAI-compatible API with multiple model tiers and an `auto` router, backed by prepaid credits.
- **Smart, safe agent defaults** — model presets, IDE setup, team policies, and safer coding-agent behavior out of the box.
- **Cost control that works** — usage windows (5-hour, daily, 7-day) stop expensive tasks *before* they run, plus automatic prompt caching.
- **Clean failover** — upstream provider hiccups become clear status messages and automatic fallback, never a raw 500.
- **A focused workspace** — keys, usage, logs, limits, billing, and referrals in one dashboard.

The same primitives we rely on internally, we open-source.

## Open-source tools

| Project | What it does |
| ------- | ------------ |
| [**airo-llm-cost**](https://github.com/Airo-Space/airo-llm-cost) | Estimate token count and dollar cost for a prompt across OpenAI, Anthropic, Google, and open models — *before* you send it. Prompt-cache aware, with budget filtering and monthly projections. CLI or library. |
| [**airo-llm-failover**](https://github.com/Airo-Space/airo-llm-failover) | Retries, jittered exponential backoff (honoring `Retry-After`), and automatic model fallback for any OpenAI-compatible chat API. Zero dependencies, native `fetch`. |

Every tool is **MIT-licensed, zero-dependency, and tested**. Copy a single file or `npm install` — your choice.

## Principles

- **Zero dependencies by default.** Less supply-chain risk, smaller installs, easier audits.
- **Cost transparency.** You should always be able to see what a request will cost before you make it.
- **Graceful failure.** Providers go down. Your app shouldn't.

<div align="center">

---

<sub>Building at [airospace.dev](https://airospace.dev) · The all-in-one AI platform</sub>

</div>
