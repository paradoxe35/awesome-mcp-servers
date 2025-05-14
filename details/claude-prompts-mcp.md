# Claude Prompts MCP

**Source:** [GitHub - minipuft/claude-prompts-mcp](https://github.com/minipuft/claude-prompts-mcp)

**Category:** AI Integration MCP Servers

**Tags:** mcp, ai-integration, prompt-management, typescript, open-source

---

## Description
Claude Prompts MCP is an open-source Node.js server implementing the Model Context Protocol (MCP) for Claude AI models. It enables users to create, manage, and use custom prompt templates with a modular, category-based system, supporting complex workflows and prompt chaining for advanced reasoning tasks.

---

## Features
- **Easy Claude MCP Integration:** Seamlessly connects with Claude models using the MCP protocol.
- **Custom Prompt Templates:** Define prompts using Markdown files, including argument validation and metadata.
- **Prompt Arguments:** Supports dynamic arguments with type validation for prompts.
- **Organized by Category:** Prompts are organized in categories for better management and clarity.
- **Multiple Transport Options:** Supports Server-Sent Events (SSE) and STDIO for flexible integration.
- **Context Placeholders:** Use special placeholders (e.g., `{{previous_message}}`) to reference conversation history in prompts.
- **Prompt Chains:** Define sequential chains of prompts to break down complex tasks into multiple steps, with variable mapping between steps.
- **Distributed Configuration:** Prompts and categories are configured through JSON files for modular management.
- **Built-in Commands:** Includes commands like `listprompts`, `process_slash_command`, and supports both double-colon (`>>`) and slash (`/`) command formats.
- **Prompt Management Tools:** API endpoints for creating, updating, deleting, and modifying prompts and categories.
- **Server Management Tools:** Endpoints to reload prompts, restart the server, and manage configuration dynamically.
- **Category Management:** Create and manage prompt categories via API.
- **Chain Debugging:** Tools and logs to help debug and test prompt chains.
- **API Support:** RESTful endpoints for prompt and category management.
- **Extensible:** Supports adding new categories, custom prompts, and extending with future tooling (e.g., planned web UI for management).
- **Logging:** Server logs status and errors to a log file for troubleshooting and auditing.
- **Open Source:** Licensed under MIT.

---

## Usage
- **Running the Server:**
  - Requires Node.js v16+ and npm/yarn.
  - Clone the repository, install dependencies, build, and start the server.
- **Integrating with Claude Desktop:**
  - Add the MCP server configuration to your Claude Desktop config file, specifying the command, arguments, working directory, and environment variables.
- **Executing Prompts:**
  - Use commands like `>>prompt_name argument1=value1` or `/prompt_name argument1=value1` in Claude Desktop.
  - Chain prompts can be executed with `>>chain_command_name argument1=value1`.
- **Managing Prompts and Categories:**
  - Use provided API endpoints or built-in commands to manage prompts and categories.

---

## Pricing
- **Open Source:** Free to use under the MIT License.

---

## Documentation
- Detailed guides are available in the `docs` folder of the repository, covering installation, prompt format, chain execution, management, architecture, and API reference.

---

## License
MIT License.
