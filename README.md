# MCP Finder: Claude Code Plugin

Find the right MCP server for any task. Search 4,500+ servers ranked by community trust.

## Install

```
/plugin install c5huracan/mcp-finder
```

## Usage

Just ask Claude to find an MCP server:

> "Find me an MCP server for PostgreSQL access"

> "I need an MCP server for web scraping"

## What's inside

- **4,500+ MCP servers** indexed from awesome-mcp-servers, npm, PyPI, and the official MCP registry
- **Ranked by community trust** - GitHub stars, recency, and usage signals
- **Instant config** - Claude helps you add the server to your `.mcp.json`

## MCP Endpoint

```json
{"mcpServers": {"mcp-finder": {"type": "streamable-http", "url": "https://api.rhdxm.com/mcp/"}}}
```

## REST API

```bash
curl -X POST https://api.rhdxm.com/find -H 'Content-Type: application/json' -d '{"query": "kubernetes monitoring"}'
```

Powered by [Project Meyhem](https://api.rhdxm.com).