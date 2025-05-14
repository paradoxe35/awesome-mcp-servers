# mcp-git-ingest

**Source:** [https://github.com/adhikasp/mcp-git-ingest](https://github.com/adhikasp/mcp-git-ingest)

**Category:** repository-code-analysis-mcp-servers

**Tags:** mcp, git, repository, code-analysis, ai-integration

---

## Description

mcp-git-ingest is a Model Context Protocol (MCP) server designed for reading and analyzing GitHub repositories, particularly to support version control data analysis with LLMs (Large Language Models). It enables programmatic exploration of repository structures and the extraction of key files.

---

## Features

- **GitHub Repository Structure Analysis**: Provides a tree-like, Unicode-based visual representation of a repository's directory structure.
- **Important File Reading**: Reads and returns the contents of specified important files within a repository.
- **MCP Server Implementation**: Uses `fastmcp` for creating the MCP server interface.
- **Git Operations**: Leverages `gitpython` to clone and interact with repositories.
- **Deterministic Temporary Directory Creation**: Creates a hash-based temporary directory for each repository, allowing possible reuse and easier cleanup.
- **CLI Tool**: Can be run directly as a command-line tool or configured via `pyproject.toml`.
- **Error Handling**: Robust error handling with descriptive messages and guaranteed cleanup of temporary directories.
- **Performance Optimizations**: Avoids recloning by checking for existing repositories, and ensures no accumulation of temporary files.
- **Flexible Configuration**: Can be configured with custom commands and arguments.
- **Python 3.8+ Support**: Requires Python 3.8 or higher.

---

## Technical Details

- **Key Functions**:
  - `clone_repo(repo_url)`: Clones a repository into a deterministic temporary directory.
  - `get_directory_tree(path)`: Recursively generates a visual directory tree.
  - `github_directory_structure(repo_url)`: Combines cloning and directory tree generation.
  - `github_read_important_files(repo_url, file_paths)`: Reads and returns the contents of specified files.
- **Dependencies**: `fastmcp`, `gitpython`, Python 3.8+.
- **License**: MIT

---

## Pricing

No pricing information is provided; mcp-git-ingest is open source under the MIT license.

---