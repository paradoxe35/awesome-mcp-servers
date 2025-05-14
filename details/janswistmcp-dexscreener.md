# janswist/mcp-dexscreener

**Source:** [GitHub Repository](https://github.com/janswist/mcp-dexscreener)

## Description
A basic MCP server implementation for accessing real-time on-chain market prices using the Dexscreener API. This project allows AI agents or other clients to query live blockchain market data through Dexscreener's free and open API.

## Features
- Provides a Model Context Protocol (MCP) server for Dexscreener API.
- Enables AI agents to retrieve any on-chain price data via the Dexscreener API.
- Supports both STDIO and SSE (Server-Sent Events) versions:
  - STDIO version for direct input/output communication.
  - SSE version (index-sse.js) that can be hosted on a remote server for real-time event streaming.
- Based on Dexscreener API documentation as of April 4th, 2025.
- Easy integration with Claude Desktop via config file customization.
- Written entirely in JavaScript.

## Project Setup
- Install dependencies using `npm run install`.
- For Claude Desktop integration, edit the `claude_desktop_config.json` to add the Dexscreener MCP server configuration.
- Inspector tool can be used to test the MCP server without Claude Desktop.

## Category
blockchain-crypto-mcp-servers

## Tags
- dexscreener
- market-data
- blockchain
- real-time

## Pricing
No pricing information is provided; appears to be open source and free to use.