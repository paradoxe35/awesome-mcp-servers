# Cloudtasks MCP

**Category:** cloud-devops-mcp-servers  
**Tags:** mcp, cloud, google-cloud, task-automation

## Description
Cloudtasks MCP is a Model Context Protocol (MCP) server that enables interaction with Google Cloud Tasks queues and tasks. It allows management and handling of Google Cloud Tasks via natural language through Claude Desktop, and serves as an example of using MCP servers for cloud task automation.

## Features
- Provides an MCP server for Google Cloud Tasks
- Enables natural language interaction with Google Cloud Tasks queues and tasks via Claude Desktop
- Supports operations such as:
  - Pausing or resuming a queue
  - Retrieving pending tasks
  - Running a task in a paused queue
- Allows configuration for multiple Google Cloud projects and locations
- Requires service account credentials for each project
- Can be installed using Smithery or manually
- Includes setup and configuration instructions for integration with Claude Desktop

## Installation & Setup
- Install via Smithery for Claude Desktop or manually by installing dependencies and building the project
- Configure `claude_desktop_config.json` with the MCP server details
- Set up `GOOGLE_CLOUD_LOCATION_PROJECTS` with a comma-separated list of location:project-id pairs
- Place service account credential files in the `keys` folder
- Ensure service accounts have appropriate permissions for Cloud Tasks

## Source
[https://github.com/gitskyflux/cloudtasks-mcp](https://github.com/gitskyflux/cloudtasks-mcp)

## Pricing
No pricing information provided; the repository appears to be open source.