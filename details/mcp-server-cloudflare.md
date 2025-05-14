# mcp-server-cloudflare

**Source:** [GitHub Repository](https://github.com/cloudflare/mcp-server-cloudflare)

## Description
mcp-server-cloudflare is an implementation of the Model Context Protocol (MCP), enabling seamless integration between MCP clients and various Cloudflare services (such as Workers, KV, R2, D1, and many others). It allows users to manage, observe, and automate tasks on Cloudflare via natural language or programmatic access through the MCP protocol.

## Features
- **Integration with Cloudflare Services:** Connects MCP clients to a wide range of Cloudflare services, including:
  - Workers (application development, bindings for storage/AI/compute)
  - KV, R2, D1 (storage and database services)
  - Observability (logs, analytics, debugging)
  - Radar (internet traffic insights, trends)
  - Logpush (summaries for job health)
  - AI Gateway (log search, prompt/response details)
  - AutoRAG (document listing/search)
  - Audit Logs (query and report generation)
  - DNS Analytics (DNS performance and debugging)
  - Digital Experience Monitoring (application monitoring)
  - Cloudflare One CASB (security misconfiguration detection for SaaS)
  - Browser rendering (web page fetching, markdown conversion, screenshots)
  - Container server (sandboxed development environments)
- **Natural Language Operations:** Allows use of natural language to read configurations, process information, make suggestions, and apply changes across Cloudflare services.
- **Remote MCP Server Access:** Can be accessed by any MCP client supporting remote servers (e.g. Cloudflare AI Playground, Cursor, Claude).
- **Template and Extensible Design:** Includes several server types as templates for building similar integrations.
- **Open Source:** Licensed under Apache-2.0, with active community and contribution guidelines.
- **Paid Features:** Some advanced features may require a paid Cloudflare Workers plan.

## Pricing
- **Open Source:** The MCP server itself is open source and free to use.
- **Cloudflare Paid Features:** Certain Cloudflare service integrations may require a paid subscription on your Cloudflare account (e.g., for advanced Workers features).

## Tags
`mcp`, `cloudflare`, `cloud`, `automation`