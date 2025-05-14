# rust-docs-mcp-server

Provides up-to-date documentation context for a specific Rust crate to LLMs via an MCP tool, using semantic search and LLM summarization.

- **Source:** [GitHub Repository](https://github.com/Govcraft/rust-docs-mcp-server)
- **Category:** Documentation & Learning Resources
- **Tags:** mcp, documentation, rust, semantic-search

## Features
- Fetches and provides the latest documentation for a specified Rust crate.
- Uses semantic search and LLM summarization to answer questions about a crate's API or usage.
- Prevents outdated code suggestions from AI assistants by ensuring context is from current docs.
- Generates and caches embeddings of crate documentation for fast repeated queries.
- Allows running multiple server instances concurrently for different crates and features.
- Communicates using the Model Context Protocol (MCP) over stdio.
- Tool provided: `query_rust_docs` for querying crate documentation context.
- Supports specifying crate versions and features, matching Cargo's package ID specification.
- Caching mechanism reduces startup time for subsequent runs with the same crate/version/features.
- Informational logging of server status and query processing for integration with MCP clients.
- Example client configurations available for tools like Roo Code and Claude Desktop.
- Open-source under the MIT License.

## Installation
- Download pre-compiled binaries for your operating system from GitHub Releases.
- Alternatively, build from source with the Rust toolchain.

## Usage
- On first run for a crate/version/features, downloads docs and generates embeddings (requires internet and OpenAI API key).
- Recommended to run once manually for new crates to complete initial embedding and caching.
- Subsequent launches use cached data for faster startup.
- Requires specifying target crate and version/features via command line.

## Pricing
- No pricing information provided; project is open-source under the MIT License.