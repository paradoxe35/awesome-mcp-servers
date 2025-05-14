# swift-mcp-gui

**Category:** Code Execution Automation MCP Servers  
**Tags:** automation, desktop, mcp, open-source, gui

## Description
swift-mcp-gui is an open-source MCP server designed for macOS, providing programmatic control of mouse and keyboard actions. It enables desktop automation by accepting commands from MCP clients and executing them to automate desktop tasks such as moving the mouse, clicking, sending keyboard input, and scrolling.

- **Source:** [https://github.com/NakaokaRei/swift-mcp-gui.git](https://github.com/NakaokaRei/swift-mcp-gui.git)
- **License:** MIT

## Features
- **Mouse Movement**: Move the mouse cursor to specified screen coordinates (`moveMouse`).
  - Input: `x` (double), `y` (double)
- **Mouse Clicks**: Perform mouse clicks at the current cursor position (`mouseClick`).
  - Input: `button` (string: "left" or "right")
- **Keyboard Input**: Send keyboard shortcuts or key combinations (`sendKeys`).
  - Input: `keys` (array of strings, e.g., "command", "shift", "a", etc.)
- **Scrolling**: Scroll in a specified direction by a given number of clicks (`scroll`).
  - Input: `direction` (string: "up", "down", "left", "right"), `clicks` (integer)
- **macOS Support**: Requires macOS 15.0 or later, Swift 6.0+, and Xcode 16.0+.
- **Integration**: Can be integrated into MCP client configurations for desktop automation.

## Installation
- Clone the repository: `git clone https://github.com/NakaokaRei/swift-mcp-gui.git`
- Install with Swift Package Manager: `swift package experimental-install`
- Configure in MCP client as per documentation.

## Security Considerations
- The server has full control over mouse and keyboard. Only connect trusted MCP clients.

## Pricing
- **Free and open-source** (MIT License)