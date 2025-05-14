# Headless Gmail

[Source](https://playbooks.com/mcp/baryhuang-headless-gmail)

## Description
Headless Gmail is an MCP server that provides headless access to Gmail for reading and sending emails. It enables credential separation and allows clients to complete OAuth authentication flows independently, making it well-suited for secure email operations in containerized and automated environments. It operates without requiring local credential setup or browser access and passes credentials as context for operations.

## Features
- Retrieve recent emails from Gmail, including the first 1,000 characters of the body
- Retrieve full email content in 1,000-character chunks using offset parameters
- Send emails via Gmail
- Handle refresh tokens separately and support automatic token refresh
- Decoupled architecture: clients complete OAuth flows and provide credentials as context
- Secure handling: credentials and tokens are managed outside the server process
- Supports reading email metadata (id, threadId, sender, recipient, subject, date)
- Can filter recent emails by max results and unread status
- Retrieve emails by message ID or thread ID
- Chunked retrieval for large emails
- Requires Google API credentials (client ID, client secret, refresh token, access token)
- Provides tools for authentication, token refresh, getting recent emails, retrieving full email bodies, and sending emails
- Docker, NPM, and manual installation options available
- Integration guides for Claude Desktop and Cursor

## Installation Options
- Docker: `docker run -i --rm buryhuang/mcp-headless-gmail:latest`
- NPM: `npm install @peakmojo/mcp-server-headless-gmail`
- Manual: Clone repo and run with Python

## Security Considerations
- Requires Google API credentials. Tokens and credentials should be kept secure and never shared with untrusted parties.

## Category
messaging-mcp-servers

## Tags
mcp, gmail, email, security

## Pricing
No pricing information provided.