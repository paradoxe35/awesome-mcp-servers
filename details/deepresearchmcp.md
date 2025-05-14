# deepresearchmcp

**Category:** Data Access & Integration MCP Servers  
**Source:** [GitHub Repository](https://github.com/ameeralns/deepresearchmcp)

## Overview
DeepResearch MCP is an open-source, research-focused Model Context Protocol (MCP) server. It automates intelligent, iterative research processes, performing web searches, analysis, and generating comprehensive, citation-rich reports on any topic.

## Features
- **Intelligent, Multi-step Research:** Conducts iterative research workflows using web searches and analytical steps.
- **Comprehensive Report Generation:** Produces detailed research reports with citations.
- **MCP Protocol Support:** Offers an MCP server interface for integration with MCP clients.
- **API Resources:**
  - `research://state/{sessionId}`: Access the current state of a research session.
  - `research://findings/{sessionId}`: Retrieve findings for a session.
- **MCP Tools:**
  - `initialize-research`: Start a new research session (parameters: query, depth).
  - `execute-research-step`: Execute the next step in the research process (parameter: sessionId).
  - `generate-report`: Generate a final report for a session (parameters: sessionId, timeout optional).
  - `complete-research`: Run the full research process end-to-end (parameters: query, depth, timeout optional).
- **Integration with Claude Desktop:** Can be configured to provide research capabilities directly within Claude Desktop via a sample configuration file.
- **Configurable Parameters:** Customizable research depth, topic, and timeout.
- **Open Source & Extensible:** Full source code available for modification and extension.
- **Sample Client Code:** Examples provided for running research tasks from a client.

## Installation & Usage
- Clone the repository and install dependencies.
- Configure environment variables (API keys required).
- Build and run the MCP server for client connections.
- Example usage and client code provided in the repository documentation.

## Troubleshooting
- Handles issues like API token limits, timeout errors, and API rate limits with suggested solutions.

## License
ISC License

## Pricing
- Free and open source (no pricing plans).

---
**Tags:** mcp, research, web-search, automation