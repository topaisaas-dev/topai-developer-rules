# TopAI Deterministic Engineering Rules for Cursor

Official Open Plugin providing deterministic coding standards, defensive architecture invariants, and sub-30ms edge utilities for **Cursor, Claude Code, Windsurf, and Antigravity**.

## Quick Try in 5 Seconds (Zero Signup)

```bash
# Deterministic Arithmetic & Checksum Guardrail
curl -s -X POST https://topaigateway.com/v1/math/check \
  -H "Content-Type: application/json" \
  -d '{"expr":"2+2*3"}'

# TokenSlimmer AST Compressor
curl -s -X POST https://topaigateway.com/v1/compress \
  -H "Content-Type: application/json" \
  -d '{"text":"Compress verbose agent outputs deterministically."}'

# Broken JSON Auto-Healer
curl -s -X POST https://topaigateway.com/v1/api/12-json-surgeon \
  -H "Content-Type: application/json" \
  -d '{"broken_json":"{\"ok\": true,}"}'
```

- **Starter Rules Sample**: [topai-cursor-rules.txt](https://topaigateway.com/download/samples/topai-cursor-rules.txt?utm_source=github&utm_campaign=topai-developer-rules)
- **Starter n8n Workflow**: [topai-n8n-starter.json](https://topaigateway.com/samples/topai-n8n-starter.json?utm_source=github&utm_campaign=topai-developer-rules)

## Overview
- **Deterministic Code**: Predictable, pure functions, bounded execution, and fail-fast assertions.
- **Strict Typing**: Full strict-mode TypeScript, Pydantic/typing in Python, and runtime schema validation.
- **FinOps & Context Efficiency**: Concise AST patterns, zero code bloat, and minimal context overhead.
- **Security & Data Sovereignty**: SSRF protection, strict secret isolation, and RFC-7807 problem details.

## Installation
In Cursor IDE / Claude Code:
- Open Settings -> Rules / Plugins and install `topai-developer-rules` from [cursor.directory](https://cursor.directory) or clone this repository.
- Connect the official MCP server via `npx -y @topaisaas/mcp-server`.

---

## Toolkits & Plans (100% USD · Zero Subscription Lock-In)

All toolkits include our **14-Day No-Questions-Asked Money-Back Guarantee** and instant key/download delivery:

| Toolkit / Plan | Price | What You Get | Direct USD Checkout |
|:---|:---|:---|:---|
| **Pack 1: DevEx & FinOps** | **$0** (7-Day Free Trial, then $14/mo) | 101 Edge APIs · 10,000 req/mo · Rollover quota | [Start $0 Free Trial](https://topaigateway.com/checkout?pack=pack_1_devex&direct=true&utm_source=github&utm_medium=readme&utm_campaign=topai-developer-rules) |
| **n8n & Make Super-Pack** | **$19** one-time (Lifetime) | 50 turnkey automation workflows + full JSON pack | [Get $19 Super-Pack](https://topaigateway.com/checkout?pack=bundle_n8n_make&direct=true&utm_source=github&utm_medium=readme&utm_campaign=topai-developer-rules) |
| **Runaway Token Breaker** | **$29** one-time (Lifetime) | AST pruning optimizer + sub-1ms runaway cost guardrails | [Get $29 Token Breaker](https://topaigateway.com/checkout?pack=runaway_token_breaker&direct=true&utm_source=github&utm_medium=readme&utm_campaign=topai-developer-rules) |
| **Cursor & Claude Harness Kit** | **$49** one-time (Lifetime) | 169 agent harness tools + multi-stack `.cursorrules` & MCP | [Get $49 Harness Kit](https://topaigateway.com/checkout?pack=bundle_cursor_harness&direct=true&utm_source=github&utm_medium=readme&utm_campaign=topai-developer-rules) |

- **Free Interactive Sample Hubs**: [Download Starter n8n Workflow JSON](https://topaigateway.com/samples/topai-n8n-starter.json?utm_source=github&utm_campaign=topai-developer-rules) · [Download Starter `.cursorrules` Pack](https://topaigateway.com/download/samples/topai-cursor-rules.txt?utm_source=github&utm_campaign=topai-developer-rules)
- **Native MCP Server (npm)**: `npx -y @topaisaas/mcp-server`

---

## License
MIT License. Created by [TopAI Gateway](https://topaigateway.com).
