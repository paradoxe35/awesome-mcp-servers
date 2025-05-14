# mcp-simple-arxiv

[Source Code](https://github.com/andybrandt/mcp-simple-arxiv)

## Description
mcp-simple-arxiv is an MCP server that allows language models (LLMs) and AI tools to search and read academic papers from arXiv, following the MCP server pattern. It provides an API interface to access arXiv papers and is compatible with clients like Claude Desktop.

## Features
- Allows LLM clients (such as Claude Desktop) to search for papers on arXiv using custom queries.
- Returns basic information about matching papers (after a search), including titles and identifiers.
- Enables retrieval of detailed information about specific papers once a paper ID is known.
- Implements proper rate limiting in accordance with arXiv's API guidelines (maximum 1 request every 3 seconds).
- Can be installed automatically via Smithery or manually.
- Follows arXiv API usage guidelines.

## Category
- Data Access Integration MCP Servers

## Tags
mcp, arxiv, research, data-access, llm

## License
MIT

## Pricing
No pricing information provided; the project is open source (MIT licensed).