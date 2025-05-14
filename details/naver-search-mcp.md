# naver-search-mcp

**Category:** data-access-integration-mcp-servers  
**Source:** [GitHub Repository](https://github.com/isnow890/naver-search-mcp)

## Description
`naver-search-mcp` is an MCP server for integrating with the Naver Search API and DataLab API. It enables comprehensive search across various Naver services, such as web documents, news, blogs, shopping, and provides data trend analysis tools using DataLab.

## Features
- **Comprehensive Naver Search Integration**:
  - Search web documents (search_webkr)
  - Search news (search_news)
  - Search blogs (search_blog)
  - Search shopping (search_shop)
  - Search images (search_image)
  - Search KnowledgeiN (search_kin)
  - Search books (search_book)
  - Search encyclopedia (search_encyc)
  - Search academic papers (search_academic)
  - Search local places (search_local)
- **DataLab Analytics**:
  - Analyze search term trends (datalab_search)
  - Analyze shopping category trends (datalab_shopping_category)
  - Analyze shopping trends by device (datalab_shopping_by_device)
  - Analyze shopping trends by gender (datalab_shopping_by_gender)
  - Analyze shopping trends by age group (datalab_shopping_by_age)
  - Analyze shopping keyword trends (datalab_shopping_keywords)
  - Analyze shopping keyword trends by device (datalab_shopping_keyword_by_device)
  - Analyze shopping keyword trends by gender (datalab_shopping_keyword_by_gender)
  - Analyze shopping keyword trends by age group (datalab_shopping_keyword_by_age)
- **Deployment Options**:
  - Install and run via Smithery CLI for different AI clients (Claude Desktop, Cursor, Windsurf, Cline)
  - Manual installation with Node.js and NPM
  - Docker container deployment
- **Configuration**:
  - Requires Naver Developers API Key (Client ID and Secret)
  - Environment variable-based configuration
  - Example configuration for Cursor Desktop and Docker
- **License**: MIT License

## Installation
- **Automated**: Use Smithery CLI for quick setup with various AI clients.
- **Manual**: Set environment variables for API keys and run via NPX or Docker.

## Pricing
- Open source under the MIT license (free to use).

## Tags
mcp, search, api-integration, news, analytics
