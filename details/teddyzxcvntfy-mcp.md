# teddyzxcv/ntfy-mcp

**Description:**  
teddyzxcv/ntfy-mcp is an MCP (Model Context Protocol) server designed to send real-time notifications to phones using the ntfy platform. It is intended to notify users when their AI assistant or automated task has completed, providing seamless integration with ntfy for task completion alerts.

**Source:** [https://github.com/teddyzxcv/ntfy-mcp](https://github.com/teddyzxcv/ntfy-mcp)

**Category:** Messaging MCP Servers

**Tags:** mcp, ntfy, notifications, real-time

---

## Features
- **MCP Server Integration:** Acts as a server implementing the Model Context Protocol for task completion notifications.
- **ntfy Notification Support:** Sends notifications to users' phones via the ntfy app, keeping users informed of task completions.
- **Real-time Alerts:** Provides instant updates when an AI assistant or automated process finishes a task.
- **Easy Setup & Configuration:** Simple installation process using npm, with options for manual start or configuration for automated environments.
- **Customizable Topics:** Allows users to specify ntfy topics for tailored notification channels.
- **Auto-approve Commands:** Supports auto-approving certain commands (e.g., `notify_user`) for streamlined workflows.
- **Cross-platform Notifications:** Works with the ntfy mobile app for both Android and iOS.
- **Open Source:** Licensed under Apache 2.0, with code available for customization and self-hosting.
- **Dependencies:** Uses `@modelcontextprotocol/sdk`, `node-fetch`, `dotenv`, and `zod`.

---

## Pricing
- **Open Source:** Free to use under the Apache 2.0 license.

---

## How It Works
- The server runs as a Node.js application.
- When a task is completed by an AI assistant (integrated via MCP), the server sends a push notification through ntfy to the configured topic.
- Users receive notifications on their phones via the ntfy mobile app.

---

## License
- Apache License 2.0
