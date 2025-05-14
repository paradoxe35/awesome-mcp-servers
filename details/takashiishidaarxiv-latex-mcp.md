# takashiishida/arxiv-latex-mcp

- **Description**: An MCP server that allows clients (such as Claude Desktop and Cursor) to directly fetch and process the LaTeX source of arXiv papers. It is designed to accurately interpret mathematical expressions and equations by using the original LaTeX source rather than PDFs.
- **Source**: [GitHub Repository](https://github.com/takashiishida/arxiv-latex-mcp)
- **Category**: API Integration / MCP Servers
- **Tags**: mcp, arxiv, latex, research

## Features
- Acts as an MCP server for integrating with compatible clients (e.g., Claude Desktop, Cursor)
- Fetches the LaTeX source of arXiv papers directly
- Utilizes `arxiv-to-prompt` for downloading and processing LaTeX content
- Enables precise interpretation of mathematical content and equations in scientific papers
- Especially useful for fields with heavy mathematical notation (computer science, mathematics, engineering)
- Designed to work as a tool for LLMs to better process scientific papers' content
- Example usage: Query specific theorems or sections from arXiv papers by their identifier

## Pricing
No pricing information is provided; the repository appears to be open source.

## Installation
- Add the server configuration as detailed in the repository's README
- Requires `uv` for running the environment (instructions for locating `uv` on different OSes provided)
- For integration with Claude Desktop, the tool appears as `get_paper_prompt` in the MCP tools list
