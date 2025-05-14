# Google Calendar MCP

[Source Code](https://github.com/takumi0706/google-calendar-mcp)

## Category

data-access-integration-mcp-servers

## Tags

mcp, google-calendar, calendar, automation

## Description

Google Calendar MCP is a Model Context Protocol (MCP) server that integrates with Google Calendar, allowing AI agents such as Claude Desktop to access, manage, and automate calendar events. It enables natural language interaction to display, create, update, and delete Google Calendar events. It utilizes the Google Calendar API and supports OAuth 2.0 authentication.

## Features

- **Integration with Google Calendar**: Enables AI agents to interact with users' Google Calendars programmatically.
- **Display Events**: Retrieve calendar events with various filtering options.
- **Create Events**: Add new events to Google Calendar, including support for recurring events via the recurrence parameter.
- **Update Events**: Modify existing calendar events, with logic to merge updates and preserve unspecified fields. Supports updating recurrence.
- **Delete Events**: Remove calendar events.
- **Natural Language Support**: Designed for integration with natural language agents, such as Claude Desktop.
- **Authentication**: Supports OAuth 2.0 authentication and allows re-authentication to switch between Google accounts without restarting the agent.
- **Claude Desktop Configuration**: Can be configured via `claude_desktop_config.json` and supports manual authentication mode for environments without localhost access.
- **Published on npm**: Available as the `@takumi0706/google-calendar-mcp` package.
- **Open Source**: Licensed under the MIT License.

## Pricing

No pricing information is provided. The project is open source and available under the MIT License.