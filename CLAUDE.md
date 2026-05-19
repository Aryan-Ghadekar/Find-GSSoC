# Claude Guide

Claude contributors should start with [AGENT.md](./AGENT.md). This file only adds Claude-specific emphasis.

Related docs:

- [AGENT.md](./AGENT.md)
- [CODEX.md](./CODEX.md)
- [CONTRIBUTING.md](./CONTRIBUTING.md)

## Working Style

- Read the existing repo docs before drafting implementation plans or PR summaries.
- Stay concrete about the real stack: Next.js frontend, FastAPI backend, Redis/RQ jobs, MinIO storage, and PostgreSQL with pgvector.
- Prefer concise change descriptions over broad design narration.

## Implementation Guardrails

- Confirm whether the issue is frontend, backend, docs, or cross-stack before changing anything.
- Preserve existing repo terminology such as upload, indexing, search, clustering, light stack, and full stack.
- Do not add generic assistant advice that is not specific to this codebase or contribution flow.

## Review Standard

- Summaries should mention the affected workflow, not just edited files.
- PR notes should include test commands run and any manual checks performed.
- If the change depends on assumptions, list them directly so reviewers can validate them quickly.

For shared workflow, testing, and anti-slop guidance, return to [AGENT.md](./AGENT.md). Codex-specific notes live in [CODEX.md](./CODEX.md).
