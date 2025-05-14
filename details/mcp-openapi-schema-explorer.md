# mcp-openapi-schema-explorer

A token-efficient MCP (Model Context Protocol) server for accessing and exploring OpenAPI/Swagger specifications via MCP Resources, designed for intelligent API exploration and integration.

- **Source:** [GitHub Repository](https://github.com/kadykov/mcp-openapi-schema-explorer)
- **Category:** API Integration MCP Servers
- **Tags:** mcp, openapi, swagger, api-integration, exploration

---

## Features

- **Token-efficient exploration**: Enables clients to access and explore large OpenAPI (v3.0) and Swagger (v2.0) specs without loading the entire file into an LLM context window.
- **Supports both local and remote specs**: Load OpenAPI/Swagger specifications from local file paths or remote HTTP/HTTPS URLs.
- **Automatic conversion**: Swagger v2.0 specs are automatically converted to OpenAPI v3.0 format upon loading.
- **MCP Resource-based access**: Exposes parts of the API spec as MCP Resources (not Tools), supporting granular, read-only data exploration tailored for MCP clients (e.g., Claude Desktop, Cline).
- **Flexible installation and usage**:
  - Use via `npx` (recommended, always latest version)
  - Docker image available (`kadykov/mcp-openapi-schema-explorer`)
  - Supports global npm installation
  - Can be run from local development builds
- **Resource templates for exploration**:
  - `openapi://{field}`
  - `openapi://paths/{path}`
  - `openapi://paths/{path}/{method*}` (multi-method fetch)
  - `openapi://components/{type}`
  - `openapi://components/{type}/{name*}` (multi-name fetch)
- **Multi-value parameter support**: Resource parameters can accept multiple comma-separated values for batch fetching.
- **No separate configuration required**: Server is configured via client settings; command-line arguments are passed through the MCP client.
- **Semantic release management**: Uses semantic-release for automated versioning and publishing.

## Pricing

No pricing information is provided. The project is open source.

## License

Open source (see [LICENSE](https://github.com/kadykov/mcp-openapi-schema-explorer/blob/main/LICENSE)).
