# Codebase Context Dumper

- **Category:** Repository Code Analysis / MCP Servers
- **Tags:** mcp, codebase, context-management, llm-integration
- **Source:** [GitHub Repository](https://github.com/lex-tools/codebase-context-dumper)

## Description
Codebase Context Dumper is a Model Context Protocol (MCP) server that automates the process of extracting and formatting codebase context for use with Large Language Models (LLMs). It streamlines the process of providing relevant project information to AI models by recursively reading and organizing codebase files.

## Features
- **MCP Server Implementation:** Acts as an MCP server, enabling integration with MCP clients such as Claude Desktop and VS Code extensions.
- **Automated Codebase Dumping:** Recursively reads all text files from a specified directory, skipping binary files and respecting `.gitignore` rules.
- **File Path Annotation:** Concatenates file contents with clear file path headers and footers to maintain context.
- **Chunked Output Support:** For large codebases, supports splitting output into manageable chunks.
- **Easy Usage via npx:** Can be run easily using npx without a local installation.
- **Local Installation Option:** Advanced users can install and run the server locally for development or customization.
- **Open Source:** Licensed under Apache License 2.0.

## Pricing
- The tool is open source and free to use under the Apache License 2.0.

## Usage
- Integrate with compatible MCP clients by configuring them to use the codebase-context-dumper server.
- Supports both quick usage via npx and advanced local installations.

---
For more details, visit the [official GitHub repository](https://github.com/lex-tools/codebase-context-dumper).