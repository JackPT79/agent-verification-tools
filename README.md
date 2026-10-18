# Agent Verification Tools (Apify)

<!-- mcp-name: io.github.JackPT79/agent-verification-tools -->

[![Listed on mcpservers.org](https://mcpservers.org/badge.svg)](https://mcpservers.org/servers/jackpt79/agent-verification-tools)

Remote MCP server (hosted by Apify) exposing four pay-per-result tools for AI agents. JSON output; uncertain results stay `unknown` instead of guessed.

**Endpoint (streamable HTTP):**
`https://mcp.apify.com/?tools=nickatnite79/google-trends-agent-summary,nickatnite79/job-listing-rechecker,nickatnite79/rfp-amendment-analyzer,nickatnite79/shopping-offer-verifier`

Authenticate with your Apify account (OAuth) or `Authorization: Bearer <APIFY_TOKEN>`.

## Tools
- [Google Trends Agent Summary](https://apify.com/nickatnite79/google-trends-agent-summary): interest over time, related queries, rising/flat/falling summary. Launch price $0.004 per keyword (normally $0.008).
- [Job Listing Rechecker](https://apify.com/nickatnite79/job-listing-rechecker): checks whether Workday/iCIMS postings are open, closed or mismatched. $0.005 per decisive check.
- [RFP Amendment Analyzer](https://apify.com/nickatnite79/rfp-amendment-analyzer): diffs RFP/tender addenda for deadline and requirement changes, with page citations. Launch price $0.25 per comparison (normally $1).
- [Shopping Offer Verifier](https://apify.com/nickatnite79/shopping-offer-verifier): checks product URLs against exact SKU/model/GTIN; price and stock evidence. Launch price $0.005 per check (normally $0.01).

## Client config
```json
{"mcpServers":{"agent-verification-tools":{"url":"https://mcp.apify.com/?tools=nickatnite79/google-trends-agent-summary,nickatnite79/job-listing-rechecker,nickatnite79/rfp-amendment-analyzer,nickatnite79/shopping-offer-verifier"}}}
```

License: MIT
