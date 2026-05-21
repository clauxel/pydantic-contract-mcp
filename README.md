# Pydantic Contract MCP

Pydantic Contract remote MCP for Pydantic AI structured output.

Paid remote MCP for Pydantic AI structured output, structured receipts, usage logs, and audit-ready evidence for agent and CI workflows.

## Public Endpoints

- Website: https://pydanticcontract.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- MCP endpoint: https://pydanticcontract.clauxel.com/mcp
- Server card: https://pydanticcontract.clauxel.com/server-card.json
- Registry name: `com.clauxel.pydanticcontract/pydanticcontract-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `contract_validate`
- `schema_diff`
- `repair_hint`
- `contract_receipt`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://pydanticcontract.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- Pricing: https://pydanticcontract.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605#pricing
- Server card: https://pydanticcontract.clauxel.com/server-card.json
- MCP endpoint: https://pydanticcontract.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
