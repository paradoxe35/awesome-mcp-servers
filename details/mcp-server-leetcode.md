# mcp-server-leetcode

A Model Context Protocol (MCP) server for LeetCode that enables AI assistants and models to access LeetCode problems, user information, and contest data. It provides fast access to the LeetCode API and supports both CLI and programmable API usage.

**Source:** [GitHub Repository](https://github.com/doggybee/mcp-server-leetcode)

## Features

- **Fast access to LeetCode API via GraphQL**
- **Search and retrieve LeetCode problems**
  - Search by difficulty, tags, limit, and pagination
  - Retrieve daily challenges
  - Fetch specific problem details
- **User data access**
  - Get user profiles by username
  - Fetch user submission history (with limit)
  - Retrieve user contest rankings
- **Contest data access**
  - Get contest details by contest slug
  - Query contest rankings
- **Full MCP tools and resources support**
- **Command-line interface (CLI) and programmable API**
- **Integration support for Claude for Desktop and other AI assistants**
- **Available as an npm package and via Smithery CLI**
- **MIT licensed, open source**

### Provided Tools

**Problem-related:**
- `get-daily-challenge`: Get the daily challenge
- `get-problem`: Get details for a specific problem (by titleSlug)
- `search-problems`: Search for problems (by tags, difficulty, limit, skip)

**User-related:**
- `get-user-profile`: Fetch user information (by username)
- `get-user-submissions`: Get user submission history (by username, limit)
- `get-user-contest-ranking`: Get user contest ranking (by username)

**Contest-related:**
- `get-contest-details`: Get contest details (by contestSlug)

### Resources Format
- `leetcode://daily-challenge`: Daily challenge
- `leetcode://problem/{titleSlug}`: Problem details
- `leetcode://problems{?tags,difficulty,limit,skip}`: Problem list
- `leetcode://user/{username}/profile`: User profile
- `leetcode://user/{username}/submissions{?limit}`: User submissions
- `leetcode://user/{username}/contest-ranking`: User contest ranking

## Installation
- Via Smithery CLI: `npx -y @smithery/cli install @doggybee/mcp-server-leetcode --client claude`
- Global npm: `npm install -g @mcpfun/mcp-server-leetcode`
- Local npm: `npm install @mcpfun/mcp-server-leetcode`

## License
MIT

## Pricing
No pricing information provided; open source under MIT license.

## Tags
mcp, leetcode, ai-integration, coding

## Category
documentation-learning-resources