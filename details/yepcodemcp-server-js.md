# yepcode/mcp-server-js

**Source:** [https://github.com/yepcode/mcp-server-js](https://github.com/yepcode/mcp-server-js)

**Category:** code-execution-automation-mcp-servers

**Tags:** code-execution, javascript, python, mcp

---

## Description

yepcode/mcp-server-js is an open-source MCP (Model Context Protocol) server that enables AI platforms to interact with YepCode's infrastructure. It allows AI assistants to execute code and manage processes securely and at scale in JavaScript or Python, with support for NPM and PyPI packages, and enables the creation of custom MCP tools.

---

## Features

- **AI Platform Integration:** Allows AI platforms (e.g., Cursor, Claude Desktop) to run and manage YepCode processes as tools accessible to AI assistants.
- **Code Execution:** Securely executes code (JavaScript or Python) in isolated, production-ready environments using the `run_code` tool. Supports runtime options such as language selection and execution context.
- **Process Exposure as Tools:** Exposes YepCode processes as individual MCP tools by tagging them with `mcp-tool`, making them callable by AI assistants.
- **Environment Management:**
  - `set_env_var`: Set environment variables in the YepCode workspace, with optional masking for sensitive values.
  - `remove_env_var`: Remove environment variables from the workspace.
- **Process Execution:**
  - `run_ycp_<process_slug>`: Execute any tagged YepCode process, supporting both synchronous and asynchronous execution modes.
  - `get_execution`: Retrieve the result, logs, and output of a process execution via execution ID.
- **Custom MCP Tools:** Ability to create custom tools based on your YepCode processes.
- **Universal Compatibility:** Works with any AI platform supporting the Model Context Protocol.
- **Multiple Deployment Options:**
  - **Hosted (remote) version:** Obtain a server URL from your YepCode Cloud workspace.
  - **Local installation:** Available via NPX or Docker.
- **MCP Options:**
  - Disable specific tools like `run_code` if needed.
  - Option to skip cleanup of source code after execution for audit purposes.
- **Debugging:** Includes an "MCP Inspector" tool for debugging server interactions via a browser interface.
- **Security:** Executes all operations in isolated environments, suitable for production.
- **MIT Licensed:** Free to use and modify under the MIT license.

---

## Pricing

No pricing information is provided. yepcode/mcp-server-js is open source and licensed under MIT, so there is no charge for the server itself. (Note: Using YepCode Cloud or other infrastructure may be subject to separate terms.)

---

## License

MIT License
