# Figma MCP Server

A TypeScript server implementing the Model Context Protocol (MCP) for the Figma API. It enables standardized, MCP-compliant access to Figma resources, allowing seamless integration of Figma files, components, and variables into applications (including LLMs), and supporting automated design handoffs and single-source-of-truth workflows.

**Source:** [GitHub - TimHolden/figma-mcp-server](https://github.com/TimHolden/figma-mcp-server)

## Features
- **MCP Resource Handlers**
  - Access and manipulation of Figma files
  - Management of Figma variables and components
  - Specialized resource handlers for files, components, and variables
  - Custom URI scheme (figma:///) for resource addressing (files, components, variables, styles, teams, projects)
- **Robust Implementation**
  - Type-safe (TypeScript-based) implementation
  - Request validation using Zod schemas
  - Comprehensive error handling, including mapping Figma API errors to MCP codes
  - Token validation and API integration
  - Batch operations support
- **Transport Support**
  - Supports stdio and SSE (Server Sent Events) transports
  - (Upcoming) WebSocket transport
- **Rate Limiting**
  - Configurable rate limiting (default: 500 requests per 15 minutes)
  - Automatic retry handling for rate-limited requests
  - Rate limit status endpoint and response headers
- **Authentication**
  - Authentication middleware for Figma access tokens
- **Development and Testing**
  - Includes tests for API endpoints
  - Debug logging via environment variables
- **Extensibility** (Planned/Upcoming)
  - Resource change notifications
  - Caching layer
  - Plugin system for custom handlers
  - Enhanced test coverage and performance optimizations

## Usage
- Install via npm: `npm install @modelcontextprotocol/sdk`
- Configure with Figma access token and optional environment variables
- Start the server and connect via MCP clients

## Error Handling
- Maps Figma API errors (403, 404, 429) to MCP error codes (resource not found, access denied, temporarily unavailable)
- Provides clear error messages and data in responses

## License
MIT License

## Pricing
- **Open Source** (no paid plans listed)

## Tags
figma, design, automation, integration

## Category
Data Access & Integration / MCP Servers