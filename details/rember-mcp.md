# rember-mcp

A Model Context Protocol (MCP) server for Rember, enabling AI-assisted creation of spaced repetition flashcards.

- **Source:** [GitHub - rember/rember-mcp](https://github.com/rember/rember-mcp)
- **Category:** Documentation & Learning Resources
- **Tags:** spaced-repetition, learning, flashcards, mcp, open-source
- **License:** MIT

## Features
- **MCP Server for Rember:** Implements the Model Context Protocol (MCP) to integrate with Rember, a tool for spaced repetition learning.
- **AI-Assisted Flashcard Creation:** Allows AI (such as Claude Desktop) to generate flashcards from chats or PDFs. For example:
  - Create flashcards from chat messages by asking "help me remember this" or "create a few flashcards"
  - Create flashcards from PDFs, e.g., "create flashcards from chapter 2 of this PDF"
- **Command-line Setup:** Can be run via `npx -y @getrember/mcp --api-key=YOUR_REMBER_API_KEY`.
- **Integration with Claude Desktop:** Easily integrate as an MCP server in Claude Desktop by configuring `claude_desktop_config.json`.
- **Available Tools:**
  - `create_flashcards`: Takes a list of notes from Claude and uses the Rember API to generate flashcards for each note.
- **Testing & Debugging:**
  - Logging to stderr for debugging
  - Suite of unit tests simulating Claude Desktop API usage
- **Best Practices & Guidance:**
  - Detailed tool descriptions and example usage provided for AI integration
  - Instructions for handling user limits and subscription prompts
  - Guidelines for error handling and retries

## Limitations / Missing Features
- No telemetry or observability currently implemented
- Incomplete error handling
- Needs more automated tests and further iterations on tool descriptions

## Pricing
- **Open Source:** The MCP server is open source under the MIT license. (No pricing or subscription details for the software itself are mentioned; the mention of "Rember Pro subscription" relates to the Rember service, not this MCP server.)
