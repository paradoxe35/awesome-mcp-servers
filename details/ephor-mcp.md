# Ephor MCP

**Category:** AI Integration MCP Servers  
**Tags:** ai-integration, collaboration, llm, mcp  
**Source:** [GitHub - kstrikis/ephor-mcp](https://github.com/kstrikis/ephor-mcp)

## Description
Ephor MCP is a Model Context Protocol (MCP) server that facilitates collaborative problem-solving and multi-perspective analysis by allowing multiple LLMs (Language Model Models) to share and analyze each other's responses to the same prompt.

## Features
- **MCP Server Implementation:** Enables multiple AI agents to share and read each other's responses to the same prompt.
- **Two Main MCP Tool Calls:**
  - `submit-response`: Allows an LLM to submit its response to a prompt.
  - `get-responses`: Retrieves all LLM responses to a prompt, with optional filtering.
- **MCP Inspector Support:** Includes integration with MCP Inspector for testing and debugging, offering a web interface for interacting with the server.
- **REST API:** The server exposes endpoints for submitting and retrieving responses.
- **Docker Support:** Includes Docker configuration and deployment scripts for easy setup on EC2 or other server environments.
- **Manual and Scripted Deployment:** Instructions and scripts for both manual and automated deployment.
- **Open Source:** Licensed under MIT.

## Pricing
Ephor MCP is open-source software and is available for use under the MIT license.
