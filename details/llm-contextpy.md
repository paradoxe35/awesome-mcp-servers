# llm-context.py

**Description:**  
llm-context.py is an open-source MCP server and CLI tool that enables developers to share code context with Large Language Models (LLMs). It supports both Model Context Protocol (MCP) integration and clipboard-based workflows, making it easy to switch between different tasks such as code review and documentation. The tool provides smart code outlining and rule-based customization for flexible context sharing.

**Source:** [GitHub - cyberchitta/llm-context.py](https://github.com/cyberchitta/llm-context.py)

**Category:** Development Tools / MCP Servers

**Tags:** llm, context-management, ai-integration, open-source

---

## Features

- **Direct LLM Integration:** Native integration with Claude Desktop via the MCP protocol.
- **Clipboard Workflow:** Works with any LLM chat interface using the command line and clipboard operations.
- **Smart File Selection:** Utilizes .gitignore patterns to select relevant files for context sharing.
- **Rule-Based Customization:** Supports multiple rule-based profiles, allowing easy switching between tasks (e.g., code review, documentation). System and user-defined rules are available.
- **Project Type Support:** Suitable for code repositories and collections of text/markdown/html documents.
- **Project Size Optimization:** Optimized for projects that fit within an LLM's context window. (Large project support is under development.)
- **Smart Code Outlines:** Automatically generates code outlines highlighting important definitions, aiding LLMs in understanding code structure.
- **Definition Implementation Extraction:** Allows pasting full implementations of specific definitions requested by LLMs.
- **Customizable Templates & Prompts:** Users can customize how project content is captured and presented.
- **Core CLI Commands:**
  - `lc-init`: Initialize project configuration
  - `lc-set-rule <n>`: Switch rules
  - `lc-sel-files`: Select files for inclusion
  - `lc-sel-outlines`: Select files for outline generation
  - `lc-context`: Generate and copy context (with options for prompts and user notes)
  - `lc-prompt`: Generate project instructions for LLMs
  - `lc-clip-files`: Process LLM file requests
  - `lc-changed`: List files modified since last context generation
  - `lc-outlines`: Generate outlines for code files
  - `lc-clip-implementations`: Extract code implementations requested by LLMs (not for C/C++)
- **Persistent Context Support:** Works well with interfaces that support persistent context (e.g., Claude Projects, Custom GPTs).
- **Open Source:** Licensed under Apache-2.0.

## Pricing

llm-context.py is open source and free to use under the Apache-2.0 license.