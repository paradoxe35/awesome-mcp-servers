# DeepView MCP

[DeepView MCP](https://mcpservers.org/servers/ai-1st/deepview-mcp) is a Model Context Protocol (MCP) server that enables IDEs like Cursor and Windsurf to analyze large codebases using Gemini's extended (1M) context window.

## Features
- Acts as an MCP server to provide code analysis capabilities to compatible IDEs (e.g., Cursor, Windsurf).
- Supports large codebases by leveraging Gemini's 1 million token context window.
- Optional configuration of codebase file within IDE setup; can set a default codebase.
- Command-line options for server configuration.
- Requires codebases to be prepared as a single file in an AI-friendly format (e.g., using `repomix`).
- Provides a tool for codebase analysis via the MCP protocol.
- Open-source and licensed under the MIT License.

## Installation
- Can be installed via Smithery for Claude Desktop or via pip.
- Server is typically managed automatically by the IDE's MCP setup; manual start is usually not required.

## Usage
- Configure with your codebase file or specify it per query.
- Specify Gemini version to use via configuration.
- Use `repomix` to generate a single-file representation of your codebase for analysis.

## License
MIT

## Author
Dmitry Degtyarev (ddegtyarev@gmail.com)

## Tags
`code-analysis`, `gemini`, `ide`, `mcp`, `open-source`

## Pricing
No pricing information provided; DeepView MCP is open-source and licensed under MIT.