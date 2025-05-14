# APKTool MCP Server

**APKTool MCP Server** is an open-source Model Context Protocol (MCP) server built on top of Apktool, designed to automate and enhance the reverse engineering of Android APKs using integration with large language models (LLMs) such as Claude. It is part of Zin's Reverse Engineering MCP Suite and is intended for ethical security assessment, research, and education.

## Features

- **Automated Reverse Engineering:** Automates analysis of Android APKs by integrating Apktool with the Model Context Protocol.
- **LLM Integration:** Provides live, context-aware reverse engineering support with LLMs like Claude for tasks such as code review and AI-driven recommendations.
- **Comprehensive MCP Toolset:**
  - `build_apk()`: Build an APK from a decoded APKTool project.
  - `list_workspace_projects()`: List all APKTool project directories in the workspace.
  - `get_manifest()`: Retrieve AndroidManifest.xml from decoded APK projects.
  - `get_apktool_yml()`: Access apktool.yml information.
  - `list_smali_directories()`: List all smali code directories.
  - `list_smali_files()`: List smali files, with optional package prefix filtering.
  - `get_smali_file()`: Get content of specific smali files by class name.
  - `modify_smali_file()`: Modify smali file contents.
  - `list_resources()`: List resources, filterable by type.
  - `get_resource_file()` / `modify_resource_file()`: Get or edit resource files.
  - `search_in_file()`: Pattern search in files by extension.
  - `check_apktool_version()`: Check installed Apktool version.
  - `sign_apk()`: Sign APK files.
  - `install_apk()`: Install APKs on connected devices (via ADB).
  - `extract_dex()`: Extract DEX files from APKs.
  - `list_packages()`: List packages on connected Android devices (via ADB).
  - `analyze_permissions()`: Analyze permissions declared in AndroidManifest.xml.
  - `clean_project()`: Clean project directories before rebuilding.
  - `create_project()` / `delete_project()`: Manage APKTool project structures.
  - `compare_smali_files()`: Compare smali files and display differences.
  - `get_available_devices()`: List Android devices connected via ADB.
  - `decode_apk()`: Decode APK files using Apktool.
- **AI-powered Prompts:** Supports a range of prompt-based workflows, including static analysis, vulnerability detection, code modification, reverse engineering, and documentation extraction.
- **Sample Use Cases:**
  - List or analyze smali files and directories.
  - Compare code versions.
  - Detect vulnerabilities or dangerous permissions.
  - Modify code or resources using AI suggestions.
  - Extract metadata and documentation.
- **Integration:** Designed for use with Claude Desktop and other Model Context Protocol-enabled LLM clients.
- **Cross-platform:** Works on Linux, Windows, and macOS.
- **Open Source:** Licensed under Apache-2.0.

## Installation & Setup

- Download the latest release from [GitHub Releases](https://github.com/zinja-coder/apktool-mcp-server/releases).
- Unzip and set up the environment using [uv](https://github.com/astral-sh/uv) for dependency management.
- Configure your LLM client (e.g., Claude Desktop) to connect to the MCP server as described in the documentation.

## Pricing

APKTool MCP Server is **free and open-source** (Apache-2.0 license).

## Links

- [Source Code & Documentation](https://github.com/zinja-coder/apktool-mcp-server)

## Tags

`mcp` `reverse-engineering` `android` `open-source`