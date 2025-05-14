# mcp-server-simulator-ios-idb

A Model Context Protocol (MCP) server that enables Large Language Models (LLMs) to interact with iOS simulators through natural language commands. It supports comprehensive control of iPhone and iPad simulators, allowing automation and testing workflows via AI integration.

**Source:** [GitHub Repository](https://github.com/InditexTech/mcp-server-simulator-ios-idb)

## Features

### Simulator Control
- Create, manage, and terminate simulator sessions
- Boot and shutdown simulators
- List available and running simulators
- Focus simulator windows

### Application Management
- Install, launch, terminate, and uninstall iOS applications
- Monitor app states and verify installations
- Handle app permissions and configurations

### UI Interaction & Testing
- Interact with simulator UI (tap, swipe, press buttons)
- Input text and key sequences
- Access and describe accessibility elements
- Record videos of UI interactions

### Development & Debugging
- Capture screenshots and system logs
- Debug applications in real-time
- Monitor and analyze crash logs
- Install dynamic libraries and manage app data

### Advanced Features
- Location simulation
- Media injection (add media to camera roll)
- URL scheme handling (open URLs)
- Contact database management
- Keychain operations (clear keychain)

### Supported Natural Language Commands
- Simulator management: create session, terminate session, list simulators, boot/shutdown simulator, focus window
- App management: install/launch/terminate/uninstall app, list apps, check installation status
- UI actions: tap, swipe, press button, input text, press key/sequence
- Accessibility: describe elements/points
- Capture/logs: take screenshot, record/stop video, get logs
- Debug: start/stop/debug status
- Crash logs: list/show/delete
- Additional: install dylib, open URL, set location, add media, approve permissions, update contacts

### Integration and Usage
- Can be used as a standalone server or as a library
- Integrates with Claude and other LLM assistants via MCP settings
- Usable directly via natural language or programmatically in Node.js projects

### Architecture
- **IDBManager:** Low-level interaction with iOS simulators via idb
- **NLParser:** Parses natural language instructions
- **MCPOrchestrator:** Coordinates commands between parser and IDBManager
- Modular components with adapters for extensibility

### Requirements
- macOS with XCode and iOS simulators
- Node.js v14.0.0 or higher
- Homebrew (for dependencies)

### Installation
- Via [Cline](https://github.com/InditexTech/cline) for automated setup
- Manual installation with git, Python virtual environment, `npm install`, and project build/start commands

### License
- Open source under Apache-2.0

## Pricing
This project is open source and free to use under the Apache-2.0 license.