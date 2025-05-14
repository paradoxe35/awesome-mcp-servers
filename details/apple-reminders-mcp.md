# apple-reminders-mcp

A Model Context Protocol (MCP) server for AI assistants to manage Apple Reminders on macOS, featuring a TypeScript API for reminders management.

## Features
- **MCP Server:** Provides a server implementing the Model Context Protocol for interacting with Apple Reminders.
- **AppleScript Integration:** Uses AppleScript to communicate with the Apple Reminders app on macOS.
- **Standardized API:** Exposes MCP tools for reminder management, including:
  - `getLists`: Retrieve all reminder lists.
  - `getReminders`: Fetch reminders from a specific list.
  - `createReminder`: Create new reminders.
  - `completeReminder`: Mark reminders as completed.
  - `deleteReminder`: Delete reminders.
- **TypeScript SDK:** Built with TypeScript and the MCP SDK for extensibility.
- **Configurable:** Can be configured for use with AI assistants such as Claude Desktop.
- **Open Source:** Licensed under the MIT license.

## Requirements
- macOS (uses AppleScript to interact with Reminders app)

## Pricing
- Free and open source (MIT License)

## Source
[https://github.com/shadowfax92/apple-reminders-mcp](https://github.com/shadowfax92/apple-reminders-mcp)