# AGENTS.md

## What this repo is

A fork of the upstream whatsapp-mcp server, carrying real local source changes so the MCP server I run keeps working. `origin` is my fork; never push to `upstream`.

It is **not a project repo.** It exists so this content is versioned and backed up — not so features get planned and delivered in it.

## Do not create implementation plans

Do not run the Phase delivery chain here. No `implementation-plan`, no `docs/agent-plans/`, no Stage/Step decomposition, no delivery branch, no `implementation-review` / `docs-closeout` / `open-delivery-pr` / `phase-merge-review`. Those skills exist for repos with sustained feature work; here they cost more than the change they wrap.

For any change:

- Edit directly on `main`. Do not branch.
- Validate the cheap way: exercise the changed tool through the running MCP server.
- Commit with a message saying what and why — but commit or push only when asked.

If something genuinely looks too large or too risky for that — a rewrite, a migration, a change you cannot validate in one pass — **say so and ask.** Reaching for a plan on your own is the failure mode this file exists to prevent.

## Everything else

`~/.claude/CLAUDE.md` still governs: git tier, sandbox posture, credentials, output contract. This file removes the plan machinery only. It loosens no guard.
