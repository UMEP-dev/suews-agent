# SUEWS Agent Plugin

Self-contained SUEWS plugin marketplace for Claude Code and Codex.

This repository is generated from
[`UMEP-dev/SUEWS`](https://github.com/UMEP-dev/SUEWS). Do not edit generated
plugin contents by hand; update the canonical SUEWS skill in the source
repository and regenerate this distribution.

## Repository Governance

This is a generated distribution mirror, not a development repository. Treat it
as read-only for human edits: changes should be made in `UMEP-dev/SUEWS`, merged
to `master`, and then published here by the SUEWS agent-plugin sync workflow.

The `main` branch should be protected. In the current low-friction setup, the
sync workflow pushes with a fine-grained `SUEWS_AGENT_PUSH_TOKEN` stored only in
`UMEP-dev/SUEWS`, with the token owner kept as the temporary maintainer
exception. Do not push manual content edits here; they will be overwritten by
the next generated sync.

## Install

Claude Code:

```text
/plugin marketplace add UMEP-dev/suews-agent
/plugin install suews@suews
```

Codex:

```bash
codex plugin marketplace add UMEP-dev/suews-agent
codex plugin add suews@suews
```

## Contents

- `.claude-plugin/marketplace.json` and `.claude/skills/suews/` for Claude Code
  (git commit identifies the installed plugin version).
- `.agents/plugins/marketplace.json` and `plugins/suews/` for Codex.
- `.mcp.json` files that launch `suews-mcp` through `uvx`.

Generated from `UMEP-dev/SUEWS` commit `2b766a36491277f6185c18044c2e797329536fd2`.
