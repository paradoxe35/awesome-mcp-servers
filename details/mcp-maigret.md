# mcp-maigret

**Category:** security-attestation-mcp-servers  
**Tags:** mcp, osint, security, social-media

## Description
mcp-maigret is an MCP (Model Context Protocol) server for Maigret, a powerful OSINT (Open Source Intelligence) tool. It enables the collection of user account information from various public sources by searching usernames across social networks and analyzing URLs. The server is designed for integration with MCP-compatible applications, such as Claude Desktop, and is intended for legitimate, ethical OSINT research.

## Features
- **Username Search:** Search for a username across hundreds of social networks and websites.
- **URL Analysis:** Parse URLs to extract information and search for associated usernames.
- **Multiple Output Formats:** Supports output in txt, html, pdf, json, csv, and xmind formats.
- **Site Filtering:** Allows filtering of searches by site tags (e.g., photo, dating, us).
- **Docker-based Deployment:** Ensures reliable and consistent execution across different environments.
- **Integration with MCP Applications:** Easily integrates with applications like Claude Desktop via configuration.
- **Tools Provided:**
  - `search_username`: Search for usernames with options for output format, site filtering, and scope.
  - `parse_url`: Analyze URLs to extract related user/account information.

## Requirements
- Node.js (v18 or later)
- Docker (with Docker Desktop for macOS/Windows or Docker Engine for Linux)
- macOS, Linux, or Windows
- Write access to a reports directory

## Installation & Setup
- Can be installed via Smithery CLI or manually via npm and Docker.
- Requires configuration of the `MAIGRET_REPORTS_DIR` environment variable and addition to MCP-compatible application configuration files.

## License
MIT License

## Source
[https://github.com/BurtTheCoder/mcp-maigret](https://github.com/BurtTheCoder/mcp-maigret)

## Pricing
No pricing information provided; the project is open source and licensed under MIT.