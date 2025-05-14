# flstudio-mcp

An MCP server connecting Claude to FL Studio, enabling AI-driven music composition, instrument control, and live recording, all via the Model Context Protocol.

## Features
- **MCP Server for FL Studio**: Acts as a Model Context Protocol (MCP) server to interface between Claude (an AI assistant) and FL Studio.
- **AI-Driven Music Composition**: Enables Claude to compose music, generate melodies, chords, and drum patterns directly in FL Studio.
- **Instrument Control**: Allows AI to control and record into specific instruments' piano rolls in FL Studio.
- **Live Recording**: Facilitates live recording of AI-generated MIDI data into FL Studio's piano roll.
- **Virtual MIDI Port Support**: Guides users to set up virtual MIDI ports (LoopMIDI for Windows, automatic for Mac) for communication between the server and FL Studio.
- **Custom MIDI Controller Integration**: Uses a 'Test Controller' in FL Studio's MIDI settings to receive AI-generated MIDI data.
- **Cross-platform Support**: Instructions provided for both Windows and Mac setup.
- **Open Source**: The project is open source and contributions are welcome.
- **MIDI Data Handling**: Includes a method for encoding extended MIDI data (e.g., note positions) over standard 7-bit MIDI messages.
- **Community Engagement**: Encourages sharing creations and feature requests via Discord.

## Installation/Setup
- Place the provided Test Controller folder in the appropriate FL Studio directory.
- Set up the MCP server and configure Claude as per the Model Context Protocol documentation.
- Set up virtual MIDI ports and configure FL Studio's MIDI input.
- Install required Python packages with pip.
- Configure the output MIDI port in the server script.

## Source
[https://github.com/veenastudio/flstudio-mcp](https://github.com/veenastudio/flstudio-mcp)

## Category
media-processing-mcp-servers

## Tags
flstudio, music, ai-integration, mcp

## Pricing
No pricing information is provided; the project is open source.