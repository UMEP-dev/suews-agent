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

- `plugins/suews/`: the plugin itself, shared by every host. It holds
  `.claude-plugin/plugin.json` (Claude Code and Anthropic's plugin directory),
  `.codex-plugin/plugin.json` (Codex), the `suews` skill, and a `.mcp.json` that
  launches `suews-mcp` through `uvx`, pinned to the source commit below.
- `.claude-plugin/marketplace.json` for Claude Code (git commit identifies the
  installed plugin version).
- `.agents/plugins/marketplace.json` for Codex.

Generated from `UMEP-dev/SUEWS` commit `e104f519eb336f53e91ae4141df4ba9bbd9013e4`.
