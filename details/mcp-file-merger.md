# mcp-file-merger

**Source:** [GitHub - exoticknight/mcp-file-merger](https://github.com/exoticknight/mcp-file-merger)

## Description
mcp-file-merger is an MCP server utility designed to merge multiple files into a single file. It is intended to help with AI chat length limits and efficient file management. The tool is simple, fast, secure, and provides detailed summaries of merge operations.

## Features
- **Simple usage:** Merge any number of files with a single command.
- **Fast performance:** Efficiently combines files of any size.
- **Secure access:** Only accesses directories that you explicitly allow.
- **Detailed reporting:** Reports file sizes and provides a merge summary.
- **API endpoints:**
  - `merge_files`: Merges files from specified input paths into a single output file, returning success message and details.
  - `list_allowed_directories`: Lists directories the server is permitted to access.
- **Integration:** Can be added as an MCP server for Claude Desktop by updating the configuration.
- **Installation:** Clone the repository, install dependencies, and build with npm.
- **Open source:** Licensed under Apache-2.0.

## Pricing
- **Free and open source** (Apache-2.0 License)

## Tags
file-merging, file-management, mcp, ai-assistant