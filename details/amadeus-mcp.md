# Amadeus MCP

**Category:** business-commerce-mcp-servers  
**Tags:** travel, api-integration, flight-search, open-source

## Description
Amadeus MCP is an open-source Model Context Protocol (MCP) server that integrates with the Amadeus Flight Offers Search API. It enables natural language flight search and itinerary creation via MCP-compatible clients (such as Claude Desktop). The server utilizes the official amadeus-python SDK and is designed to allow AI assistants to fetch and provide flight offer data.

## Features
- **Flight Offers Search:**
  - Retrieve flight options between two locations for specific dates.
  - Returns flight details including departure time, arrival time, airline, and price.
- **Natural Language Integration:**
  - Enables flight search via natural language interfaces through MCP-compatible clients.
- **Tool Exposure:**
  - Exposes a `get_flight_offers` tool to MCP clients for fetching flight data.
- **Customizable Search Parameters:**
  - Search by origin, destination (IATA codes), departure/return dates, number of adults/children/infants, travel class, non-stop preference, currency, price limits, and maximum number of offers.
- **JSON Output:**
  - Flight offers are returned in JSON format with comprehensive details including airline, timings, duration, and pricing.
- **Open Source:**
  - Available under the MIT License.

## Pricing
- **Open Source:** Free to use under the MIT License.  
  (Note: Use of the Amadeus API may require an account and API credentials from Amadeus.)

## Source
[GitHub Repository](https://github.com/donghyun-chae/mcp-amadeus)
