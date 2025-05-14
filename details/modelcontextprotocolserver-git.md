# modelcontextprotocol/server-git

**Category:** Development Tools / MCP Servers  
**Source:** [GitHub Repository](https://github.com/modelcontextprotocol/servers/tree/main/src/git)

## Description
modelcontextprotocol/server-git is a Model Context Protocol (MCP) server that provides tools for interacting with local Git repositories. It allows reading, searching, and analyzing repositories, as well as performing direct Git operations. Designed for automation and integration with Large Language Models or desktop applications.

## Features
- **Read and Manipulate Git Repositories**: Interact directly with local Git repositories.
- **Git Operations Exposed as Tools:**
  - `git_status`: Shows the working tree status.
  - `git_diff_unstaged`: Shows changes in the working directory not yet staged.
  - `git_diff_staged`: Shows changes that are staged for commit.
  - `git_diff`: Shows differences between branches or commits.
  - `git_commit`: Commit changes to the repository.
  - `git_add`: Stage files for commit.
  - `git_reset`: Unstage all staged changes.
  - `git_log`: View commit logs (with optional maximum count).
  - `git_create_branch`: Create a new branch.
  - `git_checkout`: Switch branches.
  - `git_show`: Show contents of a specific commit.
  - `git_init`: Initialize a new Git repository.
- **Integration with Desktop Apps**: Provides configuration examples for integration with Claude Desktop and Zed.
- **Multiple Installation and Running Methods**:
  - Via [uv](https://github.com/astral-sh/uv) (recommended)
  - Via pip (`pip install mcp-server-git`)
  - Via Docker
- **Debugging and Development Support**: Tools and instructions for debugging and local development, including use of the MCP Inspector.
- **MIT License**: Open source and freely available under the MIT License.

## Installation
- **uv:** No specific install needed; run directly with `uvx`.
- **pip:** Install with `pip install mcp-server-git`, then run with `python -m mcp_server_git`.
- **Docker:** Build and run as a Docker image (`docker build -t mcp/git .`).

## Configuration
- Example configurations provided for Claude Desktop and Zed.
- Supports specifying repository paths and custom arguments.

## Pricing
- **Open Source**: Free to use under the MIT License.

## Tags
`mcp`, `git`, `repository`, `code-analysis`
