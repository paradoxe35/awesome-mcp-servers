# Ableton MCP

**Category:** Media Processing MCP Servers  
**Tags:** ableton, music, automation, ai-assistant  
**Source:** [playbooks.com/mcp/ahujasid-ableton-live](https://playbooks.com/mcp/ahujasid-ableton-live)

## Description
Ableton MCP is a server that enables AI assistants, specifically Claude AI, to interact with Ableton Live for automated music creation, track editing, and session control through natural language commands. It provides a bidirectional communication system between Claude AI and Ableton Live, allowing for dynamic music production workflows.

## Features
- **Two-way Communication:** Connects Claude AI to Ableton Live via a socket-based server for real-time interaction.
- **Track Manipulation:** Create, modify, and manipulate MIDI and audio tracks.
- **Instrument and Effect Selection:** Load instruments, effects, and sounds from Ableton’s library through AI commands.
- **Clip Creation and Editing:** Create, edit, and trigger MIDI clips with note-level control.
- **Session Control:** Start/stop playback, trigger clips, and control transport functions.
- **Session and Track Information:** Retrieve information about the current Ableton session and tracks.
- **Tempo and Parameter Control:** Change tempo and adjust other session parameters.
- **Integration with Claude Desktop and Cursor:** Works with Claude Desktop and Cursor via configuration files and command-line tools.
- **Remote Script for Ableton:** Requires installing a custom MIDI Remote Script in Ableton’s directories.
- **Example AI Commands:**
  - "Create an 80s synthwave track"
  - "Create a Metro Boomin style hip-hop beat"
  - "Add reverb to my drums"
  - "Set the tempo to 120 BPM"
  - "Play the clip in track 2"

## Requirements
- Ableton Live 10 or newer
- Python 3.8 or newer
- uv package manager
- Claude AI or Cursor integration

## Installation
- Install dependencies (Python, uv)
- Configure Claude Desktop or Cursor with the MCP server
- Install the AbletonMCP Remote Script in the appropriate Ableton Live directory

## Pricing
No pricing information is provided in the available content.

## Additional Notes
- Only one instance of the MCP server should run at a time (either on Cursor or Claude Desktop).
- The MCP server can be added globally or per-project in Cursor.
- Example commands enable a wide range of music production tasks via natural language.

---