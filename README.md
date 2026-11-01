# Agent Verification Tools (Apify)

<!-- mcp-name: io.github.JackPT79/agent-verification-tools -->

[![Listed on mcpservers.org](https://mcpservers.org/badge.svg)](https://mcpservers.org/servers/jackpt79/agent-verification-tools)

Remote MCP server (hosted by Apify) exposing four pay-per-result tools for AI agents. JSON output; uncertain results stay `unknown` instead of guessed.

**Endpoint (streamable HTTP):**
`https://mcp.apify.com/?tools=nickatnite79/google-trends-agent-summary,nickatnite79/job-status-checker,nickatnite79/rfp-amendment-analyzer,nickatnite79/shopping-offer-verifier`

Authenticate with your Apify account (OAuth) or `Authorization: Bearer <APIFY_TOKEN>`.

## Tools
- [Google Trends Agent Summary](https://apify.com/nickatnite79/google-trends-agent-summary): interest over time, related queries, rising/flat/falling summary. $0.008 per keyword.
- [Job Status Checker](https://apify.com/nickatnite79/job-status-checker): checks whether Workday/iCIMS postings are open, closed or mismatched. $0.005 per decisive check.
- [RFP Amendment Analyzer](https://apify.com/nickatnite79/rfp-amendment-analyzer): diffs RFP/tender addenda for deadline and requirement changes, with page citations. $1 per comparison.
- [Shopping Offer Verifier](https://apify.com/nickatnite79/shopping-offer-verifier): checks product URLs against exact SKU/model/GTIN; price and stock evidence. $0.01 per check.

## Client config
```json
{"mcpServers":{"agent-verification-tools":{"url":"https://mcp.apify.com/?tools=nickatnite79/google-trends-agent-summary,nickatnite79/job-status-checker,nickatnite79/rfp-amendment-analyzer,nickatnite79/shopping-offer-verifier"}}}
```

License: MIT
