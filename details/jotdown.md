# JotDown

**Source:** [https://github.com/Harry-027/JotDown](https://github.com/Harry-027/JotDown)

**Category:** Project Management MCP Servers

**Tags:** mcp, notion, notes, documentation

---

## Description

JotDown is a Model Context Protocol (MCP) server written in Rust that enables large language models (LLMs) to interact with Notion for page creation and updating, as well as generate complete mdBooks from structured content. It is designed to streamline content management and publishing workflows by integrating LLM-generated content directly into Notion and mdBook projects.

---

## Features

- **Notion Integration:**
  - Automatically create or update Notion pages with LLM-generated content.
  - Store structured content such as articles and documents directly in Notion.
- **mdBook Generation:**
  - Generate and manage mdBooks from structured content.
  - Automatically create required files like `SUMMARY.md`, `README.md`, and chapter markdown files.
  - Manage book structure and navigation links in `SUMMARY.md`.
- **MCP Support:**
  - Leverages the Model Context Protocol to maintain conversational context for more intelligent and consistent content creation and updates.
- **LLM Tools Provided:**
  - Notion Page Tool: For creating/updating Notion pages from LLMs.
  - mdBook Tool: For generating entire markdown books with chapters and structure from LLM content.

---

## Installation

- **Prerequisites:**
  - Rust (install from rust-lang.org)
  - Notion API Token (internal integration secret)
  - Claude Desktop or any other MCP client (e.g., Cline, Continue)
- **Steps:**
  1. Clone the repository: `git clone https://github.com/Harry-027/JotDown && cd jotdown`
  2. Build the project: `cargo build --release`
  3. Install mdBook CLI: `cargo install mdbook`
  4. Set up Notion integration and configure your MCP client with the Notion token.

---

## License

MIT License

---

## Pricing

No pricing information is provided. JotDown is an open-source project licensed under MIT.