# mcp-flowcore-platform

**Category:** data-access-integration-mcp-servers  
**Source:** [GitHub Repository](https://github.com/flowcore-io/mcp-flowcore-platform)

## Description
The Flowcore Platform MCP Server is a Model Context Protocol (MCP) server that enables management and interaction with the Flowcore Platform. It provides a standardized API for AI assistants and other applications to query, manage, and interact with Flowcore resources. The platform supports data ingestion, analysis, and cross-referencing, with the ability to use natural language for managing data across public and private data cores.

## Features
- Provides a standardized MCP server interface for Flowcore Platform.
- Enables querying and management of Flowcore resources via structured API.
- Supports data ingestion, analysis, and cross-referencing.
- Utilizes human/natural language to manage data across public and private data cores.
- Can be run directly with `npx` or installed globally via npm.
- Compatible with Bun (JavaScript runtime) for development and building.
- Requires Flowcore username and Personal Access Token (PAT) for authentication.
- Offers both quick setup (via npx) and more permanent installation options (npm global install).
- Open source, written in TypeScript and JavaScript.

## Installation & Usage
- Run directly: `npx @flowcore/platform-mcp-server --username <username> --pat <pat>`
- Install globally: `npm install -g @flowcore/platform-mcp-server` and then `platform-mcp-server --username <username> --pat <pat>`
- For development: use Bun to install dependencies and run the source code.

## Environment Variables
- `USERNAME` (string, required): Flowcore username
- `PAT` (string, required): Flowcore Personal Access Token

## Pricing
No pricing information is provided in the available content.

## Tags
`mcp`, `flowcore`, `data-integration`, `natural-language`, `data-analysis`