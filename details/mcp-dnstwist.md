# mcp-dnstwist

[Source Code](https://github.com/BurtTheCoder/mcp-dnstwist)

## Description
mcp-dnstwist is an MCP (Model Context Protocol) server for dnstwist, a DNS fuzzing tool designed to help detect typosquatting, phishing, and corporate espionage. It provides tools for analyzing domain permutations and identifying potentially malicious domains, and is intended for integration with MCP-compatible applications such as Claude Desktop.

## Features
- **Domain Fuzzing:** Generates domain permutations using multiple algorithms.
- **Registration Check:** Verifies if permutated domains are registered.
- **DNS Analysis:** Checks A, AAAA, MX, and NS records for domains.
- **Web Presence:** Captures HTTP banner information from discovered domains.
- **WHOIS Data:** Retrieves registration dates and registrar information.
- **Phishing Detection:** Generates fuzzy hashes (ssdeep) of web pages for phishing detection.
- **Configurable:** Allows use of custom DNS servers and configurable parallel processing (threads).
- **Multiple Formats:** Supports output formats including JSON, CSV, and list.
- **Integration:** Designed to work with Claude Desktop and other MCP-compatible tools.

### Domain Fuzzing Tool (fuzz_domain)
- **Parameters:**
  - `domain` (required): Domain name to analyze (e.g., example.com)
  - `nameservers` (optional): Comma-separated list of DNS servers (default: "1.1.1.1")
  - `threads` (optional): Number of threads for parallel processing (default: 50)
  - `format` (optional): Output format (json, csv, list; default: json)
  - `registered_only` (optional): Show only registered domains (default: true)
  - `mxcheck` (optional): Check for MX records (default: true)
  - `ssdeep` (optional): Generate fuzzy hashes of web pages (default: false)
  - `banners` (optional): Capture HTTP banner information (default: true)

## Requirements
- Node.js (v18 or later)
- Docker
- macOS, Linux, or Windows with Docker Desktop installed

## Installation
- Via Smithery CLI: `npx -y @smithery/cli install @burtthecoder/mcp-dnstwist --client claude`
- Global npm install: `npm install -g mcp-dnstwist`
- Manual/source install: Clone repository, install dependencies, and build

## License
MIT License

## Pricing
No pricing information provided; the software is open-source and available under the MIT License.