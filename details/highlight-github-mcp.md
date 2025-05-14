# Highlight Github Mcp

**Category:** repository-code-analysis-mcp-servers  
**Tags:** github, code-review, repository, ai-integration

## Description
Highlight Github Mcp is an MCP server designed to extract GitHub Pull Request diffs. It provides tools for AI-driven code review and repository analysis using the Model Context Protocol.

## Features
- **GitHub Integration:** Connects to GitHub to extract diffs from Pull Requests.
- **get_diff_pr Tool:** Retrieves the diff content from a specified GitHub Pull Request.
- **Authentication:** Requires a GitHub Personal Access Token as an environment variable. The token needs `repo` scope for private repositories and `public_repo` scope for public repositories.
- **Error Handling:** Implements standard error handling for API requests.
- **AI-Driven Analysis:** Facilitates AI-powered code review and repository analysis using the extracted diffs.

## Technical Details
- Utilizes the Model Context Protocol (MCP) for its operations.
- Interacts directly with the GitHub API for pull request data.

## Pricing
No pricing information provided; appears to be an open-source project.

## Source
[https://github.com/highlight-ing/highlight-github-mcp](https://github.com/highlight-ing/highlight-github-mcp)