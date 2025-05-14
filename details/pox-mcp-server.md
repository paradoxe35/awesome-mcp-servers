# pox-mcp-server

A Model Context Protocol (MCP) server for the POX SDN controller that enables network control and management through the MCP protocol. It is designed for educational settings, network prototyping, and SDN research, leveraging POX's modular Python-based architecture.

- **Source:** [GitHub - davidlin2k/pox-mcp-server](https://github.com/davidlin2k/pox-mcp-server)
- **Category:** cloud-devops-mcp-servers
- **Tags:** pox, sdn, networking, mcp

## Features

### Exposed Resources
- **pox://network-config:**
  - Provides a comprehensive POX controller configuration memo
  - Tracks active POX components and their configurations
  - Records network topology and flow rules
  - Maintains discovered network insights
- **pox://topology:**
  - Real-time network topology view
  - Shows active OpenFlow datapaths (switches)
  - Maps host locations and connections
  - Displays link status and port mappings

### Prompts (Interactive Interfaces)
- **pox-network-manager:**
  - Manages POX controller interactively, focusing on network control aspects
  - Assists with configuring POX components and modules
  - Guides network policy implementation
  - Integrates with the network configuration memo
- **simple-hub:**
  - Basic L2 hub implementation using POX
  - Demonstrates POX's event-driven programming and packet handling
- **learning-switch:**
  - L2 learning switch implementation
  - Demonstrates MAC learning, forwarding, and table management

### Tools
- **Datapath Management:**
  - `get_switches`: List all connected OpenFlow datapaths (switches), with status and capabilities
  - `get_switch_desc`: Fetch detailed datapath (switch) information
- **Flow Management:**
  - `get_flow_stats`: Retrieve POX flow statistics for specified datapaths and filters
  - `set_table`: Configure POX flow tables for specific datapaths
- **Analysis:**
  - `append_insight`: Add network insights and observations to the configuration memo

### Usage
- Designed to be run with `uv` for local development and testing
- Example environment variable: `POX_SERVER_URL=http://localhost:8000`

### License
- MIT License (Permissive open source)

## Pricing

- The project is open source and free to use under the MIT License.
