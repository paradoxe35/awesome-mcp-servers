# Jetson MCP

[Source code on GitHub](https://github.com/Zalmotek/jetson-mcp)

## Description
Jetson MCP is a server application that integrates large language models (LLMs) with NVIDIA Jetson hardware. It allows users to monitor and remotely control a Jetson board using natural language commands over a network, particularly for edge AI, robotics, and IoT applications.

## Features
- MCP (Model Context Protocol) server for NVIDIA Jetson boards
- Enables natural language monitoring and remote control of Jetson devices from clients on the same network
- Uses the FastMCP library to provide the server functionality
- Can be run as a background service managed by systemd for reliability
- Supports manual running for testing and development
- Provides tools for retrieving hardware and software information from the Jetson device
- Network-based communication over configurable port (default 8000)
- Includes installation and setup scripts for ease of deployment
- Supports firewall configuration guidance for network access

## Installation
- Recommended to run as a systemd service on the Jetson device
- Includes setup scripts for creating and enabling the service
- Instructions provided for finding device IP/hostname and configuring firewall rules
- Can be run manually via Python for testing purposes

## Pricing
No pricing information provided; Jetson MCP is available as open source software on GitHub.

## Tags
`jetson` `iot` `edge` `llm`