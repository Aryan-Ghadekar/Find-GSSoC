# Codex Guide

Codex contributors should start with [AGENT.md](./AGENT.md). This file only adds Codex-specific emphasis.

Related docs:

- [AGENT.md](./AGENT.md)
- [CLAUDE.md](./CLAUDE.md)
- [CONTRIBUTING.md](./CONTRIBUTING.md)

## Working Style

- Inspect the relevant frontend or backend area before editing.
- Match existing repo conventions instead of introducing parallel patterns.
- Keep changes scoped to the issue. Do not bundle opportunistic refactors into the same PR.

## Implementation Guardrails

- For backend work, preserve the existing split between API routes and service-style modules under `backend/src/find_api/`.
- For frontend work, prefer existing utilities in `frontend/src/lib/` before adding new helpers.
- For docs work, verify every command and path against the current repo.

## Review Standard

- Explain the architectural surface area touched by the change, not just the files edited.
- Include the exact checks you ran.
- If you skipped tests or manual verification, state that plainly.

For shared workflow, testing, and anti-slop guidance, return to [AGENT.md](./AGENT.md). Claude-specific notes live in [CLAUDE.md](./CLAUDE.md).
