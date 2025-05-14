# cal-mcp

A lightweight MCP server for mathematical expression calculation, enabling AI models to perform calculations via MCP.

- **Source:** [GitHub Repository](https://github.com/pwh-pwh/cal-mcp)
- **Category:** Data Analysis & Exploration MCP Servers
- **Tags:** calculation, mathematics, mcp, open-source, ai-integration
- **License:** MIT

## Features
- **Mathematical Expression Calculation:** Parses and computes mathematical expressions input by the user.
- **Built-in Constants:**
  - `E`: Mathematical constant Math.E from the Bun environment
  - `PI`: Mathematical constant Math.PI from the Bun environment
  - `true`: Boolean true
  - `false`: Boolean false
- **Expression Examples:**
  - Basic operations: `2 + 2` → `4`
  - Using constants: `PI * 2` → `6.283185307179586`
  - Complex expressions: `E ^ 2 + 1` → `8.38905609893065`
- **Interaction via stdio:** The service communicates through standard input/output.
- **Lightweight and Efficient:** Designed as a simple tool for calculation, using the Bun runtime for efficiency.
- **Parameter Handling:** Accepts a string mathematical expression as input parameter (`exp`).
- **Dependency on FastMCP and expr-eval:** Utilizes these libraries for MCP service construction and math expression evaluation.
- **Parameter Validation:** Uses `zod` for validating input parameters.
- **Installation Options:**
  - Installable via Smithery CLI for Claude Desktop
  - Manual installation with Bun
- **Open Source:** Source code is available under the MIT license.

## Requirements
- **Bun Runtime:** Requires Bun (latest version recommended).

## Usage
- Start the service with `bun run index.ts`, then send mathematical expressions via stdio to receive results.

## Pricing
- **Open Source:** cal-mcp is free to use under the MIT license. No paid plans are mentioned.
