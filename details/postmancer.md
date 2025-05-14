# postmancer

[GitHub Repository](https://github.com/hijaz/postmancer)

A standalone MCP server for API testing and management, designed to allow AI assistants (such as Claude) to interact with RESTful APIs through natural language. It aims to replace tools like Postman and Insomnia, with a focus on AI/LLM integration.

## Features
- Make HTTP requests to any REST API
- Save and organize requests in collections
- Set and use environment variables with variable substitution
- Multiple authentication methods supported:
  - Basic
  - Bearer
  - API Key
  - OAuth2
- Request/response history and testing
- Tools available for AI assistants:
  - `http_request`: Send HTTP requests to any URL
  - `list_collections`: View all saved API collections
  - `list_requests`: View all requests in a collection
  - `save_request`: Save a request to a collection
  - `request_from_collection`: Execute a saved request
  - `set_environment_variable`: Set variables for request templates
  - `get_environment_variables`: View all environment variables
- Configurable via environment variables:
  - COLLECTIONS_PATH: Path to store collections (default: `~/.postmancer`)
  - LOG_LEVEL: Logging level (debug, info, warn, error; default: info)
  - POSTMANCER_ENCRYPTION_KEY: Secret key for encrypting credentials and tokens
  - ENCRYPTION_KEY: Secret key for encrypting environment variables marked as secrets
- Can be installed globally via npm, run with npx, or used via Docker

## Pricing
- Open source (MIT License)

## Tags
mcp, api, postman, insomnia, llm-integration

## Category
api-integration-mcp-servers