# Git Forensics MCP

**Category:** Repository Code Analysis MCP Servers  
**Source:** [GitHub - davidorex/git-forensics-mcp](https://github.com/davidorex/git-forensics-mcp)

## Description
Git Forensics MCP is a specialized Model Context Protocol (MCP) server designed for in-depth analysis of git repositories. It offers detailed insights into repository history, branch relationships, and development patterns, focusing exclusively on git repository analytics.

## Features
- **Branch Overview (`get_branch_overview`)**: Provides a detailed summary and analysis of repository branches.
- **Time Period Analysis (`analyze_time_period`)**: Analyzes repository activity and changes within a specified time frame.
- **File Changes Analysis (`analyze_file_changes`)**: Examines changes to files across the repository, highlighting modifications and trends.
- **Merge Recommendations (`get_merge_recommendations`)**: Offers recommendations for merging branches based on repository analysis.
- **JSON Output**: All analysis tools output results as JSON files for easy integration and processing.
- **MCP Server Integration**: Operates as an MCP service and can be integrated with any MCP-compatible client.

## Technical Details
- Input parameters are required for each analysis tool.
- Results are written to specified output files in JSON format.
- Licensed under the Apache License 2.0.

## Tags
`mcp`, `git`, `code-analysis`, `repository`, `open-source`

## Pricing
- No pricing information provided; the project is open-source under Apache License 2.0.