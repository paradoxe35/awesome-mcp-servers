# Axiom

Axiom's MCP server is an open-source implementation of the Model Context Protocol (MCP) that allows AI agents to query and analyze large datasets in real-time using the Axiom Processing Language (APL).

**Source:** [GitHub - axiomhq/mcp-server-axiom](https://github.com/axiomhq/mcp-server-axiom)

## Features
- **MCP Server Implementation:** Enables AI agents (such as Claude desktop app) to interact with Axiom datasets via the Model Context Protocol.
- **APL Query Execution:** Supports executing Axiom Processing Language (APL) queries against datasets (`queryApl` tool).
- **Dataset Listing:** Allows listing all available Axiom datasets (`listDatasets` tool).
- **Multiple Configuration Methods:** Can be configured via config file, command-line flags, or environment variables.
- **Rate Limiting:** Supports configuration of query and dataset listing rates (rate and burst settings).
- **Integration Ready:** Designed to be integrated as an MCP server for AI applications.
- **Open Source:** Licensed under the MIT License.
- **Written in Go:** 100% Go implementation.

## Installation
- Download pre-built binaries from the releases page.
- Or install via Go: `go install github.com/axiomhq/axiom-mcp@latest`

## Usage
- Configure with a config file, command-line flags, or environment variables.
- Can be used in conjunction with the Claude desktop app by specifying the MCP server command, arguments, and environment variables in the app's configuration.

## Pricing
- **Open Source:** Free to use under the MIT License.

## Tags
`data-analysis` `real-time` `ai-integration` `open-source`

## Category
Data Analysis & Exploration MCP Servers