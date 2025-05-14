# mcp-server-giphy

**Category:** Media Processing MCP Servers  
**Source:** [GitHub Repository](https://github.com/magarcia/mcp-server-giphy)

## Description
mcp-server-giphy is an open-source MCP server for integrating Giphy GIF search and retrieval capabilities via the Giphy API. It enables AI assistants to search, retrieve, and utilize GIFs from Giphy, supporting various search methods and providing optimized responses for AI model consumption.

## Features
- **Content Filtering:** Filter GIF results by rating (G, PG, PG-13, R).
- **Optimized Response Format:** Data structured for efficient AI model use.
- **Multiple Search Methods:**
  - Query-based GIF search.
  - Retrieve random GIFs, optionally filtered by tag.
  - Get currently trending GIFs.
- **Comprehensive Metadata:** Each GIF includes metadata such as dimensions, formats, attribution, and more.
- **Pagination Support:** Control result size and offset for efficient API usage.
- **Response Includes:**
  - id: Giphy identifier
  - title: GIF title
  - url: Link to the Giphy website
  - images: Various image formats with URLs, width, and height
  - Additional metadata as available

## Tools/Endpoints
- **search_gifs**
  - Search GIFs with query, limit, offset, rating, and language options.
  - Returns an array of GIF objects with metadata.
- **get_random_gif**
  - Retrieve a random GIF, optionally filtered by tag and rating.
  - Returns a single GIF object with metadata.
- **get_trending_gifs**
  - Fetch trending GIFs, with pagination and rating filters.
  - Returns an array of trending GIF objects with metadata.

## Usage
- Requires a Giphy API key (free and paid tiers available via Giphy Developer account).
- Can be installed via Smithery for use with Claude Desktop or run via npm.
- Supports local development, building, and testing.

## License
MIT License.

## Pricing
- The project itself is open source and free to use under the MIT License.
- A Giphy API key is required; Giphy offers both free and paid API plans (details available on the Giphy Developer website).