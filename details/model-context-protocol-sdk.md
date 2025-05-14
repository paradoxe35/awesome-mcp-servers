# Model Context Protocol SDK

**Category:** Development Tools / MCP Servers  
**Tags:** mcp, sdk, dotnet, development  
**Source:** [GitHub Repository](https://github.com/modelcontextprotocol/csharp-sdk)

## Description
Model Context Protocol SDK is the official C# SDK for building MCP (Model Context Protocol) servers and clients. Maintained by Microsoft, it enables .NET applications, services, and libraries to implement and interact with MCP-compatible clients and servers. MCP is an open protocol that standardizes how applications provide context to Large Language Models (LLMs), allowing secure integration between LLMs and various data sources and tools.

## Features
- **MCP Client Implementation:**
  - Provides `McpClientFactory.CreateAsync` for creating and connecting MCP clients.
  - Enumerate and invoke available tools on an MCP server from a client.
  - Supports tool invocation and interaction, including LLM tool integrations.
  - Can connect to any MCP-compliant server (not limited to those built with this SDK).

- **MCP Server Implementation:**
  - Provides services for easily creating MCP servers in C#.
  - Register tools using attributes (`McpServerToolType`, `McpTool`) for automatic discovery and registration.
  - Supports tool methods with dependency injection for services like `IMcpServer`, `HttpClient`, etc.
  - Allows exposing prompts via `[McpServerPrompt]` and `[McpServerPromptType]` attributes.
  - Fine-grained configuration of server capabilities and handlers (e.g., custom tool listing and invocation logic).
  - Sample tools and prompts (e.g., Echo tool, SummarizeContentFromUrl tool).

- **Integration & Extensibility:**
  - Designed to be server-agnostic and extensible for custom tools and services.
  - Provides samples and test projects for integration with LLM SDKs and other applications.
  - Supports `.NET` dependency injection and hosting infrastructure.
  - Logging configuration and support for diagnostics.

- **Installation:**
  - Available as a NuGet package (`ModelContextProtocol`).
  - Supports prerelease installation for preview features.

- **Open Source & Licensing:**
  - Licensed under the MIT License.
  - Actively maintained; contributions acknowledged.

## Pricing
- **Free and Open Source** (MIT License)

## Resources
- [NuGet Package](https://www.nuget.org/packages/ModelContextProtocol)
- [Official Documentation](https://github.com/modelcontextprotocol/csharp-sdk)

---
**Note:** The SDK is currently in preview; breaking changes may be introduced without notice.