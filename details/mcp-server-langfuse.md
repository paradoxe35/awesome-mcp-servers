# mcp-server-langfuse

**Description:**
MCP server to access and manage LLM application prompts created with Langfuse Prompt Management. It implements the Model Context Protocol (MCP) to allow prompt discovery, retrieval, and compilation for use in LLM applications.

**Source:** [https://github.com/langfuse/mcp-server-langfuse](https://github.com/langfuse/mcp-server-langfuse)

**Category:** ai-integration-mcp-servers

**Tags:** mcp, langfuse, prompt-management, llm, ai-integration

---

## Features
- **Implements MCP Prompts Specification:**
  - Allows prompt discovery and retrieval via MCP endpoints.
- **List Prompts:**
  - `prompts/list` endpoint to list all available prompts with optional cursor-based pagination.
  - Returns prompt names and required arguments (all arguments assumed optional; argument descriptions not included).
  - Supports pagination with next cursor if there are multiple pages.
- **Get Prompt:**
  - `prompts/get` endpoint to retrieve a specific prompt.
  - Transforms Langfuse prompts (text and chat) into MCP prompt objects.
  - Compiles prompt with provided variables.
- **Tools for Compatibility:**
  - Exports `get-prompts` and `get-prompt` tools to replicate MCP Prompts functionality for clients without prompt capability.
- **Integration Examples:**
  - Can be added as a server in Claude Desktop and Cursor for prompt management.
  - Requires setting up with Langfuse API keys and base URL.
- **Open Source:**
  - Licensed under MIT.
- **Development Support:**
  - Node.js based, supports npm install/build and testing with MCP Inspector.

### Limitations
- Only prompts with a production label in Langfuse are returned.
- All arguments are assumed optional and have no descriptions (due to lack of specification in Langfuse).
- Listing prompts requires fetching each prompt individually in the background, which is not efficient.
- The project is a work in progress.

---

## Pricing
No pricing information is provided; the project is open source under the MIT license.

---

## License
MIT License