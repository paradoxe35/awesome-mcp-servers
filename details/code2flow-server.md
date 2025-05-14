# Code2flow Server

Code2flow Server is an MCP (Machine Communication Protocol) service that wraps the code2flow tool, allowing AI applications and clients to generate and access code call graphs through a standardized protocol. It exposes a primary tool, `generate_call_graph`, which analyzes source code and produces visual representations of function and class relationships.

## Features

- **Call Graph Generation**: Analyzes source code to create call graphs that visualize relationships between functions, methods, and classes.
- **Supported Languages**: Works with Python (.py), JavaScript (.js), Ruby (.rb), and PHP (.php).
- **Parameter Options**:
  - `source_paths` (required): List of file paths or directories to analyze.
  - `output_path` (optional): Custom location for output PNG file.
  - `language` (optional): Specify source code language.
  - `exclude` (optional): Patterns for files/directories to exclude.
  - `include` (optional): Patterns for files/directories to include.
- **Integration with MCP Server**: Tool is registered and available as an MCP tool, facilitating standardized access and integration.
- **Resource Management**:
  - Registers each generated PNG image as a unique MCP resource.
  - Provides resource retrieval via MCP resource ID.
- **Execution Flow**:
  - Processes and validates parameters.
  - Constructs and runs the code2flow command.
  - Handles resource registration and returns status/results to clients.
- **Error Handling**: Captures and logs all errors, returning appropriate error messages to the client.
- **Usage Examples**: Documentation includes basic and advanced usage samples.

## Category

- Repository Code Analysis MCP Servers

## Tags

mcp, code-analysis, visualization, ai-integration

## Source

[https://deepwiki.com/kursk-ye/code2flow-mcp-server/2.2.1-generate-call-graph-tool](https://deepwiki.com/kursk-ye/code2flow-mcp-server/2.2.1-generate-call-graph-tool)

## Pricing

No pricing information provided.