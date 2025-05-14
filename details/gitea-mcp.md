# gitea-mcp

**MCP Server for interacting with Gitea instances, supporting repository, issue, and pull request management.**

- **Source:** [https://gitea.com/gitea/gitea-mcp](https://gitea.com/gitea/gitea-mcp)
- **Category:** repository-code-analysis-mcp-servers
- **Tags:** mcp, repository-management, git, open-source
- **License:** MIT

---

## Features
- Integrates Gitea with Model Context Protocol (MCP) systems for command execution and repository management via chat interfaces (e.g., Cursor, VSCode, other MCP-compatible interfaces).
- Supports multiple connection modes: `stdio` and `sse`.
- Authentication via command-line arguments or environment variables (with support for Gitea host and access token).
- Debug mode available (with `-d` flag).
- Offers a set of tools for Gitea management:
  - **User Management:**
    - Get information of the authenticated user (`get_my_user_info`)
    - Search for users (`search_users`)
  - **Repository Management:**
    - Create a new repository (`create_repo`)
    - Fork a repository (`fork_repo`)
    - List all repositories owned by the authenticated user (`list_my_repos`)
    - Search for repositories (`search_repos`)
  - **Branch Management:**
    - Create a new branch (`create_branch`)
    - Delete a branch (`delete_branch`)
    - List all branches in a repository (`list_branches`)
  - **Commit Management:**
    - List all commits in a repository (`list_repo_commits`)
  - **File Management:**
    - Get content and metadata of a file (`get_file_content`)
    - Create a new file (`create_file`)
    - Update an existing file (`update_file`)
    - Delete a file (`delete_file`)
  - **Issue Management:**
    - Get an issue by its index (`get_issue_by_index`)
    - List all issues in a repository (`list_repo_issues`)
    - Create a new issue (`create_issue`)
    - Create a comment on an issue (`create_issue_comment`)
  - **Pull Request Management:**
    - Get a pull request by its index (`get_pull_request_by_index`)
    - List all pull requests in a repository (`list_repo_pull_requests`)
    - Create a new pull request (`create_pull_request`)
  - **Organization/Team Management:**
    - Search for teams in an organization (`search_org_teams`)
  - **Server:**
    - Get the version of the Gitea MCP Server (`get_gitea_mcp_server_version`)
- Installation available via official binary releases or building from source (requires Go 1.24+ and make).
- Multi-platform support (arm64 releases available).

---

## Pricing
- **Open Source** (MIT License)
- No pricing plans; free to use.
