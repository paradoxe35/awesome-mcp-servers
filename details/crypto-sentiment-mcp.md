# crypto-sentiment-mcp

[GitHub Repository](https://github.com/kukapay/crypto-sentiment-mcp)

## Description
crypto-sentiment-mcp is an MCP server that delivers real-time cryptocurrency sentiment analysis to AI agents and applications. It leverages Santiment's aggregated social media and news data to track market sentiment and detect emerging trends.

## Features
- **Sentiment Analysis:** Retrieve sentiment balance (positive vs. negative) for specific cryptocurrencies over a specified period.
- **Social Volume Tracking:** Monitor total social media mentions for an asset and detect significant shifts (spikes or drops) in volume.
- **Social Dominance:** Measure the percentage share of discussions an asset occupies in crypto-related media.
- **Trending Words:** Identify the most popular terms trending in cryptocurrency discussions, ranked by score over a period.
- **MCP Tools (API endpoints):**
  - `get_sentiment_balance`: Get the average sentiment balance for an asset (parameters: asset, days).
  - `get_social_volume`: Fetch the total number of social media mentions for an asset (parameters: asset, days).
  - `alert_social_shift`: Detect significant spikes or drops in social volume compared to previous average (parameters: asset, threshold, days).
  - `get_trending_words`: Retrieve the top trending words in crypto discussions (parameters: days, top_n).
  - `get_social_dominance`: Measure the percentage of crypto media discussions dominated by an asset (parameters: asset, days).

## Prerequisites
- Python 3.10 or higher
- Santiment API Key (free or paid)

## License
MIT License

## Pricing
No pricing information is provided. The code is open source under the MIT License, but usage of the Santiment API may require a key (free or paid, details not specified).

## Category
blockchain-crypto-mcp-servers

## Tags
mcp, crypto, sentiment-analysis, real-time