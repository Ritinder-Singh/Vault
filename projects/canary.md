---
title: "Canary"
status: "building"
tags: [saas, go, ai, devtools, uptime-monitoring]
collaborators: []
looking-for: "frontend dev, early beta users"
started: "2026-05"
links:
  - https://github.com/Ritinder-Singh/Canary
---

## What it is
AI-native uptime monitor — does HTTP checks and incident detection like every other uptime tool, but adds Anthropic-powered root cause analysis, severity classification, and plain-English incident summaries. Built in Go.

## Stack
Go · PostgreSQL · Chi router · Anthropic API · Docker · Fly.io/Railway

## Status
MVP phase (Days 1–3): core polling engine, incident detection, AI summaries, Slack alerts, auth scaffolding, multi-tenancy. SaaS phase next: Stripe, multi-region checks, PagerDuty.

## Pricing model
Free (3 monitors) → Pro $9/mo (50 monitors) → Team $29/mo → Enterprise custom.

## Looking for
Frontend dev to own the dashboard UI. Early beta users willing to run it against their own services.

## Notes
Differentiation is the AI layer — no other uptime tool generates natural-language root cause hypotheses or recognises historical incident patterns automatically.

## Related
[[launchpad]] · [[secondbrain]]
