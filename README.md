# twitterbot

An AI agent that discovers high-signal conversations on X matching your expertise and interests. It learns from every interaction, getting smarter over time — so you spend minutes approving, not hours searching.

## What It Does

1. **Discovers** — AI-powered search finds conversations where your voice matters
2. **Delivers** — curated digests arrive in your Slack DMs
3. **Learns** — every Like, Dislike, and Skip sharpens future results
4. **Compounds** — the more you use it, the better it gets

## How It Works

### Onboarding
When you first connect, the bot interviews you in Slack — learning your skills, goals, and target domains through a natural conversation. No forms to fill out.

### Discovery
The agent generates search queries tailored to your profile, fetches posts from X, scores them for relevance, and delivers a curated digest to your Slack DMs. Each post comes with Like, Dislike, and Skip buttons.

### Learning Loop
Every decision you make feeds back into the system. The agent learns what topics you care about, which voices you trust, and what kind of content resonates — then uses all of that to improve future runs. It tracks preferences across multiple dimensions simultaneously, so run 50 is measurably better than run 1.

### Dashboard
A web dashboard shows your connection status, run history, learning analytics, and budget usage.

## Features

- **Smart Discovery** — semantic search and LLM ranking matched to your profile
- **Adaptive Learning** — multi-dimensional preference learning with zero configuration
- **Slack-Native** — one-tap decisions in your existing workspace
- **Budget Controls** — per-user daily and monthly caps with full cost transparency
- **Data Isolation** — your data is scoped to your account by design
- **Analytics Dashboard** — track how your preferences evolve over time

## Tech Stack

- **Backend:** Python, FastAPI, PostgreSQL
- **AI:** Claude (ranking & evaluation), OpenAI (embeddings), LangGraph (pipeline orchestration)
- **Bot:** Slack Bolt (Socket Mode)
- **Frontend:** Tailwind CSS, Vite
- **Auth:** Google OAuth, X OAuth, Slack OIDC
- **Infra:** Railway

## Status

Currently in private beta. [Get early access →](https://twitterbot.app)

## Roadmap

- [x] Core discovery pipeline
- [x] Multi-signal learning loop
- [x] Slack bot with DM delivery
- [x] Web dashboard with analytics
- [x] Multi-user support with tenant isolation
- [x] Budget controls and cost tracking
- [ ] Scheduled automatic discovery runs
- [ ] Reply drafting with voice matching
- [ ] Multi-platform discovery (LinkedIn, Bluesky)
- [ ] Public API

## Changelog

### v2.0 (current)
- Multi-user architecture with full tenant isolation
- Web dashboard with analytics and connection management
- Preference learning loop (categories, authors, semantic similarity, distillation)
- Budget controls with per-user caps
- Waitlist and admin approval flow

### v1.0
- Single-user discovery pipeline
- Slack bot with onboarding interview
- LLM-powered search and ranking
- Basic preference tracking

## License

[PolyForm Noncommercial License 1.0.0](LICENSE) — free for personal and research use; commercial use prohibited.

---

*Built by [@tanishnahata](https://github.com/tnahata)*
