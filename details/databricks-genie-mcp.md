# databricks-genie-mcp

A server implementing the Model Context Protocol (MCP) to connect with the Databricks Genie API, enabling large language models (LLMs) to ask questions, execute SQL, and interact with Databricks conversational agents.

## Features
- Connects to Databricks Genie API as an MCP server
- Lists Genie spaces available in your Databricks workspace (manual/resource-based)
- Fetches metadata (title, description) of specific Genie spaces
- Starts new Genie conversations using natural language questions
- Supports follow-up questions in ongoing Genie conversations
- Retrieves SQL queries and result tables in structured format
- Available MCP tools/functions:
  - `get_genie_space_id()`: List available Genie space IDs and titles
  - `get_space_info(space_id: str)`: Retrieve title and description of a Genie space
  - `ask_genie(space_id: str, question: str)`: Start a new Genie conversation and get results
  - `follow_up(space_id: str, conversation_id: str, question: str)`: Continue an existing Genie conversation
- Can be integrated with Claude Desktop for conversational data analysis
- Provides Docker support for containerized deployment
- Requires Python 3.7+ and a Databricks workspace with Genie API enabled

## Prerequisites
- Python 3.7+
- Databricks workspace with:
  - Personal access token
  - Genie API enabled
  - Permissions to access Genie spaces and run queries

## Setup
- Clone the repository
- Create and activate a Python virtual environment
- Install dependencies from `requirements.txt`
- Configure `.env` file with Databricks credentials
- Manually add Genie space IDs in the code (due to API limitation)
- Optionally test the server with MCP inspector or Docker

## Security Considerations
- Keep your `.env` file secure
- Use tokens with minimal scope and expiration
- Do not expose the server publicly without authentication

## License
MIT

## Pricing
No pricing information available (open source project).