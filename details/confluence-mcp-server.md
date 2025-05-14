# Confluence MCP Server

A TypeScript-based MCP server that enables interaction with Confluence data via CQL queries and page content retrieval. It is suitable for integration with multiple platforms, such as Claude Desktop.

## Features
- **CQL Query Execution**: Execute CQL (Confluence Query Language) queries to search for Confluence pages.
  - Parameters: `cql`, `limit` (default: 10)
- **Page Content Retrieval**: Fetch the content of a specific Confluence page.
  - Parameter: `pageId`
- **Cross-Platform Support**: Can be configured for use on both MacOS and Windows systems.
- **Development Tools**:
  - Scripts for installing dependencies, building the server, and auto-rebuilding during development.
- **Debugging Tools**: Includes an MCP Inspector for debugging communication over stdio.

## Installation & Usage
- Install dependencies: `npm install`
- Build the server: `npm run build`
- For development with auto-rebuild: `npm run watch`
- Debugging: `npm run inspector` (provides a browser-accessible inspector)
- Can be integrated with Claude Desktop via configuration in the relevant OS-specific config file.

## Source
[GitHub Repository](https://github.com/KS-GEN-AI/confluence-mcp-server)

## Pricing
No pricing information provided; appears to be an open-source project.