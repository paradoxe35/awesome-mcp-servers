# Amazon Bedrock Nova Canvas

**Category:** AI Integration MCP Servers  
**Tags:** mcp, generative-ai, image-generation, aws

## Description
Amazon Bedrock Nova Canvas is a Model Control Protocol (MCP) server that integrates with Amazon Bedrock's Nova Canvas model to provide AI-powered image generation capabilities for MCP-compatible clients.

## Features
- **Image Generation from Text:** Allows creation of images based on text descriptions using Amazon Bedrock's Nova Canvas model.
- **MCP Protocol Support:** Acts as an MCP server, enabling integration with MCP-compatible clients.
- **AWS Integration:** Requires AWS credentials with appropriate permissions for Amazon Bedrock. Credentials can be supplied via environment variables, AWS credentials file, environment variable for active profile, or IAM role when deployed on AWS infrastructure.
- **Claude Desktop Integration:** Can be integrated with Claude Desktop by configuring the settings file (paths provided for MacOS and Windows).
- **Available Tool - generate_image:** Exposes a `generate_image` tool for creating images from text prompts.
- **Prompt Guidelines:** Recommends separating negative concepts (e.g., 'without buildings') into a `negativePrompt` parameter for better results.
- **Performance Considerations:** Image generation time depends on resolution, number of images, and quality settings; higher values may cause longer generation times or timeouts.
- **Example Implementation:** Provides example usage and implementation details.
- **Open Source:** Distributed under the MIT License.

## Pricing
No pricing information is provided; the project is open source under the MIT License. AWS usage fees may apply for Amazon Bedrock services.

## Source
[GitHub Repository](https://github.com/zxkane/mcp-server-amazon-bedrock)