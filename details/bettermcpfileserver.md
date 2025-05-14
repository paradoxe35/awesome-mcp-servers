# Bettermcpfileserver

A reimagined Model Context Protocol (MCP) server for filesystem access with privacy-preserving path aliases and an optimized API designed for large language models (LLMs) and AI assistants.

## Features

- **Privacy-Preserving Path Aliases**: Maps user-friendly aliases to real filesystem paths, preventing exposure of sensitive directory structures (e.g., `code/src/main.js` instead of `/Users/yourusername/projects/src/main.js`).
- **Optimized LLM-Friendly API**: API is simplified and redesigned to be more intuitive for both AI models and developers.
- **API with Only 6 Functions**:
  1. `writeFile`: Create or update a file with specific content.
  2. `readFileContent`: Read the contents of a file.
  3. `editFile`: Make targeted changes to portions of a file.
  4. `manageFile`: Move, rename, copy, or delete a file.
  5. `manageFolder`: Create, rename, or delete a folder.
  6. `searchFilesAndFolders`: Search for files and folders using glob patterns.
- **Grouped Functionality**: Related operations are consolidated to reduce API complexity and surface area.
- **Efficient Combined Operations**: Designed to reduce round-trips and simplify common tasks.
- **Concise, Purposeful API Descriptions**: Clear and brief function descriptions for easy understanding.
- **Optimized Search Functionality**: Powerful search with optional metadata inclusion for efficiency.
- **LLM-Oriented Design Philosophy**: Focuses on simplicity, privacy, and efficiency, making it ideal for integration with AI assistants.
- **MIT Licensed**: Open source and free to use.

## Pricing

- **Open Source**: Free to use under the MIT License.

## Source

[https://github.com/martinschlott/bettermcpfileserver](https://github.com/martinschlott/bettermcpfileserver)