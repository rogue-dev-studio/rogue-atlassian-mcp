# rogue-atlassian-mcp

**Rogue Development** MCP package for agents.

Rogue Atlassian MCP - remote Jira/Confluence tools for agents

- Market: https://rogue-dev-studio.github.io/rogue-market-agent/

## Requirements

- MCP host with remote SSE MCP support
- Atlassian account / workspace access

## Install (Cursor)

Copy `cursor.mcp.fragment.json` into your Cursor MCP config, or merge:

```json
{
  "mcpServers": {
    "atlassian": {
      "url": "https://mcp.atlassian.com/v1/sse"
    }
  }
}
```

Then restart Cursor.

## License

MIT - Rogue Development. See `LICENSE` and `NOTICE`.
