# Raygun MCP

[Source Code](https://github.com/MindscapeHQ/mcp-server-raygun)

## Category
Monitoring

## Tags
raygun, monitoring, error-tracking, mcp

## Description
Raygun MCP is a Model Context Protocol (MCP) server that provides integration with Raygun API V3. It enables interaction with Raygun's Crash Reporting and Real User Monitoring features, supporting outage prediction and alert routing to collaboration platforms through MCP integration.

## Features

### Applications Management
- List all applications under your account
- Get application details by identifier or API key
- Regenerate an application's API key

### Error Management
- List error groups for an application
- Get detailed information about an error group
- Set error group status: resolved, active, ignored, or permanently ignored

### Deployment Management
- List deployments for an application
- Get deployment details by identifier
- Delete a deployment
- Update deployment information
- Reprocess deployment commit data

### User & Session Management
- List customers for an application
- List user sessions for an application
- Get detailed session information

### Performance Monitoring
- List monitored pages for an application
- Get time-series performance metrics for pages
- Get histogram of performance metrics
- Get time-series error metrics

### Source Maps Management
- List source maps for an application
- Get source map details
- Update source map information
- Remove a source map
- Upload a new source map
- Remove all source maps

### Team Management
- List pending team invitations
- Send a new team invitation
- Get invitation details
- Revoke a pending invitation

### Configuration & Integration
- Requires RAYGUN_PAT_TOKEN environment variable for authentication
- Supports optional restriction of source map operations to specific directories
- Designed for use with Claude Desktop and compatible with MCP Inspector debugging tool

## Pricing
No pricing information provided.
