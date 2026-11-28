# Gregale

**The backend platform for startup teams without an ops person.**

Deploy web APIs, background workers, schedulers, managed Postgres, remote MCP
servers, private sandboxes and AI agent workflows in one CLI command (`gregale
deploy` or `git push`) on isolated Firecracker MicroVMs. Zero YAML required,
scale-to-zero included, with hard monthly spending caps so unexpected traffic
or runaway bot loops cannot surprise your bill.

## Repositories

### Agent, IDE & CI/CD Integrations
| Repository | What it is |
|---|---|
| [gregale-cursor-plugin](https://github.com/gregale-dev/gregale-cursor-plugin) | Deploy, diagnose and roll back apps from Cursor through Gregale's hosted MCP server |
| [gregale-antigravity-plugin](https://github.com/gregale-dev/gregale-antigravity-plugin) | Deploy, diagnose and roll back apps from Antigravity through Gregale's hosted MCP server |
| [gregale-claude-code-plugin](https://github.com/gregale-dev/gregale-claude-code-plugin) | Claude Code plugin & marketplace for deploying and diagnosing Gregale apps via MCP |
| [setup-gregale](https://github.com/gregale-dev/setup-gregale) | GitHub Action (`gregale-dev/setup-gregale@v1`) to install & configure the Gregale CLI in CI/CD workflows |

### Remote MCP Server Starters
| Repository | What it is |
|---|---|
| [mcp-server-node](https://github.com/gregale-dev/mcp-server-node) | Stateless Streamable HTTP MCP server in Node.js that scales to zero (external OAuth, scoped tools, `AGENTS.md`) |
| [mcp-server-python](https://github.com/gregale-dev/mcp-server-python) | Stateless Streamable HTTP MCP server in Python with `PyJWT` external OAuth & `AGENTS.md` |
| [mcp-server-go](https://github.com/gregale-dev/mcp-server-go) | Stateless Streamable HTTP MCP server in Go (`modelcontextprotocol/go-sdk`) with external OAuth & `AGENTS.md` |
| [mcp-server-typescript-oauth](https://github.com/gregale-dev/mcp-server-typescript-oauth) | Remote MCP server in TypeScript (official SDK) that checks OAuth 2.1 access tokens: RFC 9728 metadata, audience and scope checks, tests |

### Platform Feature & Application Starters
| Repository | What it is |
|---|---|
| [scale-to-zero-websockets](https://github.com/gregale-dev/scale-to-zero-websockets) | WebSocket & SSE chat/notifications starter on Managed Realtime — idle clients stay connected at `$0` compute |
| [durable-stripe-webhooks](https://github.com/gregale-dev/durable-stripe-webhooks) | Stripe & generic HMAC-SHA256 webhook receiver with deduplication, retries & DLQ replay while parked |
| [postgres-migration-rollback-demo](https://github.com/gregale-dev/postgres-migration-rollback-demo) | FastAPI + managed Postgres starter showing release migrations & `gregale rollback --restore-databases` |
| [edge-waf-rate-limit-starter](https://github.com/gregale-dev/edge-waf-rate-limit-starter) | Pre-wake OWASP WAF, PoW bot challenge, composite rate limits, hard spend caps & trace fixtures |
| [nextjs-postgres-starter](https://github.com/gregale-dev/nextjs-postgres-starter) | Next.js 16 (App Router, standalone output) + managed Postgres 17 starter with release migrations |
| [bun-hono-postgres-starter](https://github.com/gregale-dev/bun-hono-postgres-starter) | Bun + Hono + TypeScript + managed Postgres 17 API starter |
| [node-api-worker](https://github.com/gregale-dev/node-api-worker) | Docker Compose app to production: Node.js API, private worker & Postgres job queue from one `compose.yaml` |
| [rust-axum-postgres](https://github.com/gregale-dev/rust-axum-postgres) | Rust Axum + sqlx API on managed Postgres 17: one binary serves and migrates, 57 MB image |
| [fastapi-postgres-jobs](https://github.com/gregale-dev/fastapi-postgres-jobs) | FastAPI HTTP service + async background jobs + managed Postgres starter |
| [benchmarks](https://github.com/gregale-dev/benchmarks) | Reproducible benchmark datasets, fixtures and verification scripts |

### Community & SDKs
| Repository | What it is |
|---|---|
| [community](https://github.com/gregale-dev/community) | Public Q&A, architecture guides, and troubleshooting [Discussions](https://github.com/gregale-dev/community/discussions) |
| [gregale-js](https://github.com/gregale-dev/gregale-js) | JavaScript and TypeScript SDKs |
| [gregale-python](https://github.com/gregale-dev/gregale-python) | Python SDK |
| [gregale-go](https://github.com/gregale-dev/gregale-go) | Go SDK |

## Links

[Website](https://gregale.dev) ·
[Templates](https://gregale.dev/templates) ·
[Community Q&A](https://github.com/gregale-dev/community/discussions) ·
[Features](https://gregale.dev/features) ·
[Solutions](https://gregale.dev/solutions) ·
[Docs](https://gregale.dev/docs) ·
[Quickstart](https://gregale.dev/docs/quickstart) ·
[Pricing](https://gregale.dev/pricing) ·
[Research](https://gregale.dev/research) ·
[Articles](https://gregale.dev/articles) ·
[llms.txt](https://gregale.dev/llms.txt) ·
[Talk to a founder](https://gregale.dev/contact) ·
[LinkedIn](https://www.linkedin.com/company/gregale/)

Moving from another platform? See Gregale compared with
[Heroku](https://gregale.dev/vs/heroku),
[Render](https://gregale.dev/vs/render),
[Railway](https://gregale.dev/vs/railway),
[Fly.io](https://gregale.dev/vs/fly),
[Coolify](https://gregale.dev/vs/coolify) and
[Cloudflare Workers](https://gregale.dev/vs/cloudflare-workers).
