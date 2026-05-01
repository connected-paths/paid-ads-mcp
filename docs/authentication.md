# Authentication

Paid Ads MCP is a hosted remote MCP server and is not intended for anonymous use.

## How access works

1. Users sign in through the Connected Paths browser account flow.
2. Users connect their Google Ads and/or LinkedIn Ads accounts in the hosted account console.
3. MCP-compatible clients connect to the hosted MCP endpoint after the user has completed authentication and account setup.

## Important notes

- The hosted MCP endpoint requires authenticated access.
- Some marketplaces and registries may mark the server as unhealthy if they probe the endpoint without credentials.
- Marketplace health status does not necessarily indicate an outage; it may reflect missing test credentials or unauthenticated health checks.

## Endpoint

- `https://paidads-mcp.connectedpaths.com/mcp`

## Support

If you need help connecting Paid Ads MCP to a supported AI client, contact:

- `support@connectedpaths.co.uk`
