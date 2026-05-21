# Quickstart

Pydantic Contract is a hosted remote MCP for Pydantic AI structured output.

## Fast Path

1. Open Pydantic Contract and select the buyer plan.
2. Create or request a bearer token from the hosted product.
3. Add https://pydanticcontract.clauxel.com/mcp to a compatible MCP client.
4. Run tools/list, then call contract_validate with public-safe sample data.
5. Save the returned receipt or export for human review.

## Useful Links

- https://pydanticcontract.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=pydanticcontract_public_docs&utm_content=quickstart_home
- https://pydanticcontract.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=pydanticcontract_public_docs&utm_content=quickstart_pricing
- https://pydanticcontract.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=pydanticcontract_public_docs&utm_content=quickstart_checkout

## MCP Endpoint

```text
https://pydanticcontract.clauxel.com/mcp
```

Use bearer-token authentication for production calls. Keep the token in the MCP client's secret mechanism.
