# 3D Printer Server

**Category:** Code Execution & Automation (MCP Servers)  
**Tags:** mcp, 3d-printing, iot, automation

## Description
3D Printer Server is an MCP server that integrates with multiple 3D printer management systems (such as OctoPrint, Klipper, Duet, Repetier, Bambu Labs, Prusa Connect, and Creality) to enable remote control, advanced STL file manipulation, slicing, and custom print job workflows. It allows for automation and management of 3D printers through natural language commands, supporting integration with platforms like Claude Desktop and Cursor.

## Features
- **Multi-Printer Management:** Supports OctoPrint, Klipper (via Moonraker), Duet, Repetier, Bambu Labs, Prusa Connect, and Creality printers.
- **Remote Control:** Start, cancel, and monitor print jobs remotely.
- **File Handling & STL Manipulation:**
  - Get detailed STL file information
  - Extend STL model bases
  - Uniform/non-uniform scaling
  - Rotate and translate models
  - Merge vertices
  - Center and lay flat models
  - Modify STL sections
  - Generate SVG visualizations
  - Slice STL files to G-code
  - Process and print STL files
- **Printer Control Tools:**
  - Get printer status
  - List and upload files
  - Set printer temperatures
- **Bambu-Specific Tools:**
  - Print .3mf files
  - Support for Bambu AMS and presets
  - Access machine, filament, and process presets (if configured)
- **Integration:**
  - Natural language control via Claude Desktop
  - Usable in Cursor editor (globally or per project)
- **Slicer Integration:** Supports PrusaSlicer, Cura, Slic3r, OrcaSlicer (can be installed inside Docker image)
- **Customizable Configuration:** Environment variables and .env file support for flexible setup
- **Security:** API key/token-based authentication for each printer system

## Limitations
- Processing large STL files may consume significant memory
- Some Bambu printer operations have limitations (e.g., direct temperature control, file operations via FTP)
- Complex STL operations may not work as expected with all models

## Installation
- Node.js 18+ required
- Install via npm (`npm install -g mcp-3d-printer-server`) or from source
- Docker support with custom slicer installation available
- Configuration via environment variables or .env file

## Source & Documentation
- [Project Page & Documentation](https://playbooks.com/mcp/dmontgomery40-3d-printer)
- [GitHub Repository](https://github.com/dmontgomery40/mcp-3d-printer-server)

## Pricing
No pricing information is provided; the server appears to be open source (available via npm and GitHub).
