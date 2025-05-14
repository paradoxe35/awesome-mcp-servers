# Airbnb MCP Server

**Category:** Business & Commerce MCP Servers  
**Tags:** travel, airbnb, api-integration, open-source  
**Source:** [GitHub Repository](https://github.com/openbnb-org/mcp-server-airbnb)

## Description
Airbnb MCP Server is an open-source MCP (Machine Communication Protocol) server that enables programmatic searching of Airbnb listings and retrieval of detailed listing information. It allows clients to access Airbnb data through a structured protocol, suitable for integration into travel-related services and applications.

## Features
- **Search Airbnb Listings:**
  - Search for Airbnb listings by location (required).
  - Optional parameters: placeId, checkin/checkout dates, number of adults, children, infants, pets, price range, pagination cursor, and robots.txt override.
  - Returns an array of listings with details like name, price, location, etc.
- **Retrieve Listing Details:**
  - Get detailed information about a specific Airbnb listing by ID.
  - Optional parameters: checkin/checkout dates, number of guests, robots.txt override.
  - Returns detailed information including description, host, amenities, pricing, and more.
- **Respects robots.txt:**
  - By default, respects Airbnb's robots.txt rules. Optionally, requests can ignore these rules.
- **No API Key Required:**
  - Does not require an Airbnb API key for access.
- **Structured JSON Output:**
  - Provides clean, structured JSON responses suitable for programmatic consumption.
- **HTML Parsing:**
  - Uses Cheerio for parsing HTML content from Airbnb.
- **Reduced Context Load:**
  - Data is flattened and optimized to reduce unnecessary context in responses.
- **Installation Options:**
  - Can be installed and run via Node.js (`npx`) or integrated with Claude Desktop and Smithery CLI.
- **Open Source:**
  - Licensed under the MIT License.

## Pricing
- The Airbnb MCP Server is open-source and free to use under the MIT License.

## License
MIT License

## Disclaimer
Airbnb is a trademark of Airbnb, Inc. The OpenBnB project is not affiliated with Airbnb, Inc. or its subsidiaries.