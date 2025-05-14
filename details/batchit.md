# Batchit

[Batchit](https://playbooks.com/mcp/ryanjoachim-batchit) is an open-source MCP server that enables batching of multiple Model Context Protocol (MCP) tool calls into a single request, reducing token usage and network overhead for AI agents.

## Features
- **Batch Execution**: Aggregate multiple MCP tool calls into a single `batch_execute` request.
- **Parallel Execution**: Run multiple operations simultaneously, with configurable concurrency via `maxConcurrent` option.
- **Error Handling**: Option to stop remaining operations if one fails (`stopOnError`).
- **Timeout Control**: Set timeout limits for the entire batch using `timeoutMs`.
- **Connection Caching**: Reuses connections to downstream MCP servers for efficiency.
- **Single Target Server Per Batch**: Each batch call is directed to one MCP server.
- **Consolidated Results**: All operation responses are returned together at the end of the batch.
- **Installation via Git**: Clone and run with TypeScript/Node.js.
- **Compatible with Cursor**: Can be added globally or per project in Cursor environments.

### Limitations
- No data passing between operations within a batch; dependent operations require separate batch calls.
- Each batch references only a single target MCP server.
- All results are returned together at the end of the batch.

## Usage Examples
- **Reading multiple files in one batch**
- **Creating directories and writing multiple files based on prior operations (requires phased requests)**

## Category
mcp-middleware-orchestration

## Tags
batching, orchestration, ai-agent, open-source

## Pricing
No pricing information is provided; Batchit is open-source.

## Source
[GitHub repository](https://github.com/ryanjoachim/mcp-batchit)