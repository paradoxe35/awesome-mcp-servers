# opentk-mcp

A Model Context Protocol (MCP) server that provides structured access to Dutch parliamentary data (Tweede Kamer) via the OpenTK project. It enables AI assistants to search, retrieve, and analyze parliamentary documents, debates, activities, and member information through a standardized MCP interface.

**Source:** [GitHub - r-huijts/opentk-mcp](https://github.com/r-huijts/opentk-mcp)

## Features
- **Standardized MCP Server:** Implements the Model Context Protocol for structured communication between AI models and Dutch parliamentary data.
- **Access to Parliamentary Data:** Retrieve documents, debates, activities, and member information from the Tweede Kamer (Dutch House of Representatives).
- **Comprehensive Search:** Supports advanced search queries to filter and analyze parliamentary documents, debates, and activities.
- **Integration for AI Assistants:** Designed as a bridge between large language models (LLMs) and parliamentary datasets, enabling AI-assisted research and analysis.
- **Data Source:** Utilizes Bert Hubert's tkconv service for a developer-friendly API to Dutch parliamentary data, providing more accessibility than official APIs.
- **Robust Error Handling:** Includes thorough error handling mechanisms to ensure reliability in data retrieval and API usage.
- **Modular Design:** The server is modular, making it extensible and maintainable.
- **Thoroughly Tested:** Includes comprehensive tests to ensure reliability and correctness.
- **Open Source:** Licensed under MIT License.

## Example Use Cases
- Comparing party positions on specific policies (e.g., AI, climate policy, healthcare reform)
- Researching debates and voting records
- Finding MPs based on committee memberships or recent initiatives
- Identifying scheduled parliamentary activities and topics

## Installation
- **Via NPM (for Claude Desktop integration):** Update configuration file and install as described in the documentation.
- **From Source:** Clone the repository, install dependencies, build, and start the server.

## Pricing
- **Open Source:** Free to use under the MIT License.

## Category
- data-access-integration-mcp-servers

## Tags
mcp, government, data-access, search, parliament
