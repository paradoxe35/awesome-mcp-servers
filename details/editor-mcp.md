# Editor Mcp

[Source Code](https://github.com/danielpodrazka/editor-mcp)

## Category
file-management-mcp-servers

## Description
Editor Mcp is a Python-based text editor server built on FastMCP, designed to provide tools for file operations via a standardized MCP API. It allows for reading, editing, and managing text files through the MCP protocol, with a focus on reliable and accurate code editing, especially for LLMs and AI assistants.

## Features
- **Standardized API:** Provides file operations (read, edit, manage) through an MCP API.
- **Multi-step Editing Workflow:** Enforces a stepwise process (select, overwrite, confirm/cancel) to improve code editing accuracy and reduce errors—especially for LLMs.
- **Context Preservation:** Prevents loss of context after multiple edits by LLMs.
- **Selective Edits:** Avoids resource-intensive rewrites by enforcing line-range based edits.
- **Visual Feedback:** Diff preview system lets users/LLMs verify changes before applying them.
- **Syntax Checking:** Automatic validation for Python and JavaScript/React (JSX) files to prevent committing broken code.
- **Resource Management:** Safeguards to prevent resource exhaustion and ensure system stability.
- **Configurable Environment:** Environment variables allow customization (e.g., max editable lines, syntax check toggles, protected paths).
- **ID Verification System:** Uses SHA-256 to verify that file content hasn't changed between reading and editing, ensuring data integrity.
- **Usage Statistics:** Optionally collects usage data for analysis via DuckDB.
- **13 File Operation Tools:**
    1. set_file – Set the current file
    2. skim – Read full file with line numbers
    3. read – Read specific lines from the file
    4. select – Select a range of lines for editing
    5. overwrite – Prepare to overwrite selected lines
    6. confirm – Commit pending changes
    7. cancel – Discard pending changes
    8. delete_file – Delete current file
    9. new_file – Create a new file
    10. find_line – Search for text in file
    11. find_function – Locate function/method definitions (Python/JS/JSX)
    12. listdir – List directory contents
    13. run_tests/set_python_path – Run Python tests and configure environment
- **Integration:** Designed for use with Claude Desktop and other MCP clients.
- **System Prompt:** Includes a system prompt to guide AI assistants in making manageable, safe edits.
- **Security:** Allows protection of specific paths from access or modification.

## Installation
- **Easy Installation:** Provided install script using UVX (recommended)
- **Manual Installation:** Options for pip, requirements file, or from lock file
- **Prerequisites:** Python, Node.js & Babel (for JS/JSX syntax validation)

## Development & Testing
- Provides a test suite covering all main editing operations.

## Pricing
No pricing information provided; the project is open-source.

## Tags
file-management, editor, python, mcp