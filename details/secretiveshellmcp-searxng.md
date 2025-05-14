# SecretiveShell/mcp-searxng

**Description:**
An MCP server designed to connect agentic systems to SearXNG instances, enabling privacy-respecting metasearch through the MCP protocol.

**Source:** [GitHub Repository](https://github.com/SecretiveShell/MCP-searxng)

**Category:** web-search-mcp-servers

**Tags:** mcp, search, searxng, privacy

---

## Features
- Acts as an MCP (Machine Communication Protocol) server for search integration.
- Connects agentic systems (e.g., automated agents or client applications) to SearXNG search instances.
- Enables privacy-respecting web search via the SearXNG metasearch engine.
- Supports configuration of custom SearXNG server URL via the `SEARXNG_URL` environment variable (default: `http://localhost:8080`).
- Usable with different client setups, including via `uvx` or git clone.
- Can be integrated with platforms like Claude Desktop.
- Open-source with available Dockerfile for containerized deployment.

## Usage
- Run the server using `uvx mcp-searxng` or by cloning the repository and executing locally.
- Configure the search backend by setting the `SEARXNG_URL` environment variable.
- Integrate with MCP clients for agentic search capabilities.

## Pricing
No pricing information is provided; the project appears to be open-source.

## License
License information is available in the repository.