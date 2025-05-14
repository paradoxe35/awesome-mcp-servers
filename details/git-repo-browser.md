# Git Repo Browser

**Category:** Repository Code Analysis MCP Servers  
**Tags:** mcp, git, repository, file-browsing, nodejs

## Overview
Git Repo Browser is a Node.js server implementing the Model Context Protocol (MCP) for exploration and analysis of Git repositories. It provides a server interface for various Git operations, making it easier to browse repositories, inspect files, compare branches, and view commit history programmatically.

- **Source:** [Git Repo Browser on Playbooks](https://playbooks.com/mcp/git-repository-browser)
- **GitHub:** [bsreeram08/git-commands-mcp](https://github.com/bsreeram08/git-commands-mcp)

## Features
- **Basic Repository Operations:**
  - **git_directory_structure:** Returns a tree-like ASCII representation of a repository's directory structure.
  - **git_read_files:** Reads and returns contents of specified files from a repository.
  - **git_search_code:** Searches for patterns in repository code with support for file patterns, case sensitivity, and context lines. Returns structured JSON with matching lines and context.

- **Branch Operations:**
  - **git_branch_diff:** Compares two branches and shows files changed, with an optional patch output. Returns commit count and diff summary.

- **Commit Operations:**
  - **git_commit_history:** Retrieves commit history for a branch, with filters for author, date range, and message grep.
  - **git_commits_details:** Fetches detailed commit information including full messages and diffs, with filtering options.
  - **git_local_changes:** Gets uncommitted changes in the local working directory, with status and diffs.

- **Installation & Usage:**
  - Available via npm (`npm install -g git-commands-mcp`) or manual Git clone.
  - Configurable as an MCP server for integration with MCP-compatible clients (e.g., Cursor).
  - Runs on Node.js 14.x or higher and requires Git installed on the system.
  - Communicates via stdio, compatible with MCP clients.

## Requirements
- Node.js 14.x or higher
- Git installed on the system

## Pricing
No pricing information is provided; the package appears to be open source and freely available via npm and GitHub.
