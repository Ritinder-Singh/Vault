---
title: "LaunchPad"
status: "building"
tags: [cli, go, devtools, cloudflare, deployment]
collaborators: []
looking-for: "feedback, early adopters"
started: "2026-05"
links:
  - https://github.com/Ritinder-Singh/LaunchPad
---

## What it is
Go CLI that reads a `showcase.config.json` and deploys a static project showcase page to your own subdomain on Cloudflare Pages in under 60 seconds. One command — `launchpad deploy` — and the project is live at `projectname.yourdomain.com`.

## Stack
Go · Astro (templates embedded via go:embed) · Cloudflare Pages API · Node.js (npx distribution)

## Commands
`launchpad init` · `launchpad preview` · `launchpad deploy` · `launchpad templates list`

## Templates
`minimal` (typography-focused) · `bold` (dark hero) · `developer` (terminal aesthetic) — or bring your own HTML.

## Status
Functional — the tool's own page was deployed using itself. Looking for early adopters and feedback on template variety and provider support (Vercel, Netlify planned).

## Looking for
Developers who want a dead-simple way to showcase side projects. Feedback on config UX and template designs.
