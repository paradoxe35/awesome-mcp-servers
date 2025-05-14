# mcp-nixos

**MCP-NixOS** is a Model Context Protocol (MCP) server that provides accurate, real-time information about NixOS packages, system options, Home Manager user configurations, and nix-darwin macOS settings. It is designed to prevent hallucinations in AI assistants by directly querying up-to-date resources, making it a valuable tool for developers, system administrators, and anyone integrating AI with the Nix ecosystem.

- **Project URL:** [https://github.com/utensils/mcp-nixos](https://github.com/utensils/mcp-nixos)
- **Category:** Data Access Integration MCP Servers
- **Tags:** nixos, linux, configuration, open-source, ai-integration
- **License:** MIT

---

## Features

### NixOS Resources
- Access to real NixOS packages and system options via the official Elasticsearch API
- Supports multiple channels: unstable, stable (24.11), and specific versions
- Provides detailed package metadata
- Fast in-memory and rich search engine for packages and options
- Statistics endpoints for package data

### Home Manager
- Access to Home Manager user configuration options
- Parses and presents program, service, and settings documentation
- Hierarchical path support for deep configuration queries
- Tools for searching, retrieving, and listing Home Manager options by prefix or category

### nix-darwin
- macOS configuration support for nix-darwin
- Accesses system defaults, services, and user-level settings
- Tools for searching, retrieving, and listing nix-darwin options and categories

### Smart Caching
- Caches API responses and parsed documentation for offline operation
- Platform-specific cache directories
- Configurable cache TTL and orphaned process cleanup

### Search & Query Tools
- Fast in-memory search for packages, options, and configurations
- Related option suggestions for ambiguous queries
- Python tool functions for integration (e.g., `nixos_search`, `nixos_info`, `home_manager_search`, etc.)

### Integration & Protocol
- Implements the Model Context Protocol (MCP) using JSON over stdin/stdout
- Designed for LLMs and AI assistants to access up-to-date system information
- Simple configuration for use with Claude and other MCP-compatible models

### Development & Extensibility
- Modular code structure for easy extension
- Real API integration for NixOS (not mocked)
- Dev environment provided via Nix shell or Python (pip/uv)
- Testing with real Elasticsearch API calls

### Installation
- Installable via `pip`, `uv`, or directly via `uvx`
- Configurable via MCP config files
- Development dependencies installable via `pip install -e ".[dev]"` or Nix shell

### Environment Variables
- `MCP_NIXOS_LOG_LEVEL`: Set logging verbosity
- `MCP_NIXOS_CACHE_DIR`: Set custom cache directory
- `MCP_NIXOS_CACHE_TTL`: Set cache expiration (default 24h)
- `ELASTICSEARCH_URL`: Custom NixOS Elasticsearch API endpoint

### Example Usage
- NixOS: `nixos_search(query="firefox", type="packages", channel="unstable")`
- Home Manager: `home_manager_info(name="programs.git.userName")`
- nix-darwin: `darwin_search(query="system.defaults.dock")`

---

## Pricing
- **Free and open source** (MIT License)

---

## Source Code
- [GitHub Repository](https://github.com/utensils/mcp-nixos)

---

## Supported Platforms
- Linux (NixOS)
- macOS (via nix-darwin)
- Windows (cache supported)

---

## Related Resources
- NixOS official documentation
- Home Manager documentation
- nix-darwin documentation

---

## Contributors
- [James Brink](https://github.com/jamesbrink)
- [Lawrence Sinclair](https://github.com/lwsinclair)

---