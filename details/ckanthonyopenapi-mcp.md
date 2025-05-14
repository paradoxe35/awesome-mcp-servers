# ckanthony/openapi-mcp

Dockerized MCP server that enables AI agents to access any API with OpenAPI documentation through the MCP protocol.

- **Source:** [ckanthony/openapi-mcp on GitHub](https://github.com/ckanthony/openapi-mcp)
- **Category:** api-integration-mcp-servers
- **Tags:** mcp, openapi, api-integration, docker, ai-agent

---

## Features

- **Dockerized MCP Server:** Easily deployable using Docker, with a pre-built image available on Docker Hub or buildable locally.
- **OpenAPI/Swagger Integration:** Reads OpenAPI (swagger.json or openapi.yaml) files and generates a Model Context Protocol (MCP) toolset for API interaction.
- **AI Agent Compatibility:** Allows MCP-compatible clients (such as Cursor) to access any API described by OpenAPI, enabling AI agents to interact with APIs without extra coding.
- **Automatic Tool Definition Generation:** Generates MCP tool definitions directly from OpenAPI specification files.
- **API Key Configuration:** Supports passing API keys via command line flags, environment variables, or .env files.
- **Flexible API Key Handling:** Configure API key parameter name and location (header, query, path, or cookie).
- **Selective Exposure:** Include or exclude tags and operation IDs from the OpenAPI specification to control which endpoints are exposed.
- **Base URL Override:** Manually override the API server base URL if needed.
- **Custom Naming/Description:** Set default name and description for the generated MCP toolset.
- **Example Provided:** Includes a Weatherbit API example, with Docker Compose setup for demonstration.
- **Command-Line Options:** Multiple flags for fine-grained control over server behavior and toolset generation.

## Installation

- **Docker (Recommended):**
  - Use the pre-built Docker image from Docker Hub or build locally.
  - Run the container with required OpenAPI spec and API key configuration.
- **Docker Compose:**
  - Example setup provided in the repository for running with docker-compose.

## Usage

- Provide the OpenAPI specification (local file or remote URL).
- Configure API keys as needed (via environment or .env file).
- Run the server and connect MCP-compatible clients to the exposed APIs.
- Use command-line flags to customize behavior (see features above).

## Pricing

- **Open Source:** No pricing information is provided; the project is available for free on GitHub.
