# Paid Ads MCP

Paid Ads MCP is a hosted MCP server for Google Ads and LinkedIn Ads that lets marketers use ChatGPT, Claude, Cursor, and other MCP-compatible AI clients to analyze paid media performance, generate visual cross-channel reports, review account structure, compare campaigns, surface recommendations, and monitor weekly trends without exporting spreadsheets or switching between ad platforms.

## What it does

Paid Ads MCP connects AI assistants to live paid media data so marketing teams can:

- analyze Google Ads and LinkedIn Ads account performance
- generate combined Google Ads and LinkedIn Ads dashboards with channel tabs
- review campaign, ad, keyword, and search term performance
- compare results against the immediately preceding same-length period
- generate weekly reporting views and account diagnostics
- inspect trends for spend, impressions, clicks, conversions, and views
- identify optimization opportunities faster with natural-language workflows

## Who it is for

- performance marketers
- paid media managers
- growth teams
- digital agencies
- marketing operations teams

## MCP endpoint

- Hosted endpoint: `https://paidads-mcp.connectedpaths.com/mcp`
- Transport: `Streamable HTTP`

## Supported platforms

- Google Ads
- LinkedIn Ads

## Reporting behavior

For broad report prompts, Paid Ads renders a visual dashboard rather than returning raw data only. Cross-channel dashboards include All channels, Google Ads, and LinkedIn Ads tabs, campaign breakdowns, trend controls, and an executive summary written from a paid-media perspective.

Multi-window reporting uses like-for-like comparison by default: 7 days vs prior 7 days, 30 days vs prior 30 days, and 90 days vs prior 90 days.

## Authentication and access

Paid Ads MCP is a hosted authenticated server.

- Users sign in through the Connected Paths hosted account flow
- Ad-platform connections are managed in the Paid Ads account console
- Access to the hosted product is gated by an active billing entitlement

More detail:

- [Authentication](./docs/authentication.md)
- [Billing](./docs/billing.md)
- [Supported tools](./docs/supported-tools.md)
- [Troubleshooting](./docs/troubleshooting.md)

## Product website

- Website: `https://connectedpaths.com/tools/paid-ads-mcp-server/`

## Support

- Email: `support@connectedpaths.co.uk`

## Repository purpose

This repository is the public docs and manifest surface for the hosted Paid Ads MCP server. It is intended for MCP registries, marketplaces, customers, and evaluators who need a public reference for metadata, setup guidance, and support information.
