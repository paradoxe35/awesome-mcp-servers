# Fused MCP

[GitHub Repository](https://github.com/fusedio/fused-mcp)

## Description
Fused MCP is a Python-based framework designed to connect Large Language Models (LLMs), such as Claude, to executable Python code via MCP (Model Code Proxy) User Defined Functions (UDFs). It allows data scientists to extend and enhance models by enabling LLMs to make HTTP requests and interact with APIs and executable Python functions. The framework facilitates building and running extensible MCP servers on local machines, enabling seamless integration between LLMs and custom code.

## Features
- **MCP Server Setup**: Provides step-by-step notebook workflows to set up MCP servers, particularly for integration with Claude's Desktop App, all in Python.
- **Fused User Defined Functions (UDFs)**: Allows running custom Python functions from anywhere, and enables users to add their own UDFs for local experimentation.
- **Local Execution**: All code runs locally; no Fused account is required. Works independently of cloud infrastructure.
- **Claude Integration**: Supports integration with Claude LLM via the Desktop App or through a local client (for environments where the Desktop App is unavailable, such as Linux).
- **Example Notebooks**: Includes example notebooks to guide users from basic setup to creating custom agents and functions.
- **Custom Client Support**: Provides a simple local client for Linux users to interact with the MCP server and Claude using an Anthropic API key.
- **Open Contribution**: Users can contribute their own UDFs to the repository for community use.

## Installation and Requirements
- Clone the repository and install dependencies (uses `uv` for package management).
- Works on macOS, Linux, and Windows.
- For Linux users, a local client is provided as an alternative to the Claude Desktop App.

## Pricing
No pricing information is provided; the repository appears to be open-source and free to use.

## Tags
`code-execution`, `python`, `llm-integration`, `mcp`

## Category
code-execution-automation-mcp-servers