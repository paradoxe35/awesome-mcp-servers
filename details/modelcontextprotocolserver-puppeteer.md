# modelcontextprotocol/server-puppeteer

A Model Context Protocol (MCP) server that provides browser automation capabilities using Puppeteer. This server enables large language models (LLMs) or other clients to interact with web pages, take screenshots, and execute JavaScript in a real browser environment.

**Source:** [GitHub Repository](https://github.com/modelcontextprotocol/servers/tree/main/src/puppeteer)

## Features

- **Browser Automation:** Automate browser tasks using Puppeteer.
- **Web Navigation:** Navigate to any URL in the browser.
- **Screenshot Capabilities:** Capture screenshots of entire pages or specific elements, with customizable width and height.
- **Element Interaction:**
  - Click elements on the page.
  - Hover over elements.
  - Fill out input fields.
  - Select options in `<select>` elements.
- **JavaScript Execution:** Execute arbitrary JavaScript code in the browser console.
- **Console Log Monitoring:** Access browser console logs in text format.
- **Resource Access:**
  - Retrieve console logs (`console://logs`).
  - Access PNG screenshots by name (`screenshot://<name>`).
- **Deployment Options:**
  - Run as a Docker container (headless Chromium).
  - Run locally using NPX (opens a browser window).

## Tools

- `puppeteer_navigate`: Navigate to a URL.
- `puppeteer_screenshot`: Capture screenshots (customizable by selector, width, height).
- `puppeteer_click`: Click elements by CSS selector.
- `puppeteer_hover`: Hover over elements by CSS selector.
- `puppeteer_fill`: Fill input fields by selector and value.
- `puppeteer_select`: Select options in `<select>` elements by selector and value.
- `puppeteer_evaluate`: Execute JavaScript code in the browser.

## License

Licensed under the MIT License. Free to use, modify, and distribute under the terms of the MIT License.

## Pricing

No pricing information is provided; the project is open source and free to use under the MIT License.