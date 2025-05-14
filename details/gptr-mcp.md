# Gptr Mcp

MCP server for enabling LLM and AI applications to perform deep, autonomous web research via the Model Context Protocol (MCP). It autonomously explores and validates information from trusted sources, delivering higher quality and more relevant research results than standard search tools.

**Source:** [GitHub - assafelovic/gptr-mcp](https://github.com/assafelovic/gptr-mcp)

## Features
- **Deep Research**: Performs thorough web research, autonomously exploring and validating numerous sources to ensure only relevant, trusted, and up-to-date information is returned.
- **Quick Search**: Offers a fast web search mode optimized for speed; integrates with web retrievers like Tavily, Bing, Google, etc.
- **Research Resource Tool**: Retrieves web resources directly related to a given research task.
- **Write Report**: Generates comprehensive reports based on research findings.
- **Get Research Sources**: Returns the sources used in the research for transparency and verification.
- **Get Research Context**: Provides the full context of the conducted research, optimized for LLM consumption.
- **Optimized Context Usage**: Carefully selects and summarizes information to maximize the value within LLM context windows.
- **Better Reasoning Support**: Supplies higher quality and more structured data to enhance downstream LLM reasoning and output.
- **Claude Desktop Integration**: Can be integrated with Claude Desktop on Mac for seamless research support.
- **Configurable**: Supports environment configuration and integration with various API keys and services (OpenAI, Tavily, etc.).
- **API & CLI Operation**: Can be run directly via Python or through the MCP CLI.
- **MIT Licensed**: Open source and available under the MIT license.

## Installation
- Requires Python 3.10+
- Needs API keys for OpenAI, Tavily, and any other supported services
- Install via pip and configure using `.env` file
- Can be run with `python server.py` or via MCP CLI

## Example Use Case
- LLMs (like Claude) use Gptr Mcp to research a topic (e.g., company analysis), gather and filter relevant, up-to-date information, and present a structured report with citations.

## Pricing
- **Free and Open Source** (MIT License)

## Category
- web-search-mcp-servers

## Tags
web-search, autonomous, ai-integration, mcp, deep-research