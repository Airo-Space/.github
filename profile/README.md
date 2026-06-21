<div align="center">

# Airo

### Affordable, OpenAI-compatible AI access — without the surprises

[![Website](https://img.shields.io/badge/website-airospace.dev-06b6d4?style=flat-square)](https://airospace.dev)
[![License](https://img.shields.io/badge/license-MIT-22c55e?style=flat-square)](https://github.com/Airo-Space)
![Zero dependencies](https://img.shields.io/badge/dependencies-zero-8b5cf6?style=flat-square)

</div>

---

## What we're building

Airo makes AI access **affordable, predictable, and safe to ship on**. Our platform exposes a drop-in **OpenAI-compatible API** backed by prepaid credits, so you get the models you need without runaway bills or vendor lock-in.

What sets it apart:

- **Usage windows before the call** — 5-hour, daily, and 7-day limits stop an expensive task *before* it runs, so one request can't drain your balance.
- **Prompt caching** — repeated context is billed at a steep discount, automatically.
- **Clean failover** — when an upstream provider hiccups, you see a clear status message and automatic fallback, not a raw 500.
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

<sub>Building at [airospace.dev](https://airospace.dev) · OpenAI-compatible AI access</sub>

</div>
