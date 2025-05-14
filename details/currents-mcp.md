# currents-mcp

**Category:** Testing & Debugging Tools  
**Tags:** mcp, testing, cicd, ai-agent

[Source on GitHub](https://github.com/currents-dev/currents-mcp)

## Description
Currents MCP Server is a tool that enables integration between Playwright test results (as reported to Currents) and AI agents, allowing AI to analyze, fix, or optimize tests that are failing in CI/CD pipelines. It provides a server interface for relaying test context and results to AI-powered tools and workflows.

## Features
- **MCP Server:** Acts as a middleman between Currents (test management) and AI agents, enabling automated handling of test failures.
- **Test Context Provisioning:** Supplies AI agents with detailed context about test failures from Playwright runs in CI/CD environments.
- **API Integration:** Provides endpoints to:
    - Retrieve API configuration (API key and URL for Currents API)
    - Get run information by run ID
    - Get spec file attempts and error details by instance ID
- **Multiple Editor Support:** Can be configured for use with both Cursor Editor and Claude Desktop, making it flexible for different developer environments.
- **Easy Setup:** Uses `npx` for straightforward installation and execution, with configuration via JSON files.
- **Open Source:** Source code available for customization and contributions.

## Pricing
No pricing information is provided; the project is open source on GitHub.