# dify-plugin-mcp-server

- **Category:** MCP Middleware Orchestration
- **Tags:** mcp, dify, plugin, workflow
- **Source:** [CSDN Blog Post](https://blog.csdn.net/wwwzhouhui/article/details/147315045)

## Description
`dify-plugin-mcp-server` is a Dify plugin that transforms a Dify application (either a workflow or chatflow) into a Model Control Protocol (MCP) server. This allows external MCP client tools (such as Cursor, Cherry Studio, or 魔搭社区 MCP-Playground) to directly access and utilize custom Dify workflows as callable services. The plugin is contributed by the Dify community and is available in the Dify plugin marketplace.

## Features
- **Turns Dify Apps into MCP Servers**: Any Dify workflow or chatflow can be published as an MCP server endpoint.
- **External Access**: Once configured, external MCP-compatible clients can make requests to the Dify workflow via HTTP (GET/POST) endpoints.
- **Flexible App Selection**: Choose any existing Dify application (chat or workflow) to expose as a server.
- **App Input Schema Configuration**: Define the JSON input schema for the app, specifying required parameters and their types for external clients.
- **Network Configuration**: Supports configuration for internet or LAN access by adjusting the `.env` file (e.g., updating EXPOSE_PLUGIN_DEBUGGING_HOST and ENDPOINT_URL_TEMPLATE).
- **Multiple Endpoints**: Can create multiple MCP server endpoints for different Dify apps.
- **Integration Examples**: Demonstrated working with tools like Cherry Studio and 魔搭社区 MCP-Playground for end-to-end validation.
- **Supports Both Chatflow and Workflow Types**: Can expose both types of Dify applications.
- **Works with Third-Party Storage**: For output files (like PPT), supports integration with third-party platforms (e.g., Tencent COS) to generate publicly accessible download links.
- **Monitoring**: Invocation records can be viewed within the Dify workflow dashboard.

## Usage Steps
1. Install the plugin from the Dify plugin marketplace.
2. Configure the plugin (update `.env` for network access, restart Dify).
3. In the plugin UI, create a new MCP server endpoint:
   - Set endpoint name, app, app type, and input schema.
4. Save configuration and note the endpoint URLs (GET/POST).
5. Test with MCP-compatible clients (e.g., Cherry Studio, 魔搭社区 Playground).

## Example Endpoints
- 即梦AI绘画: `http://14.103.204.132/e/boaavozuvj5w3dk9/sse`
- 儿童故事绘本-ppt chatflow: `http://14.103.204.132/e/56uageiwt2ezf8e9/sse`

## Pricing
No pricing information is provided in the available content. The plugin appears to be community-contributed and available via the Dify plugin market.
