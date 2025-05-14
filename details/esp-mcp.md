# esp-mcp

**Category:** Development Tools / MCP Servers  
**Tags:** mcp, esp32, hardware, build-automation

## Description
esp-mcp is an MCP (Machine Control Protocol) server aimed at streamlining workflows and fixing build issues for ESP32 series chips using ESP-IDF. It is currently a proof-of-concept project.

## Features
- Supports simple project builds for ESP32 using the ESP-IDF build command
- Provides build logging during the build process
- Attempts automatic issue fixing based on build logs
- Can be integrated and configured as part of a chatbot environment

## Installation
- Clone the repository: `git clone git@github.com:horw/esp-mcp.git`
- Configure the MCP server in your chatbot with the appropriate command, arguments, and environment variables (notably the `IDF_PATH` for ESP-IDF)

## Notes
- Currently in proof-of-concept stage
- Potential for extension to embedded devices, home assistants, and documentation workflows

## Source
[https://github.com/horw/esp-mcp](https://github.com/horw/esp-mcp)

## Pricing
No pricing information available; open-source proof-of-concept.