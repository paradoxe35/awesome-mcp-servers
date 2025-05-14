# mcp-chatgpt-responses

**Category:** ai-integration-mcp-servers  
**Tags:** mcp, ai-integration, chat, web-search

## Description
mcp-chatgpt-responses is an MCP server that allows integration of OpenAI's ChatGPT API with Claude Desktop, enabling conversation and information retrieval between Claude and ChatGPT, including the use of web search for up-to-date information.

## Features
- Access OpenAI's ChatGPT API directly from Claude Desktop.
- Enables conversations between Claude and ChatGPT, supporting long-running discussions.
- Customizable ChatGPT parameters, including model version, temperature, and max tokens.
- Provides web search capabilities, allowing retrieval of current information from the internet.
- Utilizes OpenAI's Responses API for automatic conversation state management, ensuring context is maintained across messages.
- Allows users to use their own OpenAI API key.
- Provides tools:
  - `ask_chatgpt(prompt, model, temperature, max_output_tokens, response_id)`: Send a prompt to ChatGPT and get a response.
  - `ask_chatgpt_with_web_search(prompt, model, temperature, max_output_tokens, response_id)`: Send a prompt to ChatGPT with web search enabled.
- Supports configuration and setup via Smithery for easy installation.
- Written in Python and includes Dockerfile for containerization.

## Setup Requirements
- Python 3.10+
- Claude Desktop application
- OpenAI API key
- `uv` Python package manager

## License
MIT License

## Source
[https://github.com/billster45/mcp-chatgpt-responses](https://github.com/billster45/mcp-chatgpt-responses)

## Pricing
No pricing information provided. (Open source repository; usage of the OpenAI API may incur costs as per OpenAI's pricing.)