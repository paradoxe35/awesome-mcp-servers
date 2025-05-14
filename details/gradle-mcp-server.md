# gradle-mcp-server

A Model Context Protocol (MCP) server enabling AI tools to interact programmatically with Gradle projects using the Gradle Tooling API.

**Source:** [GitHub Repository](https://github.com/IlyaGulya/gradle-mcp-server)

**Category:** Development Tools - MCP Servers

**Tags:** mcp, gradle, build-automation, testing, development

---

## Features

- **Programmatic Gradle Project Access:** Allows AI tools to interact with Gradle projects through the MCP protocol.
- **Uses Gradle Tooling API:** Queries project information, executes tasks, and runs tests.
- **Exposes Tools via MCP:**
  - Get Gradle Project Info
  - Execute Gradle Task
  - Run Gradle Tests
- **Supports Multiple Clients:** Can be used with MCP clients such as VSCode extensions or AI desktop applications.
- **Command-line Installation:** Offers automated and manual installation methods for various platforms (Linux, macOS, Windows).
- **Configurable:** Behavior can be controlled via command-line arguments when running the server.
- **Development Friendly:** Can be built from source and run locally for testing and development.
- **Communicates Over stdio:** By default, server communicates over standard input/output for compatibility with various clients.

---

## Pricing

No pricing information provided; the repository appears to be open source.

---

## Requirements

- Java (for running the JAR)
- Gradle projects to inspect

---

## Installation

- **Recommended:** Command-line download using curl (for Linux/macOS) or PowerShell (for Windows).
- **Alternative:** Manual download of the server JAR.

---

## Usage

- Configure your MCP client (such as VSCode extension or Claude Desktop app) to connect to the gradle-mcp-server by editing the client's settings file and adding the server configuration.
- Run the server JAR directly from the command line for testing or development.
