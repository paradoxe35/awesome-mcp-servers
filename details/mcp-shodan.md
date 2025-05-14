# mcp-shodan

**Source:** [https://github.com/BurtTheCoder/mcp-shodan](https://github.com/BurtTheCoder/mcp-shodan)

**Category:** security-attestation-mcp-servers

**Tags:** mcp, shodan, vulnerability, security

---

## Description

mcp-shodan is a Model Context Protocol (MCP) server that enables querying of the Shodan API and Shodan CVEDB. It provides a suite of tools for network reconnaissance, vulnerability intelligence, DNS operations, device discovery, and more, delivering structured output for easy analysis and integration.

---

## Features

- **Network Reconnaissance:** Query detailed information about IP addresses, including open ports, services, vulnerabilities, geolocation, SSL certificates, hostnames, and cloud provider details.
- **DNS Operations:** Perform forward and reverse DNS lookups for both domains and IP addresses.
- **Vulnerability Intelligence:** Access Shodan's CVEDB for detailed vulnerability information, including CPE lookups and product-specific CVE tracking.
- **Device Discovery:** Search Shodan's database of internet-connected devices using advanced filtering capabilities.
- **Structured Tools:**
  - **IP Lookup Tool:** Retrieve comprehensive info on IP addresses (geolocation, services, hostnames, etc.).
  - **Shodan Search Tool:** Search for internet-connected devices with result summaries, country distribution, and device details.
  - **CVE Lookup Tool:** Query detailed vulnerability data, including CVSS/EPSS scores, KEV status, mitigations, and affected products.
  - **DNS Lookup Tool:** Resolve domain names to IP addresses.
  - **Reverse DNS Lookup Tool:** Find hostnames associated with IP addresses.
  - **CPE Lookup Tool:** Search for Common Platform Enumeration entries by product name, with support for pagination and count-only queries.
  - **CVEs by Product Tool:** Search for vulnerabilities affecting specific products or CPEs, with filters for KEV flag, EPSS sorting, date ranges, and pagination.
- **Comprehensive Error Handling:** Handles invalid API keys, rate limiting, network errors, input validation, and mutually exclusive parameters.
- **Integration:** Designed for use with Claude Desktop and can be installed via npm or Smithery CLI.
- **Development Support:** Hot reloading available in development mode.

---

## Requirements

- Node.js (v18 or later)
- Valid Shodan API Key

---

## Pricing

No pricing information is provided. mcp-shodan is open-source and licensed under the MIT License. However, usage of the Shodan API requires a valid Shodan API key, which may be subject to Shodan's own pricing and rate limits.

---

## License

MIT License
