# Gregale

**The backend platform for startup teams without an ops person.**

Deploy web APIs, background workers, schedulers, managed Postgres, remote MCP
servers, private sandboxes and AI agent workflows in one CLI command (`gregale
deploy` or `git push`) on isolated Firecracker MicroVMs. Zero YAML required,
scale-to-zero included, with hard monthly spending caps so unexpected traffic
or runaway bot loops cannot surprise your bill.

## Repositories

### Agent & IDE Integrations
| Repository | What it is |
|---|---|
| [gregale-cursor-plugin](https://github.com/gregale-dev/gregale-cursor-plugin) | Deploy, diagnose and roll back apps from Cursor through Gregale's hosted MCP server |
| [gregale-antigravity-plugin](https://github.com/gregale-dev/gregale-antigravity-plugin) | Deploy, diagnose and roll back apps from Antigravity through Gregale's hosted MCP server |
| [gregale-claude-code-plugin](https://github.com/gregale-dev/gregale-claude-code-plugin) | Claude Code plugin & marketplace for deploying and diagnosing Gregale apps via MCP |

### Remote MCP Server Starters
| Repository | What it is |
|---|---|
| [mcp-server-node](https://github.com/gregale-dev/mcp-server-node) | Stateless Streamable HTTP MCP server in Node.js that scales to zero (external OAuth, scoped tools, `AGENTS.md`) |
| [mcp-server-python](https://github.com/gregale-dev/mcp-server-python) | Stateless Streamable HTTP MCP server in Python with `PyJWT` external OAuth & `AGENTS.md` |
| [mcp-server-go](https://github.com/gregale-dev/mcp-server-go) | Stateless Streamable HTTP MCP server in Go (`modelcontextprotocol/go-sdk`) with external OAuth & `AGENTS.md` |

### Application Starters & Benchmarks
| Repository | What it is |
|---|---|
| [node-api-worker](https://github.com/gregale-dev/node-api-worker) | Node.js HTTP API + durable background worker & queue starter |
| [fastapi-postgres-jobs](https://github.com/gregale-dev/fastapi-postgres-jobs) | FastAPI HTTP service + async background jobs + managed Postgres starter |
| [benchmarks](https://github.com/gregale-dev/benchmarks) | Reproducible benchmark datasets, fixtures and verification scripts |

### Official SDKs
| Repository | What it is |
|---|---|
| [gregale-js](https://github.com/gregale-dev/gregale-js) | JavaScript and TypeScript SDKs |
| [gregale-python](https://github.com/gregale-dev/gregale-python) | Python SDK |
| [gregale-go](https://github.com/gregale-dev/gregale-go) | Go SDK |

## Links

[Website](https://gregale.dev) ·
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
