# Aviation MCP

[Source Code](https://github.com/finack/aviation-mcp)

## Description
Aviation MCP is a Model Context Protocol (MCP) server that provides aviation weather information via API integration. It fetches data such as METARs, TAFs, PIREPs, and route weather information from aviationweather.gov, making it accessible for integration with other tools and large language models (LLMs), such as Claude for Desktop.

> **Disclaimer:** This tool is for informational purposes only and must not be used as the sole source for flight planning or in-flight decisions. Always consult official aviation weather sources.

## Features
- MCP server implementation for aviation weather data.
- Connects to the Aviation Weather API to retrieve:
  - METARs (Meteorological Aerodrome Reports)
  - TAFs (Terminal Aerodrome Forecasts)
  - PIREPs (Pilot Reports)
  - Route weather data
- Designed for integration with LLMs (e.g., Claude for Desktop).
- Fetches latest API definitions and generates client code during build.
- Open-source (MIT License).
- Can be extended with additional tools and data sources.

## Installation
- Clone the repository.
- Install dependencies.
- Build the server (fetches latest API definitions and compiles TypeScript code).
- Start the server.

## Integration
- Can be integrated with Claude for Desktop by configuring the server in the application's settings.

## Pricing
- Open-source and free to use under the MIT License.

## Category
- Data Access & Integration / MCP Servers

## Tags
mcp, weather, open-data, aviation, api-integration