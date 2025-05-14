# Eunomia MCP Server

**Category:** MCP Middleware Orchestration  
**Tags:** data-governance, orchestration, mcp, open-source

## Overview
Eunomia MCP Server is an open-source extension for the Eunomia framework. It connects Eunomia instruments with MCP servers, enabling orchestration of data governance and access policies for LLM-based applications. The server allows integration of data governance policies—such as PII detection and user access control—into external server processes within the MCP ecosystem.

> **Note:** This MCP server is deprecated and not compatible with the latest Eunomia developments. A new MCP integration is under development.

## Features
- Connects Eunomia instruments to MCP servers for orchestration.
- Enables application of data governance policies (e.g., PII detection, user access control) to text streams in MCP-based servers.
- Uses Eunomia's "instrument" concept within an "Orchestra" to define and apply policies.
- Designed for integration with external server processes in the MCP ecosystem.
- Open source and available for community use and modification.

## Installation & Usage
- Define application settings and instruments in an Orchestra.
- Run the MCP Orchestra server by pointing `uv` to the directory containing your server code.
- See documentation for advanced configuration and usage.

## Pricing
- Open source (free to use)

## Source
[https://github.com/whataboutyou-ai/eunomia-mcp-server](https://github.com/whataboutyou-ai/eunomia-mcp-server)