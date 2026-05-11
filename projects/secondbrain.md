---
title: "Engram (secondbrain)"
status: "building"
tags: [ai, rag, obsidian, local-first, privacy, llm]
collaborators: []
looking-for: "beta testers, contributors for voice/research agent"
started: "2026-04"
links:
  - https://github.com/Ritinder-Singh/secondbrain
---

## What it is
Privacy-first personal AI knowledge assistant that runs entirely locally via Ollama. Ingest anything (YouTube videos, GitHub repos, Obsidian notes) and query it through a local LLM with RAG. No data leaves your machine.

## Stack
Ollama (llama3.1:8b) · pgvector (PostgreSQL) · nomic-embed-text · Obsidian PARA vault · CLI + voice interface · Groq (optional fallback)

## Status
Phase 1 complete — core RAG (ingest, chunk, embed, query). Phase 2 in progress — GitHub/Obsidian connectors + voice. Phase 3 planned: research agent, SearXNG, ntfy notifications. Phase 4: hybrid search, reranking, web UI.

## Looking for
Beta testers who want a local-only second brain. Contributors interested in the voice assistant or research agent phases.

## Notes
This project is also the backbone for the Vault mind map — the LLM will write markdown files directly into the Obsidian vault, auto-updating the public graph on push.

## Related
[[canary]] · [[launchpad]]
