# gitlab-mr-mcp

**MCP server for seamless interaction with issues and merge requests in GitLab projects. Illustrates an MCP Server for GitLab.**

- **Repository:** [kopfrechner/gitlab-mr-mcp](https://github.com/kopfrechner/gitlab-mr-mcp)
- **Category:** project-management-mcp-servers
- **Tags:** mcp, gitlab, project-management, issues
- **License:** MIT

---

## Overview

gitlab-mr-mcp is a Model Context Protocol (MCP) server that enables programmatic and AI-driven interaction with GitLab repositories. It is designed to simplify and automate the management of merge requests and issues within GitLab projects.

---

## Features

- **List GitLab Projects:** Retrieve a list of accessible GitLab projects with your token.
- **List Open Merge Requests:** Get all open merge requests for a specific project.
- **Fetch Merge Request Details:** Obtain detailed information about a specific merge request.
- **Fetch Merge Request Comments:** Retrieve all comments (including discussion and diff notes) from a merge request.
- **Add General Merge Request Comments:** Post general comments to merge requests.
- **Add Line-Specific Comments:** Add comments to specific lines in files within a merge request diff.
- **Get Merge Request Diff:** Fetch the diff for a particular merge request.
- **Get Issue Details:** Retrieve detailed information about specific issues in a project.

---

## Installation

- **Using Smithery:**
  - `npx -y @smithery/cli@latest install @kopfrechner/gitlab-mr-mcp --client claude --config '{"gitlabMrMcpToken":"YOUR_GITLAB_TOKEN"}'`
- **Manual Installation:**
  - Requires Node.js, a GitLab access token with API access, and relevant project IDs.
  - Clone repository and run `npm install`.
  - Configure your MCP client as described in the README.

---

## Development

- Set environment variable `MR_MCP_GITLAB_TOKEN` to your GitLab token.
- Can be run with MCP clients and includes support for running with the Model Context Protocol Inspector.

---

## Pricing

This project is open source and released under the MIT license. No pricing plans.

---

## License

MIT

---

## Contribution

Contributions are welcome via pull requests on the GitHub repository.