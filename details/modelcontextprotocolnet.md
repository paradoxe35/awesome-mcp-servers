# ModelContextProtocol.NET

A C# SDK for building high-performance Model Context Protocol (MCP) servers on .NET 9, with NativeAOT compatibility. Designed for optimal performance and seamless MCP server implementation.

- **Source:** [Microsoft partners with Anthropic to create official C# SDK for Model Context Protocol](https://devblogs.microsoft.com/blog/microsoft-partners-with-anthropic-to-create-official-c-sdk-for-model-context-protocol)
- **Category:** MCP Middleware Orchestration
- **Tags:** mcp, sdk, dotnet, development

---

## Features

- **Official C# SDK for MCP:** Developed in collaboration between Microsoft and Anthropic, providing a standardized way to integrate MCP into C# applications.
- **Open Source:** Hosted on GitHub under the `modelcontextprotocol` organization, open to community collaboration and contributions.
- **NuGet Package:** Distributed as the `ModelContextProtocol` NuGet package for easy installation.
- **Built for .NET 9:** Leverages modern .NET features, including performance enhancements and NativeAOT compatibility for high efficiency.
- **Supports MCP Protocol Messages:** Implements standard MCP messages, including:
  - InitializeRequest
  - ListToolsRequest
  - CallToolRequest
  - ListResourcesRequest
  - ReadResourceRequest
  - ListPromptsRequest
  - GetPromptRequest
  - PingRequest
  - CreateMessageRequest (LLM sampling with human-in-the-loop)
  - SetLevelRequest (logging control)
- **Extensible and Flexible:** Allows developers to create custom tools and data sources for use with LLMs.
- **Integration with Microsoft Products:** Already supported in products like Copilot Studio, VS Code Copilot agent mode, Semantic Kernel, and more.
- **Sample Projects and Examples:** Includes sample servers (like an Echo server) and usage guides in the repository.
- **Visual Testing Tool:** Compatible with the MCP Inspector tool for interactive development and debugging.
- **Authentication Protocols:** Planned support for OAuth with OpenID Connect and HTTPS, as described in the MCP spec.

---

## Pricing

No pricing information is provided. The SDK is open source and available on GitHub.

---

## Links

- [GitHub Organization](https://github.com/modelcontextprotocol)
- [NuGet Package](https://www.nuget.org/packages/ModelContextProtocol)
