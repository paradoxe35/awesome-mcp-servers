# leetcode-mcp-server

An MCP (Model Context Protocol) server enabling automated access to LeetCode's programming problems, solutions, submissions, and user-specific features. Supports both the global (leetcode.com) and China (leetcode.cn) LeetCode sites.

## Features

- **Multi-site support:** Works with both leetcode.com (Global) and leetcode.cn (China).
- **Problem Data Retrieval:** Fetch detailed problem descriptions, constraints, examples, official editorials, and user-submitted solutions.
- **User Data Access:** Retrieve user profiles, submission history, and contest performance.
- **Private Data Access:** (with authentication) Create/query user notes, track problem-solving progress, analyze submission details (AC/WA analysis).
- **Advanced Search:** Filter problems by tags, difficulty, categories, and keywords.
- **Daily Challenge Access:** Fetch current daily challenge problem.
- **Extensive API Tools:**
  - Problems: get daily challenge, get problem details, search problems.
  - Users: get user profile, contest ranking, recent submissions (AC and all), user status, problem submission reports, problem-solving progress, full submission history.
  - Notes (China site only): search, get, create, update notes for problems.
  - Solutions: list community solutions, get full solution content.
- **Resource Endpoints:**
  - Problem categories, tags, supported programming languages, problem details, solution content.
- **Authentication:** Optional LeetCode session cookie for accessing private/user-specific data.
- **Environment/CLI Config:** Supports both environment variables and command-line arguments (with CLI taking precedence).
- **VSCode Integration:** Can be integrated as an MCP server in Visual Studio Code via settings.
- **JSON API:** All tools return structured JSON responses.

## Usage
- Install globally via npm or Smithery CLI.
- Run server with configuration for site (global/cn) and optional authentication.
- Integrate with editors like VSCode via MCP protocol.

## License
MIT License

## Source
[GitHub Repository](https://github.com/jinzcdev/leetcode-mcp-server)