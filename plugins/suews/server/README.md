# suews-mcp (vendored)

This folder is a copy of the `mcp/` package in the SUEWS source repository,
vendored into the plugin with a lockfile so the plugin runs the Model Context
Protocol server from its own files. The plugin's `.mcp.json` starts it with
`uv run --frozen`; there is nothing to install by hand. Development, tests and
documentation for the server live in the source repository.
