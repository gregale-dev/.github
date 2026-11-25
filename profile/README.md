# Gregale

**The backend platform for startup teams without an ops person.**

Gregale runs your backend in one place: APIs, background workers, cron jobs,
MCP servers, managed Postgres and S3-compatible object storage. Each app runs
in its own Firecracker microVM, and production releases reach a small share of
traffic before everyone else.

```sh
curl -fsSL https://get.gregale.dev | sh
gregale start ./my-api
```

## Why teams use it

- **Deploy what you already have.** Node, Python, Go or Bun source with no
  Dockerfile, a Dockerfile, a Heroku Procfile, or a Docker Compose file.
- **Isolation by default.** Every app gets its own Firecracker microVM with its
  own kernel.
- **Safe releases.** Each production release goes to 1% of traffic first and
  rolls back on its own on errors (beta). `gregale deploy --diff` previews a
  change, and `gregale rollback` reuses the previous build.
- **Scale to zero.** An idle app pauses about a second after its last request
  and resumes in milliseconds. Billing stops while it is paused.
- **Preview environments.** Every pull request can get its own.
- **Built for agents too.** A CLI, a REST API with an OpenAPI spec, a hosted
  MCP server and SDKs.

## Repositories

| Repository | What it is |
|---|---|
| [gregale-js](https://github.com/gregale-dev/gregale-js) | JavaScript and TypeScript SDKs |
| [gregale-python](https://github.com/gregale-dev/gregale-python) | Python SDK |
| [gregale-go](https://github.com/gregale-dev/gregale-go) | Go SDK |
| [gregale-cursor-plugin](https://github.com/gregale-dev/gregale-cursor-plugin) | Deploy, diagnose and roll back apps from Cursor through Gregale's hosted MCP server |

## Links

[Website](https://gregale.dev) ·
[Docs](https://gregale.dev/docs) ·
[Quickstart](https://gregale.dev/docs/quickstart) ·
[Pricing](https://gregale.dev/pricing) ·
[Talk to a founder](https://gregale.dev/contact) ·
[LinkedIn](https://www.linkedin.com/company/gregale/)

Moving from another platform? See Gregale compared with
[Heroku](https://gregale.dev/vs/heroku),
[Render](https://gregale.dev/vs/render),
[Railway](https://gregale.dev/vs/railway) and
[Fly.io](https://gregale.dev/vs/fly).
