# difyworkflow-mcp-server

An MCP server application that provides tools to query and execute Dify workflows using the MCP protocol, supporting the on-demand operation of multiple custom Dify workflows.

**Source:** [https://github.com/gotoolkits/mcp-difyworkflow-server](https://github.com/gotoolkits/mcp-difyworkflow-server)

## Features
- Implements an MCP server for Dify workflows.
- Allows querying and invocation (execution) of Dify workflows through the MCP protocol.
- Supports multiple custom Dify workflows, which can be managed on-demand.
- Workflow names and API keys can be configured for each workflow (requires Dify platform API keys).
- Provides commands to:
  - List authorized workflows (`list_workflows`).
  - Execute a specified workflow (`execute_workflow`) with arguments for workflow name and input message.
- Configurable via a JSON configuration file (supports specifying base URL, workflow names, and API keys).
- Can be built from source using Go or Makefile.
- Open source under the Apache-2.0 license.

## Usage
- `list_workflows`: List all authorized workflows.
- `execute_workflow`: Execute a specific workflow by name with an input message (the input variable should be named `message` in the Dify workflow definition).
- Sample prompts are provided for both Chinese and English usage.

## Installation
- Clone the repository and build using Go or `make build`.
- Configure via `config.json` for workflow names and API keys.

## Pricing
- Open source software (Apache-2.0 license); free to use.

## Tags
mcp, workflow, dify, automation

## Category
workflow-automation-mcp-servers