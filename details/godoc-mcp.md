# godoc-mcp

An MCP (Model Context Protocol) server that provides token-efficient access to Go documentation, allowing AI assistants and LLMs to retrieve Go package docs without needing full source files.

**Source:** [github.com/mrjoshuak/godoc-mcp](https://github.com/mrjoshuak/godoc-mcp)

**Category:** Documentation & Learning Resources

**Tags:** mcp, documentation, golang, open-source

---

## Features

- Provides an MCP server for accessing Go documentation efficiently, designed especially for use with LLMs (large language models).
- Enables LLMs to understand Go projects by offering direct access to package documentation without reading entire source files.
- Substantially reduces the number of tokens needed for LLMs to understand and use Go packages.
- Allows retrieval of documentation at varying levels of detail, depending on the needs of the querying agent.
- Useful for:
  - Project understanding: Get an overview of packages and their functions.
  - Package interface understanding: Retrieve interfaces and related types from packages.
  - Implementation guidance: Obtain documentation for specific interfaces or types.
  - API usage: Access documentation for types within a project or dependency.
  - Library exploration: View documentation for external dependencies used in a project.
  - Method discovery: List available methods on types (e.g., from the standard library).
  - Focused learning: Get detailed explanations for configuring or using specific types.
  - Package browsing: List and describe multiple packages within a Go project.
- Exposes a `get_doc` tool for MCP-capable LLMs (such as Claude) with customizable parameters and advanced command flags.
- Open-source under the MIT License.

## Pricing

No pricing plans are mentioned; godoc-mcp is open-source and available under the MIT License.