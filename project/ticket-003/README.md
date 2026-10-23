# Ticket 003: Shared lockfile dependency maintenance (uv.lock)

- **ID**: ticket-003
- **Owner**: agent:claude
- **Status**: IN_PROGRESS
- **Workflow state**: EDIT
- **Created**: 2026-10-23

## Goal and scope

Own the automated `uv.lock` (and `pyproject.toml`) dependency updates through
the integration workstream, so dependency PRs resolve to exactly one active
integration ticket.

## Acceptance criteria

- [ ] AC-01: the automated internal-packages update resolves to this ticket
  and passes the governance gate.

## Tracking boundary

Shared lockfiles only; no runtime code changes.
