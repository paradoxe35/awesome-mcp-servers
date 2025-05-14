# user-feedback-mcp

**Description:**  
user-feedback-mcp is a simple MCP (Model Context Protocol) Server designed to enable human-in-the-loop workflows in tools such as Cline and Cursor. It is especially useful for desktop application development that requires complex user interactions and real-time user feedback integration.

**Source:** [https://github.com/mrexodia/user-feedback-mcp](https://github.com/mrexodia/user-feedback-mcp)

**Category:** ai-integration-mcp-servers

**Tags:** mcp, ai-integration, real-time, feedback, workflow

---

## Features
- Implements an MCP server to facilitate human-in-the-loop workflows.
- Enables real-time user feedback collection and integration into tools like Cline and Cursor.
- Useful for testing and developing desktop applications requiring complex user interactions.
- Provides a configuration system via `.user-feedback.json` to specify commands and execution behavior (`execute_automatically`).
- Supports multi-step commands, allowing more complex workflows.
- Offers a web interface for interacting with MCP tools during development (`http://localhost:5173`).
- Easy installation and integration with Cline:
  - Install dependencies (e.g., `uv` Python package).
  - Clone the repository and configure in Cline MCP Servers.
- Example tool usage: exposes a `user_feedback` tool that can be invoked with project-specific arguments.
- MIT License.
- Written in Python.

---

## Installation
- Install `uv` globally:
  - Windows: `pip install uv`
  - Linux/Mac: `curl -LsSf https://astral.sh/uv/install.sh | sh`
- Clone the repository to your machine.
- Add configuration to Cline's MCP Servers settings as described in the documentation.

---

## Pricing
- **Open Source** (MIT License): Free to use.

---