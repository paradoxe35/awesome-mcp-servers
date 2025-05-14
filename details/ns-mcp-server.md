# ns-mcp-server

**Category:** Data Access & Integration / MCP Servers  
**Source:** [GitHub - r-huijts/ns-mcp-server](https://github.com/r-huijts/ns-mcp-server)

## Description
ns-mcp-server is a Model Context Protocol (MCP) server that provides access to real-time Dutch Railways (NS) travel information. It enables AI assistants, such as Claude, to fetch train schedules, real-time updates, disruptions, ticket prices, and station information using the official NS API.

## Features
- **Real-time Train Information:**
  - Departures: Real-time departure data, platform numbers, delays, and travel notes
  - Arrivals: Upcoming arrivals, origin stations, platform changes, and status updates
  - Journey Planning: Optimal routes with transfers and live updates
  - Service Updates: Disruptions, maintenance, and engineering works

- **Pricing Information:**
  - Ticket prices for single and return journeys
  - Price comparison for first and second class
  - Group pricing for adults and children
  - Discount options for joint journeys and special offers
  - Ticket validity periods and travel conditions

- **Station Information:**
  - Facilities and accessibility features
  - Platform layouts and track information
  - OV-fiets (bike rental) availability
  - Location and approach details

- **Additional Features:**
  - Multi-language support (Dutch and English)
  - Flexible queries by station name, code, or UIC identifier
  - Time zone handling for international stations
  - Real-time status updates: delays and cancellations

## Installation
- Via Claude Desktop with NPM package
- Using Smithery CLI
- From source (clone and install dependencies)

## Environment Variables
- `NS_API_KEY` (required): Your NS API key (get from [NS API Portal](https://apiportal.ns.nl/product#product=NsApp))

## License
MIT License

## Pricing
No pricing information is provided. The software itself is open-source under the MIT License; use of the NS API may be subject to the NS API's own terms and potential costs.