# mcp-simple-pubmed

**Category:** Data Access Integration MCP Servers  
**Tags:** mcp, pubmed, research, data-access, llm

## Description
mcp-simple-pubmed is an MCP server that allows searching and accessing medical and life sciences papers from PubMed. It is designed for integration within the MCP ecosystem and works by interfacing with the Entrez API, enabling programmatic queries of the PubMed database.

## Features
- Search the PubMed database using keywords
- Access article abstracts
- Download full text for open access articles directly available on PubMed (returns XML-ized versions of full text)
- Designed for integration with AI assistants (e.g., Claude Desktop)
- Uses Entrez API for reliable access to PubMed data
- Requires configuration via environment variables (PUBMED_EMAIL, optional PUBMED_API_KEY for higher rate limits)
- Supports both manual and Smithery-based installation
- No internal rate limiting (relies on NCBI/API limits)
- Cross-platform configuration examples (Mac OS and Windows)
- Open source under MIT License

## Installation
- Via Smithery: `npx -y @smithery/cli install mcp-simple-pubmed --client claude`
- Via pip: `pip install mcp-simple-pubmed`

## Configuration
- Environment variables required:
  - `PUBMED_EMAIL`: (required by NCBI)
  - `PUBMED_API_KEY`: (optional, for higher rate limits)
- Example integration snippets provided for Claude Desktop (Mac OS and Windows)

## Limitations
- Only open access full texts are available; paywalled articles' full text cannot be accessed
- XML-ized full text may be more suitable for AI parsing than human consumption
- Actual access to some articles may require manual browser navigation if API access is restricted

## License
MIT License

## Source Code
[GitHub Repository](https://github.com/andybrandt/mcp-simple-pubmed)

## Pricing
- Open source, free to use (MIT License)