# tripadvisor-mcp

A Model Context Protocol (MCP) server for the Tripadvisor Content API. It provides standardized interfaces for AI assistants to access Tripadvisor location data, reviews, and photos, enabling search and retrieval of travel destinations and experiences.

## Features
- **Search for locations** (hotels, restaurants, attractions) on Tripadvisor by query, category, and filters
- **Get detailed information** about specific locations
- **Retrieve reviews** for locations
- **Retrieve photos** for locations
- **Search for nearby locations** based on coordinates
- **API Key authentication** (requires Tripadvisor Content API key)
- **Docker containerization support** for easy deployment and isolation
- **Configurable list of interactive tools** for AI assistants (choose which tools to enable)
- **Tools provided:**
  - `search_locations`: Search by query text, category, and filters
  - `search_nearby_locations`: Find locations near specific coordinates
  - `get_location_details`: Retrieve detailed information about a location
  - `get_location_reviews`: Retrieve reviews for a location
  - `get_location_photos`: Retrieve photos for a location
- **Test suite included** (pytest compatible)
- **uv integration** for dependency management
- **Support for Claude Desktop integration**

## Usage
- Obtain a Tripadvisor Content API key
- Configure via environment variables or a `.env` file
- Can be run natively or via Docker/Docker Compose
- Example configuration provided for integration with Claude Desktop

## Project Structure
- `src/tripadvisor_mcp/`: Main source code
- `Dockerfile`, `docker-compose.yml`: Containerization support
- `tests/`: Test suite

## License
MIT

## Pricing
No pricing information provided; the project is open source under the MIT license.