# AWS Lambda MCP Server

A community MCP Server for AWS Lambda that enables serverless cost tracking and automation of Lambda functions from within the MCP ecosystem.

## Features
- **Serverless MCP Deployment:** Deploys MCP (Model Context Protocol) servers on AWS Lambda, leveraging automatic scaling and pay-per-use benefits of serverless infrastructure.
- **MCPEngine Integration:** Uses MCPEngine, an open-source Python implementation of MCP, for compatibility with Lambda's stateless, event-driven model.
- **Streamable HTTP and SSE Support:** Supports streamable HTTP alongside Server-Sent Events (SSE) for real-time interaction, fully compatible with Lambda's request/response paradigm.
- **Stateless and Stateful Tools:** Enables both stateless tool deployment and stateful applications through context management using Lambda's lifespan argument.
- **Built-in Authentication:** Integrates with OpenID Connect (OIDC) providers (e.g., Google, AWS Cognito, Auth0) for production-ready authentication.
- **Dockerized Deployment Workflow:** Supports containerization via Docker and deployment through Amazon Elastic Container Registry (ECR).
- **Function URLs:** Exposes Lambda functions directly over HTTP without requiring API Gateway.
- **Database and Resource Management:** Supports initialization and teardown of external resources (e.g., databases) using async context managers.
- **LLM Client Compatibility:** Allows connection from compatible LLM clients (e.g., Claude, ChatGPT) for real-time tool invocation.
- **Local Proxy Support:** Provides proxy tooling to bridge LLM clients and Lambda MCP server, including handling authentication flows.

## Category
cloud-devops-mcp-servers

## Tags
aws, lambda, cloud, automation, mcp

## Source
[How to Deploy MCP Servers on AWS Lambda](https://apidog.com/blog/howt-to-deploy-mcp-servers-on-aws-lambda/)

## Pricing
No pricing information was provided in the available content.