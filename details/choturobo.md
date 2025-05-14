# Choturobo

**Category:** AI Integration MCP Servers  
**Source:** [Choturobo on GitHub](https://github.com/vishalmysore/choturobo)

## Overview
Choturobo is an MCP (Model Context Protocol) server that enables integration of Arduino-based robotics—specifically using the NodeMCU ESP32 or Arduino Nano 368 boards—with AI assistants, such as Claude AI from Anthropic. It allows control of physical components (LEDs, motors, servos, sensors, etc.) through a simple interface, making it possible to command hardware remotely via mobile or web applications.

## Features
- **Supports Multiple Hardware Platforms:**
  - NodeMCU ESP32 (wireless, Wi-Fi enabled)
  - Arduino Nano 368 (wired via USB)
- **Two Operating Modes:**
  - **Wired Mode (Arduino Nano 368):**
    - Code uploaded via USB
    - No network support; runs pre-uploaded instructions
  - **Wireless Mode (ESP32):**
    - Wi-Fi enabled web server
    - Supports real-time commands via REST API or WebSocket
- **AI Integration:**
  - Compatible with MCP framework from Claude Anthropic
  - Allows AI assistants to control hardware components
- **Remote Control:**
  - Send commands from mobile or computer
  - Real-time interaction with hardware
- **Component Support:**
  - LEDs, motors, servos, fans, sensors, and more
- **Extensible Command Set:**
  - Move, set speed, turn, etc., through natural language or API commands
- **Cross-Language Server Compatibility:**
  - Can be controlled via TypeScript or Java Spring-based MCP servers
- **Debugging Tools:**
  - MCP Inspector for debugging and monitoring
- **Open for Future Expansion:**
  - Framework can be extended for more advanced AI-based robotics and IoT applications

## Example Commands
- "Move Chotu forward by 5 steps."
- "Set speed to 10."
- "Turn Chotu left."

## Requirements
- **Hardware:** NodeMCU ESP32 or Arduino Nano 368
- **Software:** Node.js, Johnny-Five library

## Pricing
No pricing information is provided; the project appears to be open source.

## Tags
`mcp` `hardware` `ai-integration` `iot`
