# Dice

A simple Model Context Protocol (MCP) server that enables Large Language Models (LLMs) to roll dice using standard dice notation (e.g., `1d20`). This project demonstrates the extensibility and utility of MCP server implementations.

## Features
- Accepts standard dice notation (such as `1d20`) via JSON input.
- Returns both individual dice rolls and their sum.
- Designed for integration with LLMs and tools like Claude Desktop.
- Can be installed and run via command line or as part of a local development environment.
- Includes tests and development tools for debugging (e.g., MCP Inspector).
- Open-source and extensible for further customization.

## Installation
- Can be installed automatically for Claude Desktop using Smithery.
- Requires `uv` for installation (see [uv documentation](https://docs.astral.sh/uv/getting-started/installation/)).

## Usage
- Accepts JSON input with a `notation` field indicating the dice roll (e.g., `{ "notation": "1d20" }`).
- Returns structured results showing each roll and their sum.

## Development
- Includes setup for installing development dependencies and running automated tests.
- Example configurations provided for Claude Desktop and different shell environments.
- Supports debugging with MCP Inspector.

## Source
[https://github.com/yamaton/mcp-dice](https://github.com/yamaton/mcp-dice)

## Category
Reference Implementations / Examples

## Tags
example, mcp, extensible, open-source

## Pricing
- Open-source (no pricing information; free to use under open-source license).
