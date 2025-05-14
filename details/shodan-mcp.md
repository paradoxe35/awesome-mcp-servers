# Shodan-MCP

[View on MCP Server Finder](https://www.mcpserverfinder.com/servers/burtthecoder/mcp-shodan)

## Description
Shodan-MCP is a security-focused Model Context Protocol (MCP) server that integrates with the Shodan API and Shodan CVEDB to provide comprehensive network intelligence and security services. It is designed for tasks such as CVE vulnerability tracking, attack surface visualization, automated pentesting report generation, and streamlined security audits. The server outputs structured, formatted data for easy analysis and integration.

## Features
- **Network Reconnaissance**: Query detailed information about IP addresses, including open ports, services, vulnerabilities, geolocation, SSL certificates, hostnames, and cloud provider details.
- **DNS Operations**: Perform both forward and reverse DNS lookups for domains and IP addresses.
- **Vulnerability Intelligence**: Access Shodan's CVEDB for vulnerability information, including CVE lookups, CPE searches, and product-specific CVE tracking.
- **Device Discovery**: Search Shodan's database of internet-connected devices with advanced filtering.
- **IP Lookup Tool**: Retrieve comprehensive information about an IP, such as geolocation, open ports, running services, SSL certificates, hostnames, and organization details.
- **Shodan Search Tool**: Search Shodan’s database with custom queries, retrieve device details, service information, and country-based statistics.
- **CVE Lookup Tool**: Query detailed vulnerability information by CVE ID, including severity scores (CVSS v2/v3), EPSS probability, KEV status, proposed mitigations, ransomware associations, affected products, and references.
- **DNS Lookup Tool**: Resolve domain names to IP addresses.
- **Reverse DNS Lookup Tool**: Map IP addresses to hostnames.
- **CPE Lookup Tool**: Search for Common Platform Enumeration (CPE) entries by product, with pagination and count support.
- **CVEs by Product Tool**: Search for vulnerabilities affecting specific products or CPEs, filter by KEV, EPSS score, and date range, with detailed vulnerability information and pagination.
- **Comprehensive Error Handling**: Handles invalid API keys, rate limiting, network errors, invalid parameters, and mutually exclusive parameter validation.
- **Output Formatting**: All tools provide structured, easy-to-parse output suitable for further processing or integration.

## Requirements
- Node.js v18 or later
- Valid Shodan API Key

## Installation
- Install via Smithery or npm for Claude Desktop integration.
- Alternatively, clone and build from source.
- Configure with your Shodan API key in the environment or configuration file.

## Version History
- **v1.0.12**: Added reverse DNS lookup and improved output formatting
- **v1.0.7**: Added CVEs by Product search functionality and renamed vulnerabilities tool to cve_lookup
- **v1.0.6**: Added CVEDB integration for enhanced CVE lookups and CPE search functionality
- **v1.0.0**: Initial release with core functionality

## License
MIT License

## Tags
`security` `cve` `vulnerability` `pentesting`

## Category
Security Attestation MCP Servers

## Pricing
_No pricing information provided._