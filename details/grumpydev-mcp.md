# Grumpydev Mcp

[GitHub Repository](https://github.com/sinedied/grumpydev-mcp)

## Description
Grumpydev Mcp is an MCP server that reviews code with a sarcastic, cynical tone, emulating the perspective of a grumpy senior developer. It is designed for both experienced developers who want sharp feedback on code quality and for those looking to improve their pull requests (PRs).

## Features
- **Code Review with Sarcasm:** Provides feedback on code and PRs in a grumpy, sarcastic style, highlighting what needs to be fixed or improved.
- **MCP (Model Context Protocol) Server:** Implements the MCP standard, allowing standardized context provision to AI models.
- **Integration Options:**
  - Can be used with VS Code (requires enabling Agent mode or using VS Code Insiders).
  - Compatible with GitHub Copilot and Claude desktop through configuration.
- **Model Customization:**
  - Supports configuration of the underlying AI model via the `GENAISCRIPT_DEFAULT_MODEL` environment variable.
  - Default model is GitHub Models with GPT-4o, but any GenAIScript-supported provider/model can be used (additional configuration such as API keys may be required).
- **Built on GenAIScript:** Leverages the GenAIScript framework for its MCP server capabilities.
- **Node.js Requirement:** Requires Node.js 20+ for operation.

## Pricing
No pricing information is provided; the project appears to be open source.

## Tags
`code-review`, `developer-tools`, `mcp`, `ai-integration`, `feedback`

## Category
Development Tools / MCP Servers