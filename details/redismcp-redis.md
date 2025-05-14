# redis/mcp-redis

**Category:** database-messaging-mcp-servers  
**Tags:** mcp, redis, database, open-source  
**Source:** [https://github.com/redis/mcp-redis](https://github.com/redis/mcp-redis)

## Description
The official Redis MCP Server is a natural language interface designed for agentic applications to manage and search data in Redis efficiently. It integrates with MCP (Model Content Protocol) clients, enabling AI-driven workflows to interact with both structured and unstructured data in Redis using natural language commands.

## Features
- **Natural Language Queries:** Allows AI agents or users to query and update Redis using natural language.
- **Seamless MCP Integration:** Works with any MCP client for smooth communication.
- **Full Redis Data Type Support:** Handles operations on strings, hashes (including vector embeddings), lists, sets, sorted sets, streams, and JSON documents.
- **Search & Filtering:** Supports efficient data retrieval and search operations within Redis.
- **Scalable & Lightweight:** Designed for high-performance data operations.
- **Pub/Sub Functionality:** Supports publish/subscribe messaging for real-time notifications and updates.
- **Stream Tools:** Add, read, and delete from data streams, with support for consumer groups.
- **Vector Index Management:** Query engine tools to manage vector indexes and perform vector searches.
- **Server Management Tools:** Retrieve information about the Redis database instance.
- **JSON Tools:** Store, retrieve, and manipulate JSON documents with path-based access.
- **Flexible Configuration:** Environment variables allow configuration of Redis host, port, authentication, SSL/TLS, and cluster mode.
- **Integration with AI Platforms:** Works with OpenAI Agents SDK and Claude Desktop (via Smithery or manual configuration).
- **Docker Support:** Includes a Dockerfile for containerized deployment.
- **Visual Debugging:** Use MCP Inspector for visual debugging and inspection.

## Example Use Cases
- **AI Assistants:** Enable LLMs to fetch, store, and process data in Redis.
- **Chatbots & Virtual Agents:** Retrieve session data, manage queues, personalize responses.
- **Data Search & Analytics:** Query Redis for real-time insights and lookups.
- **Event Processing:** Manage event streams with Redis Streams.

## Installation & Deployment
- **Manual Installation:** Clone the repository, set up a Python environment, and install dependencies with `uv`.
- **Docker:** Build and run the server as a Docker container.
- **Integration with AI SDKs:** Works with OpenAI Agents SDK and Claude Desktop.

## Configuration
Configurable via environment variables for Redis host, port, username, password, SSL/TLS, and cluster mode.

## License
MIT License

## Pricing
No pricing information provided; the project is open-source under the MIT License.