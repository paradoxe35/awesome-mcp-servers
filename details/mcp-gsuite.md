# mcp-gsuite

**Category:** API Integration MCP Servers  
**Tags:** mcp, google-workspace, gmail, calendar

A Multi-Service MCP server to integrate with Gmail and Google Calendar, allowing interaction with Google Workspace products via a unified protocol.

---

## Features

### General
- Supports integration with multiple Google accounts.

### Gmail Integration
- Retrieve Gmail user information.
- Flexible search for emails (e.g., unread, by sender, date range, with attachments).
- Retrieve complete email content by ID.
- Retrieve multiple emails at once by their IDs.
- Create new draft emails (specify recipients, subject, body, CC).
- Delete draft emails.
- Reply to existing emails (send immediately or save as draft).
- Save multiple attachments from emails to the local system.

### Google Calendar Integration
- Manage multiple calendars.
- Retrieve calendar events within specified time ranges.
- Create calendar events with:
  - Title, start/end times
  - Optional location and description
  - Optional attendees
  - Custom timezone support
  - Notification preferences
- Delete calendar events.

### Authentication & Configuration
- Uses OAuth2 for authenticating with Google APIs.
- Supports configuration of custom paths for OAuth credentials and account files.
- Allows managing multiple environments or sets of credentials.
- Stores credentials locally for each account after first login.

### Development & Debugging
- Provides commands and configurations for building, distributing, and publishing the package.
- Supports debugging via MCP Inspector and by viewing server logs.

### Platform Support
- Integration with Claude Desktop (macOS and Windows) via configuration files.

---

## Pricing

No pricing information is provided. The project is open source and distributed under the MIT license.

---

## Source
- [GitHub Repository](https://github.com/MarkusPfundstein/mcp-gsuite)