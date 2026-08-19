# Claude Autonomous iOS Agent

A reusable Claude Code configuration for an iOS repository.

## Included

- `CLAUDE.md` — global project instructions
- `.claude/agents/` — specialized engineering agents
- `.claude/commands/` — reusable commands
- `.claude/rules/` — Swift, concurrency, and Xcode rules
- `docs/` — workflow documentation

## Suggested usage

Copy the `.claude` directory and `CLAUDE.md` into the root of an iOS repository where this configuration is allowed.

Start with the `start` workflow, then implement incrementally and verify frequently.

The setup is intentionally generic so it can be reused across different iOS projects.
