# playwright-mcp

Official Microsoft Playwright MCP server, enabling LLMs to interact with web pages using structured accessibility snapshots.

- **Source:** [GitHub Repository](https://github.com/microsoft/playwright-mcp)
- **Category:** Testing & Debugging Tools
- **Tags:** mcp, playwright, browser, automation

## Features

- **Model Context Protocol (MCP) Server:** Provides browser automation using Playwright, optimized for LLM-driven workflows.
- **Structured Accessibility Snapshots:** Enables interaction with web pages using the accessibility tree, not pixel-based input or screenshots.
- **LLM-Friendly:** Operates on structured data, removing the need for vision models.
- **Deterministic Tool Application:** Reduces ambiguity compared to screenshot-based automation.
- **Headless and Headed Modes:** Supports running the browser in headless mode for background/batch operations or in headed mode (including Linux environments without DISPLAY).
- **Client-Server Operation:** Can run as a remote server, connecting via WebSocket endpoint.
- **Tool Modes:**
  - **Snapshot Mode (default):** Uses accessibility snapshots for performance and reliability.
  - **Vision Mode:** Uses screenshots and X/Y coordinate-based interactions (with `--vision` flag).
- **Automation Tools (Snapshot Mode):**
  - `browser_navigate`: Navigate to a URL
  - `browser_go_back`: Go back to previous page
  - `browser_go_forward`: Go forward to next page
  - `browser_click`: Click on web page element
  - `browser_hover`: Hover over element
  - `browser_drag`: Drag and drop between elements
  - `browser_type`: Type text into editable element
  - `browser_press_key`: Press keyboard key
  - `browser_snapshot`: Capture accessibility snapshot
  - `browser_save_as_pdf`: Save page as PDF
  - `browser_wait`: Wait for specified time (up to 10 seconds)
  - `browser_close`: Close the page
- **Automation Tools (Vision Mode):**
  - `browser_navigate`, `browser_go_back`, `browser_go_forward`, `browser_save_as_pdf`, `browser_wait`, `browser_close` (as above)
  - `browser_screenshot`: Capture page screenshot
  - `browser_move_mouse`: Move mouse to coordinates
  - `browser_click`: Click at coordinates
  - `browser_drag`: Drag and drop between coordinates
  - `browser_type`: Type text at coordinates
  - `browser_press_key`: Press keyboard key
- **Use Cases:**
  - Web navigation and form-filling
  - Data extraction from structured content
  - Automated testing driven by LLMs
  - General-purpose browser interaction for agents
- **Open Source:** Licensed under Apache-2.0

## Pricing

This project is open source and available under the Apache-2.0 license. No pricing or paid plans are listed.
