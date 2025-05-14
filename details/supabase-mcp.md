# supabase-mcp

[Source Code](https://github.com/supabase-community/supabase-mcp)

**Category:** database-messaging-mcp-servers  
**Tags:** supabase, database, mcp, ai-integration

## Description
The official Supabase MCP server enables AI assistants to directly manage tables, fetch configuration, and query data within Supabase projects. It implements the Model Context Protocol (MCP), standardizing how large language models (LLMs) interact with external services like Supabase.

## Features
- **AI Assistant Integration:** Connect Supabase projects to AI assistants such as Cursor, Claude, and Windsurf.
- **Project Management:**
  - List all Supabase projects for a user
  - Get details for a project
  - Create, pause, and restore projects
  - List/get organizations
- **Database Operations:**
  - List tables, extensions, and migrations
  - Apply SQL migrations (for schema changes)
  - Execute raw SQL queries
  - Access project logs (API, Postgres, Edge Functions, Auth, Storage, Realtime)
- **Project Configuration:**
  - Get API URL for a project
  - Get anonymous API key for a project
- **Branching (Experimental, requires paid plan):**
  - Create, list, delete, merge, reset, and rebase development branches
- **Development Tools:**
  - Generate TypeScript types from the database schema
- **Authentication:** Uses Supabase personal access tokens for authentication
- **Cross-platform Support:** Setup instructions for Linux, macOS, Windows, and WSL
- **Pre-1.0 Notice:** The server is pre-1.0 and may introduce breaking changes between versions
- **Open Source:** Licensed under Apache 2.0

## Pricing
No pricing information is provided in the available content. (Branching features require a paid Supabase plan.)
