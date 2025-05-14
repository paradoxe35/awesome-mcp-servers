# Base MCP Protocol

[View Specification](https://modelcontextprotocol.info/specification/draft/basic/)

## Description
The Base MCP Protocol defines the standard protocol and architecture for Model Context Protocol (MCP) servers, ensuring universal compatibility and standardized interfaces for AI-powered tool integration. It establishes a modular, extensible foundation for communication between clients and servers in AI applications.

## Features
### Core Protocol
- **JSON-RPC 2.0 Compliance:** All messages between MCP clients and servers adhere to JSON-RPC 2.0.
  - **Requests:** Initiate operations, include unique ID and method name.
  - **Responses:** Reply to requests, include the same ID as the request (can be results or errors).
  - **Notifications:** One-way messages, no reply, must not include an ID.
- **Error Handling:** Errors in responses must include an error code and message.

### Protocol Layers
- **Base Protocol:** Defines core message types and interactions.
- **Lifecycle Management:** Manages connection initialization, capability negotiation, and session control.
- **Server Features:**
  - **Prompts:** Server-side prompt management.
  - **Resources:** Server-exposed resources.
  - **Tools:** Tools exposed by servers for client use.
  - **Utilities:** Includes completion, logging, and pagination utilities.
- **Client Features:**
  - **Sampling:** Mechanisms for sampling data or responses.
  - **Roots:** Directory-like listing of root resources.
- **Utilities:** Cross-cutting concerns such as logging, argument completion, and progress reporting.

### Authorization
- **Auth Framework:** Provides an authorization framework for HTTP+SSE transport.
- **Custom Auth Strategies:** Allows clients and servers to negotiate custom authentication/authorization methods.
- **STDIO Transport:** Uses environment credentials instead of the HTTP+SSE framework.

### Schema
- **TypeScript Schema:** Full protocol specified as a TypeScript schema, serving as the source of truth.
- **JSON Schema:** Automatically generated from the TypeScript source for use with automated tooling.

### Modularity
- **Modular Design:** Implementations can support only the components needed for their application, ensuring flexibility and scalability.
- **Clear Separation of Concerns:** Each protocol layer and component is well-defined and separated.

## Category
Documentation & Learning Resources

## Tags
specification, standardization, protocol, reference

## Pricing
No pricing information is provided; this is a protocol specification and reference documentation.