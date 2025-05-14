# openMF/mcp-mifosx

**Description:**
A core banking MCP (Model Context Protocol) server for managing clients, loans, savings, shares, and financial transactions, with the ability to interface with Apache Fineract®.

**Source:** [https://github.com/openMF/mcp-mifosx](https://github.com/openMF/mcp-mifosx)

**Category:** finance-market-data-mcp-servers

**Tags:** banking, finance, transactions, open-source

---

## Features

- **Multi-language Implementations:**
  - Available in Python (Flask), Java (Quarkus), and Node.js
- **Standardized API Access:**
  - Uses `fineract://` URIs for resources
- **MCP-Compliant:**
  - Supports STDIO and SSE transports for communication
- **Environment-Agnostic Configuration:**
  - Configurable using environment variables for Fineract base URL, authentication token, and tenant ID
- **Core Banking Resources:**
  - List and retrieve clients (`fineract://clients`, `fineract://clients/{clientId}`)
  - List and retrieve loans (`fineract://loans`, `fineract://loans/{loanId}`)
- **Additional Tools:**
  - `search_clients`: Search clients by name/attributes
  - `create_client`: Create a new client (Node.js/Python only)
  - `update_loan_status`: Update loan status (Java/Python only)
- **Developer Tools:**
  - MCP Inspector: Test and debug your MCP server with a local web UI
- **Native Executable Support:**
  - Java (Quarkus) implementation can be compiled to a native executable
- **Open Source:**
  - Community-driven, contributions welcome

## Getting Started
- Choose your preferred implementation (Python, Java, Node.js)
- Configure required environment variables
- Run the server following language-specific instructions
- Test and debug using the MCP Inspector tool

## Contributing
- Extend endpoints and resources in the respective language implementation

## Pricing
- **Open Source:** No pricing or paid plans; available under an open source license.

---