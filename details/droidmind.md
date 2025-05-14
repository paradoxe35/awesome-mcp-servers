# droidmind

[Source on GitHub](https://github.com/hyperb1iss/droidmind)

**Category:** Testing & Debugging Tools  
**Tags:** mcp, android, automation, ai-integration

---

## Description
DroidMind is a tool that allows AI assistants to control, debug, and analyze Android devices using the Model Context Protocol (MCP) over ADB in a secure, structured way. It enables natural language device interaction, suitable for agentic coding workflows where assistants can build and debug directly on real devices.

---

## Features
- **Device Control:** Connect to Android devices over USB or TCP/IP, run shell commands, reboot devices.
- **System Analysis:** Inspect device properties, view hardware info, analyze system logs.
- **File System Access:** Browse directories, read/write files, manage files on devices.
- **Visual Diagnostics:** Capture device screenshots for analysis and debugging.
- **App Management:** Install, uninstall, start, stop, and clear app data for applications on devices.
- **Multi-Device Support:** Control and switch between multiple connected devices.
- **UI Automation:** Automate UI interactions (taps, swipes, text input, key presses).
- **App Inspection:** View app manifests, shared preferences, and app-specific logs.
- **Security Framework:** Command validation, risk assessment, input sanitization, protected system paths, comprehensive command logging, suspicious pattern detection, and ADB command security.
- **MCP Integration:** Works with AI assistants such as Claude, Cursor, Cline, and others via the MCP protocol.
- **Resource Endpoints:** Extensive set of MCP resources for device listing, property fetching, log retrieval, file system operations, app data access, etc.
- **CLI Tools:** Tools for device listing, property fetching, log analysis, file operations, app management, device rebooting, screenshot capturing, bug report generation, heap dumps, and more.
- **Example AI Queries:** Provides sample queries for AI assistants to perform device operations, retrieve logs, analyze device status, manage apps, and automate UI.
- **Development Support:** Uses UV for dependency management, supports testing, linting, and type checking.

---

## Security Features
- **Command Validation:** All shell commands are checked against an allowlist.
- **Risk Assessment:** Commands categorized by risk level (SAFE to CRITICAL).
- **Command Sanitization:** Prevents command injection.
- **Protected Paths:** Critical system paths are protected from modification.
- **Comprehensive Logging:** All commands are logged with risk levels.
- **Suspicious Pattern Detection:** Blocks potentially dangerous commands.
- **ADB Command Security:** Special handling and async validation for ADB commands.
- **User Warnings:** High-risk commands display warnings, critical ones are blocked unless explicitly overridden.

---

## Requirements
- Python 3.13+
- Android device with USB debugging enabled
- ADB installed and in PATH
- UV package manager (recommended)
- For network: ADB over TCP/IP enabled on device

---

## Installation & Usage
- Clone the repo and install dependencies with UV.
- Run the server (`droidmind --transport sse`) to connect AI assistants via MCP.

---

## License
Apache-2.0

---

## Pricing
No pricing information is provided; DroidMind appears to be open source and free to use under the Apache-2.0 license.