# Rootly MCP Server

[Source Code](https://github.com/Rootly-AI-Labs/Rootly-MCP-server)

## Overview
Rootly MCP Server is an open-source MCP (Model Control Protocol) server that integrates with the Rootly incident management platform. It enables integration with AI agents and MCP-compatible editors (such as Cursor, Windsurf, and Claude) to facilitate incident response workflows directly from the IDE.

## Features
- **Dynamically generated MCP tools:** Utilizes Rootly's OpenAPI (Swagger) specification to generate available MCP resources automatically.
- **Editor integration:** Can be used with MCP-compatible editors, allowing incident management and response actions without leaving the IDE.
- **Default pagination:** Applies a default pagination (10 items) for incident endpoints to avoid context window overflow.
- **API path limiting:** Restricts the number of API paths exposed to AI agents for both context size management and security reasons.
  - By default, only `/incidents` and `/incidents/{incident_id}/alerts` endpoints are available.
  - The `allowed_paths` variable can be customized to expose more API endpoints if needed.
- **Customizable setup:** Can be installed via PyPI or by cloning the repository; supports configuration for different editors and environments.
- **Open source:** Licensed under Apache-2.0.

## Prerequisites
- Python 3.12 or higher
- `uv` package manager
- Rootly API token

## Installation & Setup
- Install via [PyPI](https://pypi.org/project/rootly-mcp-server/) or clone the repository.
- Configure in your IDE or editor using the provided configuration samples.
- To customize available API paths, modify the `allowed_paths` variable in `src/rootly_mcp_server/server.py`.

## Disclaimer
This project is a prototype and not intended for production use.

## Pricing
Rootly MCP Server is open-source and free to use under the Apache-2.0 license.

## Tags
incident-management, workflow, automation, mcp, open-source