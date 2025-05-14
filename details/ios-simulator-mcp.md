# ios-simulator-mcp

A Model Context Protocol (MCP) server for interacting with iOS simulators, enabling information retrieval, UI control, and inspection.

**Source:** [https://github.com/joshuayoes/ios-simulator-mcp](https://github.com/joshuayoes/ios-simulator-mcp)

## Features
- Retrieve the ID of the currently booted iOS simulator
- Interact with the simulator UI:
  - Describe all accessibility elements on screen
  - Tap on screen coordinates
  - Input text
  - Swipe between coordinates
  - Get information about UI elements at specific coordinates
- Take screenshots of the simulator screen
- Start and stop recording video of the simulator screen
- Filter available tools using environment variables (e.g., filter out screenshot, record_video, stop_recording)
- Designed for integration with MCP clients such as Cursor and Claude Code
- Useful for automating and validating UI interactions, including QA tasks via AI assistant tool calls

## Prerequisites
- Node.js
- macOS (required for iOS simulators)
- Xcode and iOS simulators installed
- Facebook IDB tool

## Installation
- Can be installed and run via NPX or by cloning the repository and running locally
- Integrates with MCP clients such as Cursor and Claude Code via configuration

## License
MIT

## Pricing
- Free and open source (MIT License)

## Tags
`mcp` `ios` `simulator` `ui` `development`