# AWS KB

[Source Code](https://github.com/sammcj/mcp-aws-kb)

## Description
AWS KB is an MCP server that enables users to retrieve information from AWS Knowledge Bases using Retrieval-Augmented Generation (RAG) via the Bedrock Agent Runtime. It allows querying AWS Knowledge Bases and returns both raw context and structured RAG sources.

## Features
- **Retrieval-Augmented Generation (RAG):** Retrieve context from AWS Knowledge Bases based on a query and Knowledge Base ID.
- **Multiple Results Retrieval:** Option to retrieve a customizable number of results (default is 3).
- **Flexible Output:** Returns both raw context (text) and structured results (JSON) with metadata (id, fileName, snippet, score).
- **AWS Credentials Support:**
  - Supports configuration using IAM Access Keys (with optional session token for temporary credentials).
  - Supports AWS SSO (Single Sign-On) credentials.
- **Default Knowledge Base IDs:**
  - Optionally specify one or more default Knowledge Base IDs via environment variable.
- **Easy Integration:**
  - Can be run via Docker, NPX, or directly from a cloned/built repository.
  - Example configurations for integration with Claude Desktop and other MCP-compatible systems.
- **Open Source:** Licensed under the MIT License.

## Usage
- Configure AWS credentials using either IAM Access Keys or AWS SSO.
- Specify Knowledge Base IDs as needed.
- Run the server using Docker, NPX, or Node.js.
- Supports flexible integration and deployment options.

## Pricing
- **Free and Open Source:** Licensed under the MIT License; no pricing plans.

## Tags
`aws` `rag` `knowledge-base` `bedrock`