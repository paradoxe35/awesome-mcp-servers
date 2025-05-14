# r-huijts/xcode-mcp-server

**Source:** [https://github.com/r-huijts/xcode-mcp-server](https://github.com/r-huijts/xcode-mcp-server)

**Category:** Development Tools / MCP Servers

**Tags:** xcode, build-automation, project-management, mcp

---

## Overview

`xcode-mcp-server` is an open-source Model Context Protocol (MCP) server that provides deep integration with Xcode. It enables AI assistants and automated tools to manage Xcode projects, perform file operations, build and test code, and interact with simulators and package managers via the MCP protocol.

---

## Features

### Project Management
- Set active projects and retrieve detailed project information
- Create new Xcode projects from templates (iOS, macOS, watchOS, tvOS)
- Add files to Xcode projects with target/group specification
- Parse workspace documents to find associated projects
- List available schemes in projects and workspaces

### File Operations
- Read and write files (multiple encodings supported)
- Handle binary files with base64 encoding/decoding
- Search for text content within files (pattern/regex)
- Check file existence and get file metadata
- Create directory structures automatically

### Build & Testing
- Build Xcode projects with customizable options
- Run tests with detailed failure reporting
- Analyze code for issues
- Clean build directories
- Archive projects for distribution

### CocoaPods Integration
- Initialize CocoaPods in projects
- Install and update pods
- Add and remove pod dependencies
- Execute arbitrary pod commands

### Swift Package Manager (SPM)
- Initialize new Swift packages
- Add/remove package dependencies (version requirements supported)
- Update and resolve packages
- Generate documentation using DocC
- Run tests and build Swift packages

### iOS Simulator Tools
- List available simulators with details
- Boot and shut down simulators
- Install and launch apps on simulators
- Take screenshots and record videos
- Manage simulator settings and state

### Xcode Utilities
- Execute Xcode commands via `xcrun`
- Compile asset catalogs
- Generate app icon sets from images
- Trace app performance
- Export and validate archives for App Store submission
- Switch between different Xcode versions

### Security and Error Handling
- Path validation restricts operations to allowed directories
- Detailed error messages and parameter validation
- Safe process management for external commands

### Configuration
- Environment variables and CLI arguments for flexible configuration
- Supports setting base project directory, allowed paths, port, debug/log level

### Compatibility
- Works with Xcode 14.0+, Node.js 16+, Swift 5.5+, CocoaPods (optional)
- Supports standard Xcode projects, workspaces, and SPM projects

---

## Installation & Setup

- **Automated setup script:** Verifies environment, installs dependencies, configures the server, and optionally integrates with Claude Desktop.
- **Manual setup:** Clone the repo, install dependencies, build, and configure via `.env` file.
- **Troubleshooting guides** included for common setup and runtime issues.

---

## Usage

- Start the server with `npm start` (or `npm run dev` for development)
- Configure AI assistants to connect via the server URL (default: `http://localhost:3000`)
- Tools can be invoked programmatically for project setup, file operations, building, and more

---

## Licensing

- Licensed under the MIT License

---

## Pricing

- **Free and open source** (MIT License). No paid plans.
