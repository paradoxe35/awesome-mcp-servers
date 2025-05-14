# bear-mcp-server

An MCP (Model Context Protocol) server that enables integration with Bear Notes on macOS, allowing AI systems and other clients to access and read notes from the Bear note-taking app.

## Features
- **Read Notes:** Retrieve all notes stored in Bear Notes.
- **Search Notes by Text:** Search for notes that contain specific text queries.
- **List All Tags:** List all tags used within Bear Notes.
- **MCP Tools:**
  - `get_notes`: Retrieves all notes.
  - `get_tags`: Lists all tags.
  - `get_notes_like`: Searches for notes containing specific text.
- **Multiple Deployment Options:**
  - Can be run via Node.js or Docker.
- **Integration Ready:**
  - Can be configured as an MCP server for tools like Claude Desktop.

## Requirements
- Node.js
- Bear Notes application (macOS)
- Access to the Bear Notes database (SQLite file)

## Installation
- Clone the repository: `git clone https://github.com/akseyh/bear-mcp-server`
- Install dependencies: `npm install`
- Build the project: `npm run build`
- Deploy via Node.js or Docker (see documentation for configuration details)

## License
MIT License

## Source
[https://github.com/akseyh/bear-mcp-server](https://github.com/akseyh/bear-mcp-server)

## Pricing
This is an open-source project and is available for free under the MIT license.