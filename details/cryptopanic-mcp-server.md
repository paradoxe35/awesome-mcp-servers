# cryptopanic-mcp-server

[GitHub Repository](https://github.com/kukapay/cryptopanic-mcp-server)

## Description
cryptopanic-mcp-server is an MCP server designed to provide the latest cryptocurrency news to AI agents. It is powered by the CryptoPanic API and allows integration with AI systems to fetch up-to-date crypto news, analysis, and videos.

## Features
- Fetches the latest cryptocurrency news from CryptoPanic.
- Designed for integration with AI agents and automation workflows.
- Implements a single tool function:
  - `get_crypto_news(kind: str = "news", num_pages: int = 1) -> str`
    - `kind`: Content type ("news", "analysis", "videos").
    - `num_pages`: Number of pages to fetch (default: 1, maximum: 10).
- Flexible configuration for server setup, including environment variable for API key.
- Open source under the MIT License.

## Requirements
- CryptoPanic API key (required to fetch news).
- Python environment to run the server.

## Usage Example
- Fetch headlines such as:
  - "Bitcoin Breaks $60k Resistance Amid ETF Optimism"
  - "Ethereum Layer 2 Solutions Gain Traction"
  - "New Crypto Regulations Proposed in EU"

## License
MIT License

## Pricing
No pricing information is provided. The project is open source.