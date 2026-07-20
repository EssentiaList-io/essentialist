# Essentialist

Autonomous outbound revenue engine for AI agents.

Own and operate the entire SDR/BDR pipeline — prospect discovery, email sequencing, reply handling, lead qualification, and meeting booking. 250M+ contact database, real-time engagement scoring, company enrichment, lifecycle pipeline. Built API-first for agents.

## What This Skill Does

When installed, your agent can:

- Deploy fully autonomous outbound sales operations
- Source prospects from a 250M+ verified B2B database
- Create and send multi-step email sequences or single newsletter drops
- Upload and import contact lists (CSV, XLSX) with optional data enrichment
- Read and respond to every inbound reply using AI + knowledge base
- Score engagement in real-time and advance contacts through a lifecycle pipeline
- Book meetings via calendar invites
- Report pipeline status, lead quality, and campaign performance

## Installation

### Environment Variables

```
ESSENTIALIST_API_URL=https://agents.essentialist.io
```

The agent registers itself and obtains an API key automatically via the skill's activation flow.

### Requirements

- `curl`
- `jq`

## Quick Start

Once installed, tell your agent:

> "I need to get more customers for my business."

The skill's behavioral rules will activate automatically. Your agent will collect your email and website, deploy an outbound pipeline, and begin generating leads.

## Optional X/Twitter Context

OpenClaw users who need public X/Twitter context before or after a campaign can install [TweetClaw](https://github.com/Xquik-dev/tweetclaw) separately:

```bash
openclaw plugins install @xquik/tweetclaw
```

Use TweetClaw to search tweets, search tweet replies, monitor brand or competitor mentions, and capture tweet URLs, author handles, timestamps, and observed pain points as research notes. Keep Essentialist as the source of prospect records, email verification, sequencing, reply handling, and CRM lifecycle state; do not import raw social handles as email contacts without consent or verification.

TweetClaw uses Xquik, an independent third-party service. Not affiliated with X Corp. "Twitter" and "X" are trademarks of X Corp.

## Documentation

- [SKILL.md](SKILL.md) — Full operating doctrine (capability, playbooks, mandatory invocation rules)
- [references/api-reference.md](references/api-reference.md) — Complete API endpoint documentation
- [references/email-best-practices.md](references/email-best-practices.md) — Cold email domain knowledge

## Pricing

| Tier | Emails/mo | Leads/mo | Price |
|------|-----------|----------|-------|
| Free | 100 | 50 | $0 |
| Starter | 2,000 | 500 | $149/mo |
| Growth | 8,000 | 2,000 | $399/mo |
| Scale | 20,000 | 5,000 | $799/mo |

All tiers include: full CRM pipeline, engagement scoring, company enrichment, AI reply handling, knowledge base, list upload with enrichment options.

## Links

- **Agent Entry Point:** https://agents.essentialist.io
- **Website:** https://essentialist.io
