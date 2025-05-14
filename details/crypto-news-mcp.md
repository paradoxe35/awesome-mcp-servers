# crypto-news-mcp

An open-source MCP server that supplies real-time cryptocurrency news using data from NewsData, intended for integration with AI agents and MCP-compatible applications.

## Features
- **Real-Time Cryptocurrency News:** Provides up-to-date news headlines related to cryptocurrencies.
- **Latest News Headlines Tool:** Fetches the most recent cryptocurrency news headlines with publication dates.
- **Crypto News Search Tool:** Search for news articles using keywords or specific cryptocurrencies, with pagination support via a nextPage API feature.
- **News Summary Prompt:** Generates prompts to summarize news about a particular cryptocurrency or topic, suitable for LLMs or AI agents.
- **MCP Protocol Integration:** Designed for seamless integration with MCP-compatible clients and agents.
- **Open Source:** Licensed under the MIT license.
- **Python-Based:** Requires Python 3.10+ and a Newsdata.io API key.

## Installation
- Clone the repository: `git clone https://github.com/kukapay/crypto-news-mcp.git`
- Install dependencies: `pip install mcp[cli] httpx python-dotenv`
- Install as a plugin or configure manually for MCP-compatible clients.

## Usage
- **get_latest_news:** Fetch latest crypto news headlines.
- **get_crypto_news:** Search for news articles by keyword or cryptocurrency, with pagination.
- **summarize_news:** Generate a prompt for summarizing news on a specific topic.

## License
MIT License

## Source
[https://github.com/kukapay/crypto-news-mcp](https://github.com/kukapay/crypto-news-mcp)

## Pricing
No pricing information provided; the project is open source under the MIT license.