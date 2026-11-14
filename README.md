# Shellway plugin for AI agents

Let Claude Code, Codex, Cursor or Gemini CLI work on **your own computers and servers** through
[Shellway](https://getshellway.com): run commands, read and edit files, search, run long jobs —
from any device, with no port forwarding or VPN.

This plugin adds:
- the **Shellway MCP server** (`https://mcp.getshellway.com/mcp`, OAuth sign-in), and
- the **`shellway` skill**, which teaches the agent how to use it safely.

## Install

**Claude Code**
```
/plugin marketplace add sandeepkumar466/shellway-agent
/plugin install shellway@shellway
```

**Gemini CLI**
```
gemini extensions install https://github.com/sandeepkumar466/shellway-agent
```

**Cursor**: install **Shellway** from the Cursor Marketplace (once listed), or add it by hand in
`~/.cursor/mcp.json`:
```json
{ "mcpServers": { "shellway": { "url": "https://mcp.getshellway.com/mcp" } } }
```

**Any MCP client**: add a remote (streamable HTTP) MCP server with URL `https://mcp.getshellway.com/mcp`.

Then connect your computer: sign in at https://mcp.getshellway.com/dashboard and run the one-line
command shown there (Windows, macOS, Linux). New accounts get a **7-day free Pro trial, no card**.

## Try
- "List my Shellway computers and show disk usage on each"
- "Find the biggest files in my Downloads folder"
- "My nginx service on the VPS is failing — check the logs and tell me why"

## Links
Website https://getshellway.com · Pricing https://getshellway.com/pricing/ · Privacy https://getshellway.com/privacy/ · Support support@getshellway.com

License: MIT (this plugin's files). Shellway service: https://getshellway.com/terms/
