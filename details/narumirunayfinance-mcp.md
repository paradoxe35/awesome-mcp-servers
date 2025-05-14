# narumiruna/yfinance-mcp

A simple MCP server for Yahoo Finance using yfinance. This server provides a set of tools to fetch stock data, news, and other financial information.

## Features
- **get_ticker_info**: Retrieve stock data including company info, financials, trading metrics, and governance data. Requires `symbol` input.
- **get_ticker_news**: Fetches recent news articles related to a specific stock symbol, including title, content, and source. Requires `symbol` input.
- **search**: Fetches and organizes search results from Yahoo Finance, including stock quotes and news articles. Inputs: `query` (ticker symbol or company name), `search_type` ("all", "quotes", "news").
- **get_top**: Get top entities (ETFs, mutual funds, companies, growth companies, or performing companies) in a specific sector. Inputs: `sector`, `top_type` ("top_etfs", "top_mutual_funds", "top_companies", "top_growth_companies", "top_performing_companies"), `top_n` (optional, default 10).
- **get_price_history**: Fetch historical price data for a given stock symbol over a specified period and interval. Inputs: `symbol`, `period` (optional, default '1mo'), `interval` (optional, default '1d').
- **Deployment options**: Can be used via the `uv` Python package installer or Docker.
- **Open Source**: Licensed under the MIT License.

## Pricing
- This project is open-source and free to use under the MIT License.

## Source
[https://github.com/narumiruna/yfinance-mcp](https://github.com/narumiruna/yfinance-mcp)

## Tags
`yfinance` `market-data` `finance` `open-source`