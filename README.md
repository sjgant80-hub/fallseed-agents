# FallSeed · Agents

> **The level-3 seed.** A sovereign single-HTML PWA for running an organisation of agents around 6 role presets: Sales · Research · Marketing · Support · Ops · Personal.

**Live:** https://sjgant80-hub.github.io/fallseed-agents/

## What this is

`fallseed-agents` is one HTML file. Spawn an agent from a role; run any of its 6 tuned tasks through the LLM cascade; schedule recurring runs; full transcript log + audit chain. Output stays on your device.

## Roles shipped

- **◆ Sales** — lead qualification, outreach, follow-up, demo prep, proposal drafting
- **◈ Research** — paper synthesis, literature mapping, competitor analysis, trend monitoring
- **◉ Marketing** — content drafts, campaign briefs, social copy, SEO topic clusters
- **◍ Support** — ticket triage, response drafts, KB lookup, escalation routing
- **◐ Ops** — standup summaries, blocker tracking, retrospective notes, decision logs
- **◌ Personal** — daily brief, inbox triage, weekly review, calendar audit

Add custom roles via the Build tab (cascade-driven).

## What kind of seed is this?

A **level-3** seed in the FallSeed family. L0 packages tools; L1 packages frameworks; L2 packages personas; L3 packages **actors** — agent roles with system prompts, task libraries, schedules, and transcript stores. Built on the Fork Seed primitive — see [the spec](https://www.ai-nativesolutions.com/spec.html).

## Tabs

Welcome · Roles · My agents · Tasks · Runs · Schedule · Build · LLM Providers · Fork Seed · Inspect · Settings · Install

## Architecture invariants

- One HTML file · IDB primary · BroadcastChannel mesh (`fall-agents` + `fall-signal`)
- P3 audit chain on every state mutation (agents, runs, schedules)
- 8-provider LLM cascade with streaming
- **In-tab scheduler** — recurring runs fire automatically while tab is open
- Fork Seed packager (jsLiteral serializer)
- Peer-tracking + cross-seed request/response over fall-signal

## Cosmology

Prime **1223**, spine-clean mod 127 = 80 = 2⁴·5. Seed level **3**. Mesh channel **`fall-agents`**. Root seed (parent: null). Seal **◊·κ=1**.

## Disclaimer

**Operational scaffolding, not autonomous decision-making.** Agent outputs are *drafts you review* — never blind-execute. The Personal agent suggests an inbox triage; you decide. The Sales agent drafts an outreach; you send. The Support agent triages a ticket; you escalate. Sovereignty = your judgement remains in the loop.

## Licence

MIT © Simon Gant.
