# lucidity-mcp

**Source:** [github.com/hyperb1iss/lucidity-mcp](https://github.com/hyperb1iss/lucidity-mcp)

## Description
Lucidity MCP is an open-source Model Context Protocol (MCP) server designed to enhance the quality of AI-generated code. It provides intelligent, prompt-based analysis to help AI coding assistants review code more effectively, identifying and addressing common quality issues. The tool analyzes git changes across multiple software quality dimensions using structured prompts.

## Features
- **Comprehensive Issue Detection:** Analyzes code for 10 critical quality dimensions:
  - Unnecessary Complexity
  - Poor Abstractions
  - Unintended Code Deletion
  - Hallucinated Components (references to non-existent APIs/functions)
  - Style Inconsistencies
  - Security Vulnerabilities
  - Performance Issues
  - Code Duplication
  - Incomplete Error Handling
  - Test Coverage Gaps
- **Contextual Analysis:** Compares code changes against original code to identify unintended modifications.
- **Language Agnostic:** Works with any programming language supported by the AI assistant.
- **Focused Analysis:** Option to target specific issue types based on project needs.
- **Structured Outputs:** Provides actionable feedback with clear recommendations.
- **MCP Integration:** Seamless integration with Claude and other MCP-compatible AI assistants.
- **Lightweight Implementation:** Simple server design with minimal dependencies.
- **Extensible Framework:** Easily add new issue types or refine analysis criteria.
- **Flexible Transport:** Supports both stdio (terminal) and SSE (network) communication.
- **Git-Aware Analysis:** Analyzes changes directly from `git diff` for pre-commit reviews.
- **Logging Options:** Configurable logging behavior depending on transport (console, file, or stderr).
- **Command-line Options:** Customizable server behavior (debug, host/port, log level, etc.).
- **UV Package Manager Support:** Uses UV for dependency management and development workflows.

## Usage
- Analyze git changes for quality issues before committing code.
- Integrate with AI assistants (e.g., Claude) via MCP protocol for automated code reviews.
- Target analysis to specific files or issue types using command-line parameters.

## Prerequisites
- Python 3.13 or higher
- Git
- UV package manager (recommended)

## Development
- Dependency management with UV
- Testing with pytest
- Linting with ruff
- Type checking with mypy

## License
- Apache-2.0 License

## Pricing
Lucidity MCP is free and open source; no pricing plans are mentioned.

## Tags
`mcp` `code-analysis` `quality-assurance` `ai-integration`