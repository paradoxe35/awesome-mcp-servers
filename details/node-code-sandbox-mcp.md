# node-code-sandbox-mcp

[Source Code](https://github.com/alfonsograziano/node-code-sandbox-mcp)

## Description
node-code-sandbox-mcp is a Node.js server implementing the Model Context Protocol (MCP) that runs arbitrary JavaScript code in ephemeral, isolated Docker containers. It supports on-the-fly npm dependency installation and clean teardown of containers, making it suitable for secure, repeatable code execution and automation workflows.

## Features
- **Isolated Node.js Sandboxes:** Start and manage disposable Docker containers for secure code execution.
- **Arbitrary Command Execution:** Execute any shell command inside the sandboxed containers.
- **On-the-fly NPM Installation:** Specify and install npm dependencies per job or session.
- **Ephemeral and Session-based Modes:**
  - **One-shot (Ephemeral):** Run a script, capture output (stdout, files), and teardown container automatically.
  - **Session-based:** Initialize a sandbox, run multiple commands/scripts, and teardown manually.
- **ES Module Support:** Execute JavaScript code written as ES modules.
- **File Return:** Files saved by scripts (e.g., images, text files) are automatically returned with the output.
- **Detached Mode:** Option to keep the container running after execution (useful for long-lived services or servers).
- **Resource Limits:** Containers run with controlled CPU and memory constraints for safety.
- **API Tools:**
  - `run_js_ephemeral`: One-shot JS execution with optional dependencies.
  - `sandbox_initialize`: Start a persistent sandbox container.
  - `sandbox_exec`: Run shell commands in a running container.
  - `run_js`: Execute JS code in a persistent sandbox, with dependency management.
  - `sandbox_stop`: Terminate and remove a sandbox container.
- **Docker Integration:** Direct support for Docker, including mounting volumes for file output.
- **VS Code & Claude Desktop Integration:** Example configs and quick install for popular tools.
- **MIT Licensed**

## Prerequisites
- Docker must be installed and running on the host machine.

## Pricing
This is an open-source project released under the MIT License. There are no pricing plans; usage is free.

## Tags
mcp, code-execution, sandbox, nodejs

## Category
code-execution-automation-mcp-servers