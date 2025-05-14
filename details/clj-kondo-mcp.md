# Clj Kondo MCP

A Model Context Protocol (MCP) server that provides clj-kondo linting capabilities for Clojure, ClojureScript, and EDN files. Useful in environments without built-in linting.

## Features
- Implements MCP server for integration with editors or tools supporting the protocol
- Provides linting for Clojure, ClojureScript, and EDN files using clj-kondo
- Supports linting via the `lint_clojure` tool call
- Accepts absolute file paths for linting and configuration directory
- Automatically detects `.clj-kondo` config directories, with option to override via `configDir` parameter
- Can be integrated into IDEs or used in desktop environments lacking native linting
- Manual and quick install options
- Can run in watch mode for continuous linting

## Installation
- Requires clj-kondo installed and available in system PATH
- Install dependencies as described in the repository

## Usage
- Run the MCP server to provide linting services
- Configure client tools (like Cline or IDEs) to connect to the MCP server
- Use the `lint_clojure` tool call for linting operations
- Both `file` and `configDir` parameters must use absolute paths

## Source
[https://github.com/Bigsy/clj-kondo-mcp](https://github.com/Bigsy/clj-kondo-mcp)

## Category
Development Tools / MCP Servers

## Tags
mcp, linting, clojure, code-analysis

## Pricing
No pricing information provided; open source project.