# Milos Cvetkovic

**Senior Full-Stack Engineer · Platform & Architecture** — Belgrade, Serbia

13+ years building and modernising production systems, 8+ of them in lead and architecture roles. Currently the sole senior engineer rebuilding a UK commodity-trading platform: 13 NestJS/Fastify microservices across 9 DDD bounded contexts on Kubernetes — GitOps, canary releases, SLO-gated automatic rollback — ~250k lines of TypeScript from empty repo to live multi-tenant environment, delivered largely through an AI-assisted loop I designed (~780 merged PRs in 7 months).

## What I work with

- **TypeScript, end to end** — NestJS · Fastify · React 18 · PostgreSQL · RabbitMQ · Nx
- **Platform** — Kubernetes (AKS) · ArgoCD + Argo Rollouts · Terraform · GitHub Actions · OpenTelemetry/Grafana
- **AI-native delivery** — Claude Code & Claude Agent SDK: agent loops with independent verification. Maker ≠ checker; done is a claim, not a proof.

## Featured

- [panlode](https://github.com/milosCvetkovicDev/panlode) · **[docs online](https://miloscvetkovicdev.github.io/panlode/)** — evidence before code: a Claude Code plugin and workspace that validates startup ideas before anything is built. Subagents read public forums, review sites and job boards for customer pain; every signal keeps its source link and an evidence score, and each idea runs one cheap experiment at a time (at most 100 € and 14 days) that ends in continue, pivot or kill. Plain Markdown in git, checked on every write by a dependency-free Python engine wired into four Claude Code hooks.
  - [A real run](https://github.com/milosCvetkovicDev/panlode/tree/main/examples/first-scout-run) — 19 candidates, 16 signals, three clusters, and no idea yet, on purpose: weak evidence says the pain exists, not that anyone pays.
  - [How it compares](https://miloscvetkovicdev.github.io/panlode/comparison.html) — against AI idea generators, validation canvases, social listening tools and spreadsheets.

- [claude-code-monorepo](https://github.com/milosCvetkovicDev/claude-code-monorepo) · **[read it online](https://miloscvetkovicdev.github.io/claude-code-monorepo/)** — the real, sanitized Claude Code configuration behind that platform, written up as a 13-chapter book: 71 skills, 34 hooks, 31 agents, 172 memories, one full epic walkthrough.
  - [Loops, not prompts](https://miloscvetkovicdev.github.io/claude-code-monorepo/book/02-loops-not-prompts/) — six primitives mapped to the concrete tools that enforce them.
  - [An epic, start to finish](https://miloscvetkovicdev.github.io/claude-code-monorepo/book/11-an-epic-start-to-finish/) — one initiative from PRD to verified-green, including the pilot that found three defects in its own test baseline.
  - [How it was sanitized](https://miloscvetkovicdev.github.io/claude-code-monorepo/sanitization/) — six adversarial audit rounds; each found a class the previous round's method could not see.

- [football-trackers](https://github.com/milosCvetkovicDev/football-trackers) · **[docs online](https://miloscvetkovicdev.github.io/football-trackers/)** — a DIY real-time GPS tracking system for youth football, built end to end as a personal project: ESP32+GNSS wearables → authenticated MQTT → Bun/Elysia ingest → live coach view on a React canvas, plus an offline CV subproject. Privacy-first by construction — pseudonymous ids on the wire and at rest, per-player erasure that also rewrites every backup and proves it by re-count.
  - [How this is built](https://github.com/milosCvetkovicDev/football-trackers#how-this-is-built) — 25 cross-referenced ADRs; 32-suite server gate behind a runner that cannot silently shrink; Playwright e2e across five self-contained stacks driven by a simulated device fleet (no hardware, no mocks); static posture guards that fail CI if a deploy stack drifts.
  - [Decision records](https://miloscvetkovicdev.github.io/football-trackers/docs/decisions/) — from transport choice and MQTT security to location-data retention and right-to-erasure.

## Elsewhere

[LinkedIn](https://linkedin.com/in/milos-cvetkovic-dev) · cvetkovicmilos@gmail.com
