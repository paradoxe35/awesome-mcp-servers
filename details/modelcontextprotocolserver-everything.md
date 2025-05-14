# modelcontextprotocol/server-everything

A comprehensive MCP server that exercises all features of the Model Context Protocol, serving as a robust reference implementation. It is designed primarily as a test server for builders of MCP clients, showcasing a wide range of protocol capabilities.

## Features

### Tools
- **echo**: Echoes back input messages.
  - Input: `message` (string)
  - Returns: Text content with echoed message.

- **add**: Adds two numbers together.
  - Inputs: `a` (number), `b` (number)
  - Returns: Text result of the addition.

- **longRunningOperation**: Demonstrates progress notifications for long operations.
  - Inputs: `duration` (number, default: 10), `steps` (number, default: 5)
  - Returns: Completion message with duration and steps, sends progress notifications during execution.

- **sampleLLM**: Demonstrates LLM sampling capability using MCP sampling feature.
  - Inputs: `prompt` (string), `maxTokens` (number, default: 100)
  - Returns: Generated LLM response.

- **getTinyImage**: Returns a small test image.
  - No inputs required.
  - Returns: Base64 encoded PNG image data.

- **printEnv**: Prints all environment variables for debugging.
  - No inputs required.
  - Returns: JSON string of all environment variables.

- **annotatedMessage**: Demonstrates annotated messages with metadata.
  - Inputs: `messageType` ("error" | "success" | "debug"), `includeImage` (boolean, default: false)
  - Returns: Content with varying annotations and optional image.

### Resources
- Provides 100 test resources:
  - Even numbered: Plaintext format, URI: `test://static/resource/{even_number}`
  - Odd numbered: Binary blob format, URI: `test://static/resource/{odd_number}`
- Supports pagination (10 items per page)
- Allows subscribing to resource updates
- Demonstrates resource templates
- Auto-updates subscribed resources every 5 seconds

### Prompts
- **simple_prompt**: Basic prompt, single message exchange.
- **complex_prompt**: Advanced prompt with required (`temperature`) and optional (`style`) arguments, supports multi-turn conversation with images.

### Logging
- Sends random-leveled log messages every 15 seconds, e.g., info, warning, error levels.

### Other
- Intended for testing, not for production use
- Can be integrated with Claude Desktop via configuration

## Category
- Testing & Debugging Tools

## Tags
- mcp, reference-implementation, testing, examples

## Source
[https://github.com/modelcontextprotocol/servers/tree/main/src/everything](https://github.com/modelcontextprotocol/servers/tree/main/src/everything)

## Pricing
No pricing information provided; appears to be open-source.