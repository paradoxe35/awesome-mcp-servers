# Git V2

**Category:** Repository Code Analysis MCP Servers  
**Tags:** mcp, git, repository-management, github, ai-integration

**Source:** [playbooks.com/mcp/sheshiyer-git](https://playbooks.com/mcp/sheshiyer-git)

## Description
Git V2 is an MCP (Model Context Protocol) server that allows AI assistants and applications to interact with Git repositories via a standardized API. It supports a wide range of Git operations, branch and tag management, remote operations, GitHub integration, and batch actions, making it suitable for managing code repositories and enabling collaborative development workflows through automation or AI tools.

## Features
- **Standardized API for Git**: Exposes core Git operations for programmatic and AI-driven access.
- **Basic Git Operations**:
  - Initialize a repository (`init`)
  - Clone repositories (`clone`)
  - Check repository status (`status`)
  - Stage files (`add`)
  - Create commits (`commit`)
  - Push and pull changes (`push`, `pull`)
- **Branch Management**:
  - List branches (`branch_list`)
  - Create, delete, switch branches (`branch_create`, `branch_delete`, `checkout`)
- **Tag Operations**:
  - List tags (`tag_list`)
  - Create and delete tags (`tag_create`, `tag_delete`)
- **Remote Management**:
  - List, add, and remove remotes (`remote_list`, `remote_add`, `remote_remove`)
- **Stash Operations**:
  - List stashes (`stash_list`)
  - Save and apply/remove stashes (`stash_save`, `stash_pop`)
- **Batch Operations**: Perform multiple Git actions in sequence with `bulk_action`.
- **Performance Features**:
  - Repository state caching for faster repeated operations
  - Performance monitoring
  - Smart path handling and resolution
  - Comprehensive error handling with specialized error types
- **GitHub Integration**: Supports GitHub Personal Access Token for repository access and management.
- **Environment Configuration**: Supports environment variables like `GIT_DEFAULT_PATH` and `GITHUB_PERSONAL_ACCESS_TOKEN`.
- **MCP Integration**: Easily addable to Cursor or other MCP-compatible tools for project or global use.

## Installation & Setup
- **Prerequisites**: Node.js, npm, and Git
- **Setup**:
  1. Clone the repository
  2. Install dependencies (`npm install`)
  3. Build the project (`npm run build`)
  4. Configure via MCP settings and environment variables

## Pricing
No pricing information is provided in the available content.
