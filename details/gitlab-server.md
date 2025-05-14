# gitlab-server

[Source Code](https://github.com/yoda-digital/mcp-gitlab-server)

## Overview
**gitlab-server** is a Model Context Protocol (MCP) server enabling robust integration with the GitLab API. It provides tools for interacting with GitLab repositories, issues, merge requests, wikis, group projects, and project events via natural language and supports both stdio and Server-Sent Events (SSE) transports. The server is implemented in TypeScript and is available as an npm package.

---

## Features
- **Transport Support**: Operates via stdio (default) or SSE transport.
- **Strict TypeScript Typing**: Uses the MCP SDK for robust type safety.
- **Comprehensive GitLab API Integration**:
  - **Repository Operations**: Search, create, and fork repositories.
  - **File Operations**: Read, create, update single or multiple files.
  - **Branch Operations**: Create new branches.
  - **Issue Management**: Create, list, and filter issues.
  - **Merge Requests**: Create, list, and filter merge requests.
  - **Group Projects**: List projects within a GitLab group.
  - **Project Events**: Retrieve recent project activities/events.
  - **Commit History**: Access commit logs with filtering.
  - **Member Management**: List project and group members (including inherited members).
  - **Wiki Management**:
    - Project and group wiki support (list, get, create, edit, delete pages)
    - Wiki attachment handling
    - Multiple wiki formats supported: markdown, rdoc, asciidoc, org
- **Configuration**: Supports environment variables for access tokens, GitLab API URL, port, and transport selection.
- **Available as NPM Package**: Installable via npm or directly runnable via npx.
- **Open Source**: MIT licensed.

### Supported Tools/Operations
- `search_repositories`, `create_repository`, `fork_repository`, `list_group_projects`
- `get_file_contents`, `create_or_update_file`, `push_files`
- `create_branch`
- `create_issue`, `list_issues`
- `create_merge_request`, `list_merge_requests`
- `get_project_events`, `list_commits`
- `list_project_members`, `list_group_members`
- `list_project_wiki_pages`, `get_project_wiki_page`, `create_project_wiki_page`, `edit_project_wiki_page`, `delete_project_wiki_page`, `upload_project_wiki_attachment`
- `list_group_wiki_pages`, `get_group_wiki_page`, `create_group_wiki_page`, `edit_group_wiki_page`, `delete_group_wiki_page`, `upload_group_wiki_attachment`

---

## Installation & Usage
- **Install via npm**: `npm install @yoda.digital/gitlab-mcp-server`
- **Run from source**: Clone repo, `npm install`, `npm run build`, then `npm start`
- **Run with npx**: `npx @yoda.digital/gitlab-mcp-server` (requires GitLab personal access token)

### Configuration
- `GITLAB_PERSONAL_ACCESS_TOKEN` (required)
- `GITLAB_API_URL` (optional, defaults to https://gitlab.com/api/v4)
- `PORT` (optional, for SSE)
- `USE_SSE` (optional, set to 'true' for SSE transport)

---

## License
MIT License

---

## Tags
mcp, gitlab, repository-management, natural-language

## Category
project-management-mcp-servers