# SUEWS Agent Plugin

Self-contained SUEWS plugin marketplace for Claude Code and Codex.

This repository is generated from
[`UMEP-dev/SUEWS`](https://github.com/UMEP-dev/SUEWS). Do not edit generated
plugin contents by hand; update the canonical SUEWS skill in the source
repository and regenerate this distribution.

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

Generated from `UMEP-dev/SUEWS` commit `ad044655d3533fe300b0a4e809c37158a3869634`.
