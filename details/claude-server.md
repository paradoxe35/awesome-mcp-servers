# Claude Server

**Category:** AI Integration MCP Servers  
**Tags:** mcp, ai-integration, context-management, open-source

## Description
Claude Server is an open-source Model Context Protocol (MCP) server designed to enhance Claude's context management capabilities. It provides persistent knowledge organization, hierarchical project contexts, and conversation thread storage across sessions. All context data is efficiently organized in a structured `~/.claude` directory, supporting organized, project-specific context and conversation continuity.

## Features
- **Project Context Management:** Allows for hierarchical organization of knowledge and context by project.
- **Conversation Continuity:** Maintains ongoing conversation threads across user sessions.
- **Efficient Storage:** Stores all session and project context data in a structured directory (`~/.claude`).
- **Context Retrieval:** Enables easy retrieval of stored context for different projects or conversations.
- **Automatic Configuration:** Integrates with the Claude desktop app's MCP settings for seamless setup.
- **Configurable:** Settings managed via `claude_desktop_config.json` in the user's Application Support directory.

## Installation
- Automatically configured through the Claude desktop application's MCP settings.
- All context and data stored under `~/.claude/`.

## Development Status
- **Early development (v0.1.0):** Not ready for production use.
- **Active development:** Significant rewrite ongoing, with future enhancements planned.

## License
MIT

## Source
[GitHub Repository](https://github.com/davidteren/claude-server)

## Pricing
- Open source (MIT License) — Free to use.