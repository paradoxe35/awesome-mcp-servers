# firefly-mcp

[Source Code](https://github.com/gofireflyio/firefly-mcp)

## Description

Firefly MCP is a TypeScript-based MCP (Model Context Protocol) server that bridges to Firefly.ai's cloud infrastructure platform. It enables resource inventory queries and generates Terraform code for cloud resource discovery and management. It integrates with Cloud and SaaS accounts connected to Firefly.

## Features

- **Resource Discovery**: Find any resource in your connected Cloud and SaaS accounts.
- **Resource Codification**: Convert discovered resources into Infrastructure as Code (Terraform).
- **Secure Authentication**: Utilizes `FIREFLY_ACCESS_KEY` and `FIREFLY_SECRET_KEY` for secure communication.
- **Easy Integration**: Works seamlessly with Claude and Cursor, and can be used in natural language workflows.
- **Stdin/Stdout and SSE Support**: Can be run as a local server supporting standard input/output and Server-Sent Events (SSE).
- **Flexible Credential Management**: Supports providing credentials via environment variables or command-line arguments.
- **TypeScript Implementation**: Built primarily in TypeScript, with support for Node.js environments.
- **Open Source**: Licensed under the MIT License.

## Installation & Usage
- Requires Node.js (v14 or higher) and npm or yarn.
- Can be run directly using `npx @fireflyai/firefly-mcp`.
- Credentials are provided via environment variables or arguments.
- Integration with tools like Cursor is possible for natural language resource queries and Terraform code generation.

## Pricing
No pricing information is provided; Firefly MCP is open source and available under the MIT License.

## Category
cloud-devops-mcp-servers

## Tags
`mcp`, `firefly`, `cloud`, `terraform`, `resource-discovery`