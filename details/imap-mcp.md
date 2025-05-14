# imap-mcp

A Model Context Protocol (MCP) server for interactive email processing, designed to enable AI assistants (such as Claude) to access, process, and manage email via IMAP servers while learning user preferences.

- **Source:** [https://github.com/non-dirty/imap-mcp](https://github.com/non-dirty/imap-mcp)
- **Category:** mcp-server-directories-lists
- **Tags:** curated-list, directory, mcp, reference

## Features
- **Email Authentication:** Secure access to IMAP servers with multiple authentication methods, including OAuth2 (Gmail supported).
- **Email Browsing:** List folders and messages; filter and search emails across folders.
- **Email Content Handling:** Read message contents (plain text, HTML, attachments).
- **Email Organization:** Move, delete, mark as read/unread, and flag messages.
- **Email Composition:** Draft and save replies with support for both plain text and HTML; reply-all and CC support; proper email threading using headers.
- **Draft Support:** Save email drafts to appropriate folders.
- **Automated Email Summarization & Categorization:** (Planned) Summarize and categorize emails automatically.
- **Learning User Preferences:** (Planned) Record/analyze user decisions to predict future actions and personalize email handling.
- **Interaction Patterns:** (Planned) Structured patterns for processing emails and learning user preferences.
- **Multi-Provider IMAP Support:** Works with any standard IMAP provider (Gmail recommended, others possible).
- **Extensive Documentation:** Includes installation guides, configuration samples, and usage examples.
- **Test Suite:** Includes tests for core components and models.
- **Command-Line Tools:** For listing inbox, managing OAuth2 tokens, and launching the server.
- **Development-Friendly:** Supports virtual environments, development dependencies, and testing via pytest.

## Installation & Usage
- Requires Python 3.8+, `uv` for package management.
- Detailed installation and configuration instructions are provided in the repository.
- Example commands for checking email, starting the server, and managing OAuth2 tokens.

## Security Considerations
- Emphasizes secure credential storage and limited folder access.
- Recommends using app-specific passwords or OAuth2 for authentication.

## Roadmap (Planned Features)
- Advanced search capabilities
- User preference learning
- Multi-account support
- Integration with major email providers

## Pricing
- **Open Source:** No pricing; distributed under the MIT License.

## License
- MIT License

---

**Note:** This is a server implementation, not a directory or list of MCP servers as described in the initial summary.