# llm-context

[Source Code](https://github.com/cyberchitta/llm-context.py)

## Description
LLM Context is a tool designed to help developers quickly inject relevant content from code or text projects into Large Language Model (LLM) chat interfaces. It supports sharing code context via the Model Context Protocol (MCP) or through the clipboard, enhancing code understanding and collaboration with LLMs.

## Features
- **Model Context Protocol & Clipboard Support**: Share code context with LLMs either via the MCP protocol or by copying to the clipboard.
- **Rule-Based Customization**: Easily switch between different tasks (such as code review and documentation) using customizable, markdown-based rules.
- **Smart File Selection**: Utilizes .gitignore patterns for intelligent file selection within your projects.
- **Multiple Usage Patterns**:
  - Native integration with Claude Desktop via MCP protocol
  - Works with any LLM chat interface using CLI/clipboard
  - Optimized for interfaces with persistent context (e.g., Claude Projects, Custom GPTs), but also works with standard chat interfaces
- **Project Type Flexibility**: Suitable for code repositories and collections of text/markdown/html documents.
- **Smart Code Outlining**: Automatically generates outlines highlighting the high-level structure and important definitions in your codebase.
- **Definition Implementation Extraction**: Extracts and provides full implementations of specific definitions requested by LLMs.
- **Customizable Templates and Prompts**: Users can define how context and instructions are presented to LLMs.
- **System and User Rules**: Offers system rules for default functionality and allows user-defined rules for custom workflows.
- **CLI Commands for Workflow Management**:
  - `lc-init`: Initialize project configuration
  - `lc-set-rule <n>`: Switch between rules
  - `lc-sel-files`: Select files for inclusion
  - `lc-sel-outlines`: Select files for outline generation
  - `lc-context`: Generate and copy context (with options for prompts and user notes)
  - `lc-prompt`: Generate project instructions
  - `lc-clip-files`: Process LLM file requests
  - `lc-changed`: List files modified since last context generation
  - `lc-outlines`: Generate code outlines
  - `lc-clip-implementations`: Extract code implementations (not supporting C/C++)
- **Optimized for Projects within LLM Context Window**: Best suited for projects that fit within the context window of an LLM; support for larger projects is in development.
- **Open Source**: Licensed under the Apache-2.0 license.

## Pricing
No pricing information is provided. The tool is open source under the Apache-2.0 license.

## Tags
mcp, context-management, codebase, ai-integration

## Category
Development Tools – MCP Servers
