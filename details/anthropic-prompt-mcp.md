# Anthropic Prompt MCP

**Category:** AI Integration MCP Servers  
**Tags:** prompt-management, anthropic, ai-integration, open-source

## Description
Anthropic Prompt MCP is a server that provides tools for interacting with Anthropic's prompt engineering APIs. It enables users to generate, improve, and templatize prompts, supporting the integration of prompt management features into other platforms.

## Features
- **Prompt Generation API:** Programmatically generate prompts based on a provided description and task.
- **Prompt Improvement:** Enhance and refine prompts for better results (experimental).
- **Templatize Prompts:** Tools to structure prompts for reuse and adaptability.
- **API Authentication:** Uses API key authentication scoped to a workspace for secure access.
- **Experimental/Beta Features:** Access to closed research preview APIs for advanced prompt engineering.
- **Flexible Beta Versioning:** Specify multiple API beta versions via headers.
- **Usage Metrics:** Response includes detailed usage statistics, such as token counts and tool request numbers.
- **Response Format:** Returns message objects compatible with the Anthropic Messages API, facilitating easy integration.
- **Model Agnostic:** Optional parameter to specify the model for which the prompt is intended.
- **System Prompts:** Directions and context can be included in messages; future updates may support system field population.

## Pricing
No public pricing information is provided. Access to the prompt tools API is currently by request as part of a closed research preview.

## Source
[Anthropic Prompt MCP Documentation](https://docs.anthropic.com/en/api/prompt-tools-generate)