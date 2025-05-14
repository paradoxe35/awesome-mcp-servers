# qianniuspace/mcp-security-audit

A powerful MCP (Model Context Protocol) server for auditing npm package dependencies for security vulnerabilities, integrating remote npm registry for real-time checks.

- **Repository:** [https://github.com/qianniuspace/mcp-security-audit](https://github.com/qianniuspace/mcp-security-audit)
- **Category:** security-attestation-mcp-servers
- **License:** MIT

## Features

- Real-time security vulnerability scanning of npm dependencies
- Integration with remote npm registry for up-to-date security data
- Detailed vulnerability reports, including severity levels (critical, high, moderate, low)
- CVSS scoring and CVE references for each vulnerability
- Automatic fix recommendations and indication of fix availability
- Supports npm, pnpm, and yarn package managers
- Compatible with MCP (Model Context Protocol) integrations
- Provides structured API responses suitable for automation and further processing
- Example response files for development and integration reference

## Installation & Integration

- Can be installed via Smithery or using NPX
- Supports both automatic and manual configuration for MCP servers (Cursor, Cline)
- Example configuration snippets are provided for easy integration

## API Response Format

- Returns detailed information for each vulnerability, including package name, version, severity, description, CVE ID, recommendation, fix availability, CVSS score, and more
- Returns a clear message when no vulnerabilities are found

## Development

- Example response files available for reference (Severity-response.json, no-Severity-response.json)
- Written primarily in TypeScript

## Pricing

- Open source (MIT License); no paid plans

## Links

- [GitHub Repository](https://github.com/qianniuspace/mcp-security-audit)
- [Changelog](https://github.com/qianniuspace/mcp-security-audit/blob/main/CHANGELOG.md)
- [Issue Tracker](https://github.com/qianniuspace/mcp-security-audit/issues)