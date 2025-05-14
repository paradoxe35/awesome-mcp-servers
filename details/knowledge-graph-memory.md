# Knowledge Graph Memory

**Category:** AI Integration MCP Servers  
**Tags:** knowledge-graph, memory, context-management, ai-assistant

[Source & More Info](https://forum.cursor.com/t/mcp-add-persistent-memory-in-cursor/57497)

## Description
Knowledge Graph Memory is an MCP extension that provides AI agents (specifically for Cursor) with persistent contextual memory. It creates a knowledge graph from project or documentation data, allowing more accurate context-aware responses and documentation retrieval. The system is a fork of Anthropic’s original memory server, with added improvements like version tracking and a customizable memory storage path.

## Features
- **Persistent Memory:** Remembers information about you and your projects across chats and sessions in Cursor.
- **Knowledge Graph Storage:** Utilizes a local knowledge graph structure to store and retrieve contextual information.
- **Customizable Memory Path:** Memory files can be stored at configurable locations, set via configuration files, environment variables, or command-line arguments.
- **Separate Project Memories:** Supports different memory files per project for isolated context.
- **Version Tracking:** Maintains a history of how project knowledge evolves over time.
- **Automatic Persistence:** All knowledge graph operations are automatically saved to a JSONL file (default: `memory.jsonl`).
- **Beginner-Friendly Setup:** Provides step-by-step instructions for configuration, including handling hidden files and directory setup.
- **Memory Interaction:**
  - Retrieve info by asking prompts like "What do you remember about..."
  - Store info by saying "Please remember that..."
  - Memory is used automatically in task-related conversations.
- **Troubleshooting Support:** Guides for debugging and verifying persistent memory functionality.
- **Open Source & NPM Package:** Available as `@itseasy21/mcp-knowledge-graph` on npm.

## Pricing
No pricing information is provided. The extension appears to be open source and freely available via npm.

## Source & Documentation
- [Forum Post & Setup Guide](https://forum.cursor.com/t/mcp-add-persistent-memory-in-cursor/57497)
- [npm Package: @itseasy21/mcp-knowledge-graph](https://www.npmjs.com/package/@itseasy21/mcp-knowledge-graph)