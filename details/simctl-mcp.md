# simctl-mcp

A Model Context Protocol (MCP) server implementation for iOS Simulator control, enabling interaction and automation with iOS simulators.

- **Source:** [simctl-mcp on GitHub](https://github.com/ambar/simctl-mcp)
- **Category:** code-execution-automation-mcp-servers
- **Tags:** mcp, ios, simulator, automation, development
- **License:** MIT

## Features

**Configuration & Usage:**
- Can be started in two modes:
  - **STDIO Mode:** Communicates through standard input/output streams.
  - **HTTP Server Mode:** Listens for HTTP connections on a specified port (default 8081, configurable).
- Easy integration via `npx simctl-mcp` command.

**Device Management:**
- Create new simulator devices
- Delete existing devices
- Boot and shutdown devices
- List all available devices, device types, and runtimes

**App Management:**
- Install and uninstall apps
- Launch and terminate running apps
- Get app container path and app information
- List installed apps

**App Permissions:**
- Grant, revoke, and reset all app permissions for apps

**System Features:**
- Open URLs in the simulator
- Add media files
- Get/set environment variables
- Get/set appearance (light/dark mode)
- Send simulated push notifications

**Certificate & Security:**
- Add root and regular certificates
- Reset keychain

**Media & Content:**
- Take screenshots
- Get/set pasteboard (clipboard) content

**Prompt Examples:**
- Query supported simulator operations
- Open shortcuts://
- Get bundle ID of "Settings" app
- Set clipboard content
- Query simulator SDK version
- Generate Appium connection string for an app

## Pricing

simctl-mcp is open-source software released under the MIT license. There is no cost to use it.
