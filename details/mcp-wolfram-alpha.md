# mcp-wolfram-alpha

Connect your chat REPL to Wolfram Alpha computational intelligence via an MCP server.

- **Source:** [GitHub Repository](https://github.com/SecretiveShell/MCP-wolfram-alpha)
- **Category:** API Integration MCP Servers
- **Tags:** wolfram-alpha, computation, api-integration, mcp

## Features
- Provides an MCP server for querying the Wolfram Alpha API.
- Enables advanced computational queries from chat-based REPLs through the MCP protocol.
- Includes prompt functionality analogous to the `!wa` bang in DuckDuckGo search.
- Exposes Python methods for querying Wolfram Alpha:
    - `wa(query: str)`: Prompts Wolfram Alpha to answer a question.
    - `query_wolfram_alpha(query: str) -> str`: Directly queries the Wolfram Alpha API.
- Supports environment-based configuration via `WOLFRAM_API_KEY`.
- Example configuration provided for integration with MCP clients and inspectors.
- Tested with the full results API of Wolfram Alpha (full API not strictly required).
- Docker and Python support for deployment and development.
- Open source under the MIT license.

## Configuration
- Requires a Wolfram Alpha API key set as `WOLFRAM_API_KEY` in the environment.
- Supports both Windows and Unix-style directory paths in configuration.
- Example `config.json` files provided for setup and debugging.
- Recommended to use `wong2's mcp-cli-inspector` for debugging, due to limited environment variable support in official MCP inspector.

## Pricing
- Open source, free to use (MIT License).
- Note: Usage of the Wolfram Alpha API may require a separate API key and could incur costs depending on Wolfram Alpha's terms.
