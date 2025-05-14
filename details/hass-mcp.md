# Hass MCP

**Category:** AI Integration MCP Servers  
**Tags:** mcp, home-assistant, smart-home, natural-language  
**Source:** [GitHub - voska/hass-mcp](https://github.com/voska/hass-mcp)

## Description
Hass-MCP is a Model Context Protocol (MCP) server that integrates Home Assistant with large language models (LLMs) like Claude. It enables natural language control and management of smart home devices by exposing Home Assistant's API via a Dockerized MCP server.

## Features
- **Entity Management**: Query the state of devices and sensors, control lights, switches, and other entities, search for entities by name, type, or state.
- **Domain Summaries**: Obtain high-level information about groups of entities (e.g., all lights or sensors).
- **Automation Support**: List and control automations within Home Assistant.
- **Guided Conversations**: Use AI-driven prompts for creating automations, troubleshooting, and optimizing routines.
- **Smart Search**: Find entities using flexible queries.
- **Token Efficiency**: Lean JSON responses reduce LLM token usage.
- **Resource Endpoints**: Access entity states, detailed attributes, domain-specific listings, and custom search endpoints.
- **Tools Provided**:
  - `get_version`: Retrieve Home Assistant version
  - `get_entity`: Get state of a specific entity
  - `entity_action`: Perform actions (on/off/toggle) on entities
  - `list_entities`: List entities with filtering
  - `search_entities_tool`: Search for entities by query
  - `domain_summary_tool`: Domain entity summaries
  - `list_automations`: List all automations
  - `call_service_tool`: Call any Home Assistant service
  - `restart_ha`: Restart Home Assistant
  - `get_history`: Retrieve state history of entities
  - `get_error_log`: Fetch Home Assistant error logs
- **Guided Prompts**:
  - `create_automation`, `debug_automation`, `troubleshoot_entity`, `routine_optimizer`, `automation_health_check`, `entity_naming_consistency`, `dashboard_layout_generator`
- **Multiple Client Support**: Works with Claude Desktop, Cursor, and Claude Code CLI.
- **Docker Support**: Easily deployable via Docker for seamless integration.

## Installation
- Requires a Home Assistant instance with a Long-Lived Access Token.
- Can be run via Docker (recommended) or with Python 3.13+ and uv.
- Detailed instructions are provided for use with Claude Desktop, Cursor, and CLI tools.

## License
MIT License

## Pricing
No pricing information provided; open-source under the MIT license.