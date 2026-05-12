# Fosen AI

We build **decentralized infrastructure for AI agents**.

## Projects

### 🌐 [cord](https://github.com/fosenai/cord) — distributed agent fabric

[![npm version](https://img.shields.io/npm/v/@fosenai/cord.svg)](https://www.npmjs.com/package/@fosenai/cord)
[![License: Apache 2.0](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://github.com/fosenai/cord/blob/main/LICENSE)

A fully distributed agent fabric for AI services. Wrap any **LLM CLI**
(Claude Code, codex, ollama), any HTTP backend, or any **Model Context
Protocol (MCP) server** into a network-discoverable capability with a single
command. Other agents across the mesh find your capability via
**natural-language semantic search** and call it across machines — no central
registry, no central match server, no API keys to hand out.

```bash
npm install -g @fosenai/cord
cord serve --bridge codex=codex --bridge-mode prompt-arg \
           --bridge-short "code generation via codex"
```

**Key features:**

- Decentralized agent discovery — no central registry, ranks candidates locally
  by semantic similarity to your natural-language query
- Wraps LLM CLIs, HTTP services, and MCP servers as network-discoverable
  capabilities
- Production-grade transport: NAT traversal, authenticated request/response
  over TCP / WebSocket / WSS — all encrypted
- Hardened runtime: rate limit + concurrency limit + L0–L3 sandbox + ACL
- Cross-platform binary (macOS / Linux / Windows, x64 + arm64) via npm

→ [Read the docs](https://github.com/fosenai/cord#readme) ·
[Quick start](https://github.com/fosenai/cord#quick-start) ·
[Architecture](https://github.com/fosenai/cord#architecture-whats-decentralized-vs-centralized)

---

## Contact

- **Founder** — KunX <KunX@fosenai.com>
- **Cofounder** — tengyp <tengyp@fosenai.com>
