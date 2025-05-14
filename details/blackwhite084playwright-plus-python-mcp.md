# blackwhite084/playwright-plus-python-mcp

[Source on GitHub](https://github.com/blackwhite084/playwright-plus-python-mcp)

A Python-based MCP (Model Context Protocol) server using Playwright for browser automation, suitable for LLM integration.

**Category:** Code Execution & Automation / MCP Servers  
**Tags:** playwright, python, browser-automation, llm

---

## Features

### Resources
- Implements a simple note storage system:
  - Uses a custom `note://` URI scheme for accessing individual notes.
  - Each note resource has a name, description, and `text/plain` mimetype.

### Prompts
- Provides a "summarize-notes" prompt:
  - Summarizes all stored notes.
  - Optional `style` argument to control summary detail level (brief/detailed).
  - Generates a prompt combining all current notes with style preference.

### Tools
Implements multiple Playwright-based browser automation tools:
- `playwright_navigate`: Navigates to a specified URL (creates a new session if none exists).
  - Requires `url` (string).
- `playwright_screenshot`: Takes a screenshot of the current page or a specific element.
  - Requires `name` (string) for screenshot file name.
  - Optional `selector` (string) for CSS selector; if omitted, takes full-page screenshot.
- `playwright_click`: Clicks an element using a CSS selector.
  - Requires `selector` (string).
- `playwright_fill`: Fills an input field.
  - Requires `selector` (string) and `value` (string).
- `playwright_evaluate`: Executes JavaScript in the browser console.
  - Requires `script` (string).
- `playwright_click_text`: Clicks an element by its text content.
  - Requires `text` (string).
- `playwright_get_text_content`: Gets the text content of all visible elements.
- `playwright_get_html_content`: Gets HTML content of a page or element.
  - Requires `selector` (string).

### Configuration & Deployment
- Can be configured for development or published server modes.
- Supports integration with Claude Desktop (macOS/Windows).
- Built and distributed via `uv` toolchain; can be published to PyPI.
- Debugging recommended with [MCP Inspector](https://github.com/modelcontextprotocol/inspector).

### License
- Apache-2.0

---

## Pricing
No pricing information provided (open source project).

---

## Quickstart
- Install using the provided configuration for Claude Desktop or run via command line using `uv` or `uvx`.
- Build and publish using `uv` commands (`uv sync`, `uv build`, `uv publish`).
- Set PyPI credentials via environment variables or command-line flags when publishing.

---

## Development
- 100% Python implementation.
- Contributions and issues managed via GitHub.

---