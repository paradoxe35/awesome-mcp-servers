# graphlit-server

**Category:** Data Access & Integration / MCP Servers  
**Tags:** mcp, data-integration, search, ai-integration

## Description
The `graphlit-server` is a Model Context Protocol (MCP) Server that integrates MCP clients with the Graphlit service. It enables ingestion and retrieval of diverse data sources, providing a robust solution for data integration and search within MCP-compatible environments.

## Features
- **Data Ingestion:** Supports ingestion from a wide range of sources, including Slack, Discord, websites, Google Drive, email, Jira, Linear, and GitHub into a Graphlit project.
- **Document Extraction:** Converts documents (PDF, DOCX, PPTX, etc.) and HTML web pages into Markdown format upon ingestion.
- **Audio/Video Transcription:** Automatically transcribes audio and video files during ingestion.
- **Web Crawling & Search:** Built-in web crawling and web search tools are available as MCP tools, eliminating the need for separate integrations (e.g., Firecrawl, Exa).
- **Search & Retrieval:** Enables searching and retrieving relevant knowledge within various MCP clients such as Cursor, Windsurf, and Cline.
- **Data Connectors:** Optional configuration for additional data connectors (e.g., Slack, Google Email, Notion).
- **Flexible Installation:** Can be installed in various IDE applications (Windsurf, Cline, Cursor, Smithery) using NPX or manual setup.
- **Environment Configuration:** Supports environment variables for authentication and connector configuration.
- **Operations & Notifications:** Includes tools for data operations and notification handling.

## Installation
- Installable via NPX in supported IDEs (Windsurf, Cline, Cursor, Smithery) or manually in any MCP client application.
- Requires configuration of environment variables: `GRAPHLIT_ORGANIZATION_ID`, `GRAPHLIT_ENVIRONMENT_ID`, and `GRAPHLIT_JWT_SECRET` (additional connector credentials optional).

## Pricing
_No pricing information provided._

## Source
[graphlit-server on MCP Now](https://mcpnow.org/servers/graphlit-graphlit-mcp-server)
