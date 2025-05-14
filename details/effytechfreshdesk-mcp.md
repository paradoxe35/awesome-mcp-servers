# effytech/freshdesk-mcp

**Source:** [GitHub Repository](https://github.com/effytech/freshdesk_mcp)

## Description
`effytech/freshdesk-mcp` is an open-source MCP (Model Control Protocol) server that integrates with Freshdesk, enabling AI models to interact with Freshdesk modules and perform various customer support operations via the Freshdesk API.

## Features
- **Freshdesk Integration:** Seamlessly interacts with Freshdesk API endpoints.
- **AI Model Support:** Enables AI models to perform automated support operations within Freshdesk.
- **Automated Ticket Management:**
  - Create support tickets with customizable fields (subject, description, source, priority, status, email, requester ID, custom fields).
  - Update existing tickets (update any ticket fields by ticket ID).
  - Delete tickets by ID.
  - Search tickets using query strings.
  - Retrieve all ticket fields.
  - List all tickets with pagination (page number, tickets per page).
  - Retrieve details of a single ticket by ID.
- **Smithery Integration:** Can be installed and managed via Smithery for Claude Desktop.
- **Configuration:** Requires Freshdesk account and API key; supports environment variable configuration for secure access.
- **Testing Support:** Can be started manually for testing and development.
- **Open Source:** Licensed under the MIT License.

## Components / Tools
- `create_ticket`: Create new support tickets with required and optional fields.
- `update_ticket`: Update fields of existing tickets.
- `delete_ticket`: Delete tickets by ID.
- `search_tickets`: Search tickets using custom queries.
- `get_ticket_fields`: Retrieve all available ticket fields.
- `get_tickets`: Retrieve a paginated list of tickets.
- `get_ticket`: Retrieve details for a single ticket by ID.

## Requirements
- Freshdesk account and API key
- `uvx` installed (`pip install uv` or `brew install uv`)
- Smithery CLI (for installation via Smithery)

## License
MIT License

## Pricing
No pricing information provided; the project is open-source and free to use under the MIT License.