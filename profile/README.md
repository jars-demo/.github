
**Practical engineering. Learned by building.**

JARS DEMO is an independent collection of open-source workshops, developer tools, and hands-on engineering labs.

Explore modern technologies through working implementations, guided experiments, and practical demonstrations. Every project is designed to help developers go beyond documentation and understand how things work in practice.

Most workshops follow the same shape: short chapters, a small app with real bugs in it, and a check that tells you when your fix works. Each one has its own site to read along.

---

## Workshops & Learning Labs

### AI & agents

| Workshop | What you'll learn | Site |
|---|---|---|
| [Local AI](https://github.com/jars-demo/local-ai-demo) | Build a full-stack AI notes assistant with Next.js, FastAPI, PostgreSQL and a small model on Ollama, then ship it to a Linux server with no internet connection. | [local-ai.jishanahmed.in](https://local-ai.jishanahmed.in) |
| [Evals, not vibes](https://github.com/jars-demo/evals-demo) | Build a tiny eval harness in plain Python and compare prompts and models with numbers instead of opinions. | [evals.jishanahmed.in](https://evals.jishanahmed.in) |
| [Build your own MCP](https://github.com/jars-demo/build-your-mcp-demo) | Build Jotter, a real MCP server in TypeScript: tools, resources, prompts, tests, stdio and Streamable HTTP, connected to Claude Code, Cursor and VS Code. | [buildyourmcp.jishanahmed.in](https://buildyourmcp.jishanahmed.in) |
| [MCP vs API](https://github.com/jars-demo/mcp-vs-api-demo) | Run the same AI request through a traditional API integration and through MCP, side by side, and watch every step. | [mcp-vs-api.jishanahmed.in](https://mcp-vs-api.jishanahmed.in) |
| [Cognee](https://github.com/jars-demo/cognee-demo) | AI memory with cognee: turn your data into a knowledge graph that agents can search, reason over and keep up to date. | [cognee.jishanahmed.in](https://cognee.jishanahmed.in) |

### Data & databases

| Workshop | What you'll learn | Site |
|---|---|---|
| [Make the slow query fast](https://github.com/jars-demo/slow-query-demo) | Read query plans, choose the right index, fix N+1 queries, page without OFFSET and guard plans in CI, on a 200,000 order SQLite shop. | [slowquery.jishanahmed.in](https://slowquery.jishanahmed.in) |
| [Pull the plug](https://github.com/jars-demo/build-a-database-demo) | Build a key-value database from scratch, then crash it at every byte: an append-only log, an index, checksums, fsync, group commit and compaction. | [database.jishanahmed.in](https://database.jishanahmed.in) |
| [FalkorDB](https://github.com/jars-demo/falkordb-demo) | Graph databases and graph-powered applications with FalkorDB, the fast, open-source graph database. | [falkordb.jishanahmed.in](https://falkordb.jishanahmed.in) |
| [Why did our AI assistant get worse?](https://github.com/jars-demo/datahub-ai-rca) | A support assistant on Pinecone and Langfuse starts giving wrong answers, with no crash and no alert. Bring both into DataHub, follow one lineage graph from source documents to production traces, and let an agent on any LLM find the cause, the owner and the fix. Built to show the DataHub connectors for [Pinecone](https://github.com/datahub-project/datahub/pull/16472) (merged) and [Langfuse](https://github.com/datahub-project/datahub/pull/19923) (in review) at work. | [Workshop guide](https://github.com/jars-demo/datahub-ai-rca/tree/main/workshop) |
| [cognee Data Engineering Lab](https://github.com/jars-demo/cognee-data-lab) | Apache Airflow and DataHub connectors for cognee, and a lab that shows what agent memory of your data platform unlocks. | [Watch the demo](https://youtu.be/9-4LVBFVDww) |

### Backend & APIs

| Workshop | What you'll learn | Site |
|---|---|---|
| [FastAPI](https://github.com/jars-demo/fastapi-demo) | Build Shelf, a production-shaped reading-list API, in twelve chapters: validation, SQLAlchemy, auth, tests, logs and Docker. | [fastapi.jishanahmed.in](https://fastapi.jishanahmed.in) |
| [Rate limits from scratch](https://github.com/jars-demo/rate-limit-demo) | Build fixed window, sliding log and token bucket limiters in plain Python, serve 429s, and write a client that backs off politely. | [ratelimit.jishanahmed.in](https://ratelimit.jishanahmed.in) |
| [Every row, exactly once](https://github.com/jars-demo/pagination-demo) | Eight real pagination bugs in a small record shop: offsets, limits, stable order, keyset cursors with ties, opaque cursors, knowing when to stop and syncing changes. | [pagination.jishanahmed.in](https://pagination.jishanahmed.in) |
| [Caching, from first principles](https://github.com/jars-demo/caching-demo) | Eight real caching bugs in one small bookshop: keys, invalidation, private answers, TTLs, stampedes, eviction, negative caching and HTTP ETags. | [caching.jishanahmed.in](https://caching.jishanahmed.in) |
| [Once, in order, on time](https://github.com/jars-demo/notifications-demo) | Ten real bugs in a notification service: the outbox, idempotency keys, backoff and jitter, ordering, consent, quiet hours, digests, priority lanes and signed webhooks. | [notifications.jishanahmed.in](https://notifications.jishanahmed.in) |
| [gRPC](https://github.com/jars-demo/grpc-demo) | How HTTP, TLS, HTTP/2 and gRPC fit together: build a real service, secure it with TLS and mutual TLS, and debug real certificate failures. | [grpc.jishanahmed.in](https://grpc.jishanahmed.in) |

### Security

| Workshop | What you'll learn | Site |
|---|---|---|
| [How systems talk](https://github.com/jars-demo/how-systems-talk-demo) | Stage 1 of a security series: eight local lab cases on DNS, HTTP framing, TLS, cookies, sessions, security headers and access logs, each with a fix and a check. | [howsystemstalk.jishanahmed.in](https://howsystemstalk.jishanahmed.in) |
| [Enterprise auth, hands on](https://github.com/jars-demo/enterprise-auth-demo) | Run an OIDC single sign-on flow with PKCE, verify ID tokens, read SAML, map roles, find a cross-tenant leak and stop it with Postgres row-level security. | [enterpriseauth.jishanahmed.in](https://enterpriseauth.jishanahmed.in) |
| [PyArmor](https://github.com/jars-demo/pyarmor-demo) | Protect a FastAPI app with PyArmor, verify it, ship it in Docker, and learn the real security boundary of obfuscated Python. | [pyarmor.jishanahmed.in](https://pyarmor.jishanahmed.in) |

### DevOps & delivery

| Workshop | What you'll learn | Site |
|---|---|---|
| [Docker, from first container to production](https://github.com/jars-demo/docker-demo) | Twelve exercises on real Docker: the build cache, secrets, networking, volumes, Compose, multi-stage builds, signals, health checks, cgroup limits and digests. | [docker.jishanahmed.in](https://docker.jishanahmed.in) |
| [GitHub Actions: CI/CD from zero](https://github.com/jars-demo/github-actions-demo) | Take a small app from no automation to tested, released, containerised and deployed on every push. | [githubactions.jishanahmed.in](https://githubactions.jishanahmed.in) |
| [Ship it to the island](https://github.com/jars-demo/air-gap-demo) | Deploy into a network with no internet: catch phone-homes, pack a sealed reproducible crate, carry its wheels, run with no network and roll back. | [airgap.jishanahmed.in](https://airgap.jishanahmed.in) |
| [OpenTelemetry incident lab](https://github.com/jars-demo/otel-demo) | Break a distributed system, trace the failure with OpenTelemetry, find the root cause and fix it. | [otel.jishanahmed.in](https://otel.jishanahmed.in) |

### Foundations

| Workshop | What you'll learn | Site |
|---|---|---|
| [Git good](https://github.com/jars-demo/git-demo) | Learn Git by fixing real repositories with HEAD the cat: twelve quests from your first commit to merge conflicts, rebase, bisect, the reflog and AI agents. | [git.jishanahmed.in](https://git.jishanahmed.in) |
| [Debug like a detective](https://github.com/jars-demo/debugging-demo) | Eight real bugs in a tiny bakery app, solved with tracebacks, failing tests, logging, pdb, bisection, profiling and written-down assumptions. | [debugging.jishanahmed.in](https://debugging.jishanahmed.in) |
| [Concurrency, from first principles](https://github.com/jars-demo/concurrency-demo) | Eight real concurrency bugs in one busy kitchen: threads and the GIL, races, locks, deadlock, queues, asyncio, semaphores, timeouts and cancellation. | [concurrency.jishanahmed.in](https://concurrency.jishanahmed.in) |
| [TypeScript](https://github.com/jars-demo/typescript-demo) | Build Streak, a typed habit tracker and CLI, in ten chapters: unions, generics, safe parsing, errors as values and Vitest. | [typescript.jishanahmed.in](https://typescript.jishanahmed.in) |

---

## Developer Tools

Reusable engineering tools designed to extend beyond a single workshop.

- **[Breakdown](https://github.com/jars-demo/wispr-demo)** - *Shipped it? Now understand it.* A three-minute game for every change your coding agent ships: replay what it did, the engineering behind it, predict-the-behaviour questions and an explain-back round. Built hands-free with Wispr Flow for No Hands: The Wispr Challenge (WeMakeDevs). Live at [wispr.jishanahmed.in](https://wispr.jishanahmed.in).
- **[MailingKit](https://github.com/jars-demo/mailingkit-demo)** - A drop-in, provider-agnostic transactional email layer for Python. One small typed API for SMTP, Resend or your own provider, with templates, retries and idempotency. Docs at [mailingkit.jishanahmed.in](https://mailingkit.jishanahmed.in).
- **[Companion Kit](https://github.com/jars-demo/companion-demo)** - Playful, accessible companions for any React app: a copy-in kit, six ready characters and a ten-chapter workshop to draw your own. Live at [companion.jishanahmed.in](https://companion.jishanahmed.in).

## Agent Skills & Playbooks

Focused, reusable instructions and workflows for AI-assisted development.

- **[JARS Skills](https://github.com/jars-demo/jars-skills)** - 60+ agent skills, one focused playbook each, for Claude Code, Cursor, GitHub Copilot, Codex, Gemini CLI and more. Browse them at [skills.jishanahmed.in](https://skills.jishanahmed.in).

---

## Principles

- **Learn by doing.** Working code over theory alone.
- **Reproducible by design.** Clear setup instructions and verifiable results.
- **Understand the trade-offs.** Explore limitations, failure modes, and implementation choices.
- **Independent by default.** Each project maintains its own scope, dependencies, and lifecycle.
- **Open to collaboration.** Contributions, feedback, and thoughtful experimentation are welcome.

## Get involved

Choose a project, follow its setup instructions, experiment with the implementation, and explore the underlying technology.

Found an issue or have an idea? Open an issue or contribute directly to the relevant repository.

---

**JARS DEMO**  - Created and Maintained by **[Jishanahmed AR Shaikh (JARS)](https://jishanahmed.in)**

[GitHub](https://github.com/jars-demo) · [Portfolio](https://jishanahmed.in) · [Mail](mailto:jishanahmedshaikh@gmail.com)
