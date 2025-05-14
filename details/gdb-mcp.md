# gdb-mcp

A GDB/MI protocol server based on MCP, providing remote debugging capabilities with AI assistants.

- **Source:** [https://playbooks.com/mcp/signal-slot-gdb](https://playbooks.com/mcp/signal-slot-gdb)
- **Category:** Testing & Debugging Tools
- **Tags:** mcp, gdb, debugging, ai-integration

## Features

- **Remote Debugging with AI Assistants:** Integrates with AI assistants (e.g., Claude) to provide GDB debugging functionality via a conversational interface.
- **GDB/MI Protocol Support:** Acts as a server for the GDB Machine Interface protocol.
- **C/C++ Program Debugging:** Enables debugging of C/C++ programs, including breakpoint setting, code stepping, memory examination, and call stack viewing.
- **Session Management:**
  - `gdb_start`: Start a new GDB session
  - `gdb_terminate`: Terminate an active session
  - `gdb_list_sessions`: List all active GDB sessions
- **Program Control:**
  - `gdb_load`: Load a program into GDB
  - `gdb_attach`: Attach to a running process
  - `gdb_load_core`: Load a core dump file
- **Execution Control:**
  - `gdb_continue`: Continue program execution
  - `gdb_step`: Step program execution
  - `gdb_next`: Step over function calls
  - `gdb_finish`: Execute until the current function returns
- **Inspection Commands:**
  - `gdb_backtrace`: Show call stack
  - `gdb_print`: Print value of an expression
  - `gdb_examine`: Examine memory
  - `gdb_info_registers`: Display processor registers
  - `gdb_set_breakpoint`: Set a breakpoint
- **Generic GDB Command:**
  - `gdb_command`: Execute arbitrary GDB commands
- **Integration with Editors:**
  - Can be configured for use with editors like Cursor via their MCP server configuration (globally or per-project)
- **TypeScript Implementation:**
  - Developed in TypeScript, available as an npm package.

## Installation & Configuration

- Clone the repository and install dependencies using npm.
- Configure as an MCP server in your AI assistant or editor (such as Claude or Cursor).

## Pricing

No pricing information provided.
