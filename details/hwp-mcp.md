# hwp-mcp

**Category:** file-management-mcp-servers  
**Tags:** mcp, document-management, nodejs, ai-assistant

[Source Code](https://github.com/jkf87/hwp-mcp)

## Description
**hwp-mcp** is a Node.js server implementing the Model Context Protocol (MCP) for controlling Korean word processor (HWP) documents. It enables AI assistants (such as Claude) to automatically create, edit, and manage Hangul documents by providing a specialized MCP server for document workflows.

## Features
- Provides an MCP server to control HWP documents programmatically
- Allows AI models to:
  - Create new Hangul (HWP) documents
  - Insert text into documents
  - Create tables and input data into them
  - Save documents
  - Perform batch operations on documents
- Integrates with AI assistants (e.g., Claude) for automation
- Includes a security module (FilePathCheckerModuleExample.dll) to interact with HWP software and handle file access security dialogs
- Ensures correct data entry into all table cells (previous cursor issues have been resolved)
- Troubleshooting guidance for common integration and connection issues
- Distributed under the MIT License

## Pricing
- Open Source (MIT License)

## System Requirements
- Requires the HWP (Hangul Word Processor) program to be installed and running

## Usage
- Can be integrated with Claude and other AI models to automate HWP document workflows

---
For more details and installation instructions, refer to the [GitHub repository](https://github.com/jkf87/hwp-mcp).