# google-news-mcp-server

**Source:** [github.com/ChanMeng666/server-google-news](https://github.com/ChanMeng666/server-google-news)

A Model Context Protocol (MCP) server implementation that provides Google News search capabilities via SerpAPI integration, with automatic topic categorization and multi-language support.

## Features

- **Comprehensive Search Capabilities**: Supports query-based search, topic search, publication filtering, and full story coverage.
- **Global Coverage**: Supports multiple languages and regions via configurable language (`hl`) and country (`gl`) codes.
- **Automatic Topic Categorization**: News results are automatically categorized into topics such as AI & Technology, Business, Science & Research, and Healthcare.
- **Multiple Result Types**: Handles headlines, stories, related topics, and menu links.
- **Robust Error Handling**: Provides helpful error messages for API failures and invalid inputs.
- **Language Fallback**: Automatically falls back to English for unsupported language codes, with user notification.
- **API Parameter Support**:
  - `q` (search query)
  - `gl` (country code)
  - `hl` (language code)
  - `topic_token`, `publication_token`, `story_token`, `section_token` for more refined searches
- **Installation Options**: Can be installed via npm, yarn, pnpm, Smithery, or mcp-get.
- **Development Tools**: Includes scripts for development mode (hot reload), linting, and testing.
- **MIT Licensed**

## API Usage & Limits

- **SERP API Key Required**: Obtainable from SerpAPI (free and paid tiers available).
- **Free Tier**: 100 searches per month.
- **Paid Plans**: Start at $50/month for 5000 searches. Billing is based on successful API calls.
- **Usage Limits**:
  - 2 requests/second
  - No IP restrictions
  - Up to 5 concurrent requests
  - Response cache time: 1 hour

## Tech Stack
- Node.js, TypeScript, JavaScript, Docker

## Pricing

- **Free tier**: 100 searches/month (via SerpAPI)
- **Paid plans**: Starting at $50/month for 5000 searches (via SerpAPI)

## License

MIT License

## Author

Created and maintained by Chan Meng.