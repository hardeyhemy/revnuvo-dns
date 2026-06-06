# Revnuvo DNS Intelligence

DNS Intelligence API for AI Agents.

## Tools

## Available on Smithery

[Install via Smithery](https://smithery.ai/server/tijaniiismael62/revnuvo-dns)
### verify_domain

Checks if a domain exists and returns:

- exists
- has_mx
- has_a
- dnssec
- checked_at

### resolve_domain_dns

Returns:

- A records
- AAAA records
- MX records
- TXT records
- NS records

## MCP Endpoint

https://mcp.revnuvo.site/mcp

## DNS API

https://dns.revnuvo.site

## Example

verify_domain("stripe.com")

resolve_domain_dns("stripe.com")
