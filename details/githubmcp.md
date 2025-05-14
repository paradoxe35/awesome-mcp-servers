# Githubmcp

[Source Code](https://github.com/stephanj/githubmcp)

## Description
Githubmcp is a Model Context Protocol (MCP) server that integrates with GitHub's API, enabling repository management, issue tracking, pull request handling, and code manipulation via natural language commands. It is designed to expose GitHub operations as tools for Large Language Models (LLMs) through the MCP protocol, allowing AI systems to interact with GitHub in a controlled manner.

## Features
- **Repository Management**: Create, update, and manage GitHub repositories.
- **Issue Management**: Create, update, and track issues in repositories.
- **Pull Request Management**: Create, review, and manage pull requests.
- **Branch Management**: Create, list, and manage branches within repositories.
- **Commit Management**: View and manage commits within repositories.
- **Content Management**: Access and modify repository content/files.
- **Exposed as MCP Tools**: All operations are available as tools for LLM agents through the MCP protocol.
- **Supports Multiple Clients**: Usable with clients like Claude Desktop and DevoxxGenie IDEA plugin.
- **Environment Variable Authentication**: Authentication with GitHub via environment variables for ease and security.
- **Supports Both GitHub.com and GitHub Enterprise**: Can be configured to access enterprise GitHub instances via environment variable.
- **STDIO or Web Server Operation**: Can be run as a standard input/output (STDIO) server or as a web server.
- **Service Classes**: Modular services for repository, issue, pull request, branch, commit, and content management.

## Pricing
No pricing information is provided. The project is open source and licensed under the MIT License.

## Tags
- github
- repository-management
- mcp
- natural-language
- integration