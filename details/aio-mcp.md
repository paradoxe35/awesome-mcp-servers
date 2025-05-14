# Aio MCP

**Category:** Development Tools / MCP Servers  
**Tags:** integration, developer-tools, workflow, open-source

[Source Code / Project Page](https://github.com/athapong/aio-mcp)

---

## Description

Aio MCP is an open-source Model Context Protocol (MCP) server that unifies multiple developer services and tools into a single platform. It features AI-powered search, Retrieval-Augmented Generation (RAG), and integrates with popular development and productivity tools such as GitLab, Jira, Confluence, YouTube, and Google AI. The server is designed to streamline and enhance development workflows by providing a rich set of utility tools accessible via various modes (stdio and SSE/HTTP).

---

## Features

- **Multi-Service Integrations:**
  - GitLab: Manage projects, merge requests, commits, pipelines, user events, repositories, etc.
  - Jira: Issue management (create, update, search, transition), sprint management, status listing.
  - Confluence: Search, get, create, update, and compare pages.
  - YouTube: Manage videos (list, get details, update), fetch transcripts.
  - Google Calendar: Create, list, update, respond to events.
  - Google Chat: List spaces, send messages.
  - Gmail: Search emails, move to spam, manage filters and labels.

- **AI & RAG Capabilities:**
  - AI-powered search (Google AI Search).
  - Web search using Brave Search API.
  - Retrieval-Augmented Generation (RAG): Index and search content/files in memory; manage vector collections.
  - Deepseek Reasoning: Multi-step problem solving and critical analysis via AI.
  - Sequential Thinking Tool: Dynamic, reflective problem-solving and thought process management.

- **Development Tools:**
  - Safe command-line script execution (sandboxed, timeout, cross-platform).
  - Fetch web content from HTTP/HTTPS sources.
  - Tool manager: Enable/disable tools dynamically.
  - Tool use planner: Plan execution strategies using available tools.

- **Server Modes:**
  - Stdio mode (default): Communicates via standard input/output.
  - SSE (Server-Sent Events) mode: Runs as HTTP server for real-time communication with web clients.

- **Configurability:**
  - Tools can be enabled/disabled via environment variables.
  - Interactive installation/setup via Smithery or Go.

---

## Installation

- Install via Smithery (with interactive CLI setup).
- Install via Go (`go install`) with environment configuration.

---

## Pricing

*No pricing or commercial plans are specified; Aio MCP is open-source and publicly available on GitHub.*

---

## Source

[https://github.com/athapong/aio-mcp](https://github.com/athapong/aio-mcp)
