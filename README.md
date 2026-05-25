# Chrome DevTools Session MCP

Chrome DevTools Session MCP is a hosted remote MCP for AI agent browser DevTools MCP.

This repository is a public documentation project for Chrome DevTools Session MCP. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://chromedevtoolsmcp.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=chromedevtoolsmcp_public_docs&utm_content=readme_home
- Pricing: https://chromedevtoolsmcp.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=chromedevtoolsmcp_public_docs&utm_content=readme_pricing
- Checkout: https://chromedevtoolsmcp.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=chromedevtoolsmcp_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://chromedevtoolsmcp.clauxel.com/mcp
- Server card: https://chromedevtoolsmcp.clauxel.com/server-card.json
- Registry name: `com.clauxel.chromedevtoolsmcp/chromedevtoolsmcp-mcp`
- Tools: `inspect_page_state`, `read_console_errors`, `summarize_network_waterfall`, `export_devtools_receipt`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

AI product teams, operations leads, workflow owners, and technical evaluators.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: inspect_page_state
- MCP tool: read_console_errors
- MCP tool: summarize_network_waterfall
- MCP tool: export_devtools_receipt

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
