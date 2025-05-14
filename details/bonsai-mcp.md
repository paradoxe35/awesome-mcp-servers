# Bonsai MCP

**Category:** Data Access Integration MCP Servers  
**Tags:** mcp, blender, bim, ai-integration

## Description
Bonsai MCP is a Model Context Protocol (MCP) server that connects Claude (and other AI assistants) to Blender for analyzing and interacting with IFC (Industry Foundation Classes) building models. It is specifically designed for BIM (Building Information Modeling) workflows, enabling AI-driven querying, analysis, and modification of IFC files via Blender and IfcOpenShell.

## Features
- **AI Integration:** Allows large language models like Claude to interact with IFC models via natural language.
- **Blender & IfcOpenShell Support:** Requires Blender 4.0+ and the Bonsai BIM addon for full IFC functionality.
- **REST/OpenAPI Interface:** Exposes MCP tools as REST/OpenAPI APIs for integration with other systems.
- **Specialized BIM Tools:**
  - `get_ifc_project_info`: Retrieves basic project information from IFC files.
  - `list_ifc_entities`: Lists entities of a specific type (e.g., walls, doors, spaces).
  - `get_ifc_properties`: Retrieves all properties of a selected IFC entity.
  - `get_ifc_spatial_structure`: Explores the spatial hierarchy of the IFC model.
  - `get_ifc_relationships`: Retrieves all relationships for a specific IFC entity.
  - `get_selected_ifc_entities`: Gets data for currently selected entities in Blender.
  - `get_user_view`: Captures current Blender viewport as an image.
  - `export_ifc_data`: Exports IFC data to structured JSON or CSV.
  - `place_ifc_object`: Creates and places IFC objects at specified coordinates.
- **Sequential Thinking Tool:** Facilitates structured, step-by-step analysis and planning for complex BIM tasks.
- **Multiple Installation Options:**
  - Clone & run with `uv` package manager.
  - Dockerized deployment with configurable environment variables.
- **Blender Addon Integration:** Dedicated addon for Blender to manage MCP-IFC interactions.
- **Open WebUI & Cursor Compatibility:** Easily connect with Open WebUI and Cursor for enhanced workflow integration.
- **Troubleshooting & Performance:** Documentation includes tips for connection issues, large file handling, and CORS settings.

## Installation Requirements
- Blender 4.0+
- Python 3.12+
- uv package manager
- Bonsai BIM Blender addon

## Source & Documentation
- [Official Source & Docs](https://playbooks.com/mcp/jotaderodriguez-bonsai-blender-ifc)
- [GitHub Repository](https://github.com/JotaDeRodriguez/Bonsai_mcp)

## Pricing
No pricing information provided in the available content.