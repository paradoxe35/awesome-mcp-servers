# Git MCP

[Git MCP](https://github.com/idosal/git-mcp) is a free, open-source server that transforms any GitHub project into a Model Context Protocol (MCP) endpoint, enabling AI assistants to access and understand a project's documentation without any setup.

## Features
- **GitHub Project Documentation Access**: Allows AI assistants to access the documentation of any public GitHub repository via an MCP endpoint.
- **Semantic Search**: Provides semantic search over project documentation to optimize token usage and retrieve relevant information efficiently.
- **Zero Setup Required**: No configuration or modification needed; works out of the box for any public repository.
- **Privacy Focused**: Does not collect or store personally identifiable information or queries. No authentication required.
- **Self-hosting Available**: As open-source software, users can deploy their own instance.
- **Multiple Access Methods**:
  - Direct URL: `gitmcp.io/{owner}/{repo}` for repositories
  - Custom domain: `{owner}.gitmcp.io/{repo}` for GitHub Pages
  - Dynamic endpoint: `gitmcp.io/docs` for flexible repository access
- **Tooling**:
  - `fetch_<repo-name>_documentation`: Fetches documentation from a specified repository (prefers `llms.txt`, falls back to `README.md` or other docs).
  - `search_<repo-name>_documentation`: Performs semantic search within repository documentation.
  - Generic tools (`fetch_generic_documentation`, `search_generic_documentation`) for dynamic endpoint usage.
- **MCP Standard**: Implements the Model Context Protocol for structured, external context retrieval by AI assistants.
- **Compatibility**: Works with any AI assistant that supports MCP (e.g., Cursor, VSCode, Claude, Copilot, etc.).
- **Open Source**: Licensed under the MIT License.
- **Respects robots.txt**: For GitHub Pages, checks robots.txt before accessing content.

## Pricing
- **Free**: Git MCP is available free of charge to the community.

## Source
- [GitHub Repository](https://github.com/idosal/git-mcp)

## Tags
mcp, git, github, documentation, open-source