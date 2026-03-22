# ⭐ reviewOracle

**Consumer MCP Server** — 8 tools | Part of [ToolOracle](https://tooloracle.io)

![Tools](https://img.shields.io/badge/MCP_Tools-8-10B898?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-00C853?style=flat-square)
![Tier](https://img.shields.io/badge/Tier-Free-2196F3?style=flat-square)

## Quick Connect

```bash
# Claude Desktop / Cursor / Windsurf
npx -y mcp-remote https://tooloracle.io/review/mcp/
```

```json
// claude_desktop_config.json
{
  "mcpServers": {
    "revieworacle": {
      "command": "npx",
      "args": ["-y", "mcp-remote", "https://tooloracle.io/review/mcp/"]
    }
  }
}
```

## Tools (8)

| Tool | Description |
|------|-------------|
| `review_search` | Search for product reviews, tests, and ratings from news sources. Returns articl |
| `brand_monitor` | Monitor all news mentions of a brand. Returns mention count, top sources, and re |
| `competitor_compare` | Compare news sentiment between your brand and a competitor. Returns sentiment sc |
| `product_reviews` | Find product test and review articles. Highlights trusted sources like Stiftung  |
| `sentiment_trend` | Analyze overall sentiment trend for a brand based on recent news. Returns positi |
| `warentest_search` | Search Stiftung Warentest results for any product category. |
| `alert_check` | Check for recent negative news, recalls, warnings or lawsuits about a brand. |
| `health_check` | ReviewOracle server status. |

## Pricing

| Tier | Rate Limit | Price |
|------|-----------|-------|
| Free | 100 calls/day | €0 |
| Pro | 10,000 calls/day | €29/month |
| Enterprise | Unlimited | Custom |

> Free tier includes all tools with rate limiting. Upgrade for higher limits and priority support.

## Part of ToolOracle

reviewOracle is one of **42 specialized MCP servers** in the [ToolOracle](https://tooloracle.io) ecosystem — the largest collection of production-ready MCP tools for AI agents.



**Related Oracles:**
- [FeedOracle](https://feedoracle.io) — Evidence-grade compliance data infrastructure
- [ToolOracle](https://tooloracle.io) — 42 Oracles, 390+ MCP Tools

## Links

- 🌐 Live: `https://tooloracle.io/review/mcp/`
- 📚 Docs: [tooloracle.io/docs](https://tooloracle.io/docs)
- 🏠 Platform: [tooloracle.io](https://tooloracle.io)

---

*Built by [FeedOracle](https://feedoracle.io) — Evidence by Design*
