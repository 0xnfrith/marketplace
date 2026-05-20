# nfrith-marketplace

Plugin marketplace by nfrith for Claude Code.

## Install

```
/plugin marketplace add nfrith/marketplace
/plugin install claude-canvas@nfrith-marketplace
/plugin install statusline@nfrith-marketplace
/plugin install visualize@nfrith-marketplace
```

## Plugins

- **claude-canvas** — visual brainstorming canvas; Claude paints a system diagram, you riff on it, both see the same surface. Powered by React Flow + dagre + the channels API for operator → Claude push.
- **statusline** — minimal themed Claude Code statusline. Identity prefix, branch, cwd, model, context bar, world clocks, rotating quote. Pure inline; no MCP server, no cache, no external producers.
- **visualize** — diagram-rendering canvas. Claude draws via D2 / raw SVG / image URLs; operator riffs on a tldraw surface.
