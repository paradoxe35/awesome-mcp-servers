# Filescopemcp

[Filescopemcp](https://github.com/admica/filescopemcp) is a TypeScript-based Model Context Protocol (MCP) server and code analysis tool. It ranks files in your codebase by importance, tracks dependencies, and provides file summaries to help understand and visualize code structure. The tool is designed to integrate with AI assistants and supports multiple programming languages.

## Features

- **File Importance Analysis**: Assigns importance scores (0-10) to each file based on how central it is to your codebase (e.g., how many files import it).
- **Dependency Tracking**: Scans for import statements and language-specific patterns to build a bidirectional dependency graph.
- **Visualization**: Generates diagrams of your codebase structure and dependencies using valid Mermaid syntax and HTML output.
- **File Summaries**: Allows adding and retrieving custom summaries for files to aid understanding.
- **Multiple Project Support**: Can manage and analyze multiple projects.
- **Persistent Storage**: Stores file tree data and analysis results in JSON format for later retrieval and use.
- **File Tree Management**: Builds and maintains a tree representation of your project's files.
- **File Analysis**: Provides detailed information about files, including their relationships and summaries.
- **File Watching**: Monitors for changes in the codebase and updates analysis as files are modified.
- **Automatic Language Support**: Parses popular programming languages such as Python, C, C++, Rust, Zig, and Lua.
- **Integration with AI tools**: Exposes information through Cursor's Model Context Protocol for use with AI assistants.
- **Customizable Diagram Layouts**: Offers options to customize the generated diagrams.
- **Path Normalization**: Handles various path formats for consistent file identification.

## Technical Details
- Written in TypeScript.
- Installation scripts for Windows and Linux.
- Licensed under GNU General Public License v3 (GPL-3.0).

## Pricing

No pricing information is provided; Filescopemcp is open source and available under the GPL-3.0 license.

## Source
[https://github.com/admica/filescopemcp](https://github.com/admica/filescopemcp)