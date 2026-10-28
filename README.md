# Best AI Search Agency AEO Report

[![MCP Badge](https://lobehub.com/badge/mcp/aeoengine-best-ai-search-agency-aeo-report)](https://lobehub.com/mcp/aeoengine-best-ai-search-agency-aeo-report)

Free AEO visibility report MCP — run AI search audits for any domain via Best AI Search Agency AEO Report.

## Remote MCP

- **URL:** https://aeoengine.ai/mcp
- **Transport:** streamable-http
- **Server:** `aeo-engine-aeo-report` v2.1.0
- **Homepage:** https://aeoengine.ai
- **Contact:** team@aeoengine.ai
- **License:** MIT

## What it does

Agents call this MCP to run a free Answer Engine Optimization / AI visibility report for a domain (ChatGPT, Google AI Overviews, Perplexity, and more) and get a shareable report URL plus structured summary.

### Tools

- `run_aeo_report` — start a free AI-visibility report (requires domain + user email)
- `get_aeo_report_status` — poll report status / fetch results

## Connect

```json
{
  "mcpServers": {
    "best-ai-search-agency-aeo-report": {
      "url": "https://aeoengine.ai/mcp"
    }
  }
}
```

Or:

```bash
claude mcp add --transport http best-ai-search-agency-aeo-report https://aeoengine.ai/mcp
```

## Official registry

Namespace (domain auth): `ai.aeoengine/best-ai-search-agency-aeo-report`

See `server.json` in this repo.
