# opgginc/opgg-mcp

**Category:** data-access-integration-mcp-servers  
**Tags:** gaming, analytics, real-time, ai-integration  
**Source:** [GitHub Repository](https://github.com/opgginc/opgg-mcp)

## Description
OP.GG MCP Server is a Model Context Protocol (MCP) implementation that connects OP.GG gaming data with AI agents and platforms. It provides a standardized interface for AI agents to access real-time gaming data, analytics, esports schedules, and statistics for games such as League of Legends, Teamfight Tactics (TFT), and Valorant.

## Features
- **Standardized AI Integration**: Seamlessly connect OP.GG data with MCP-compatible AI tools and agent frameworks.
- **Remote Server Access**: Simple connection via remote server endpoint (`https://mcp-api.op.gg/mcp/sse`) for immediate data access.
- **Multiple Game Support**: 
  - **League of Legends:**
    - Champion analysis data
    - Champion leaderboard and ranking
    - Esports schedules and team standings
  - **Teamfight Tactics (TFT):**
    - Current meta deck lists
    - Item combinations and recipes
    - Champion item build information
    - Champion recommendations for specific items
    - Playstyle comments for champions
  - **Valorant:**
    - Map meta data
    - Character meta data
    - Regional leaderboards
    - Agent composition by map
    - Character statistics (filterable by map)
    - Player match history by game name and tag
- **Tool Listing and Discovery**: Provides a method for AI agents to list all available tools and data endpoints.
- **Flexible Installation**: Can be installed using Smithery CLI, added to MCP configuration files for platforms like Claude Desktop, or accessed directly via the mcp-remote package.
- **Open Source**: Licensed under MIT.

### Currently Supported Tools
- lol-champion-analysis: Fetch analysis data for a specific champion
- lol-champion-leader-board: Fetch that champion's rank
- esports-lol-schedules: Get upcoming LoL match schedules
- esports-lol-team-standings: Get team standings for a LoL league
- tft-meta-trend-deck-list: Retrieve current meta decks in TFT
- tft-meta-item-combinations: Information about TFT item combinations and recipes
- tft-champion-item-build: Champion item build information in TFT
- tft-recommend-champion-for-item: Champion recommendations for a specific TFT item
- tft-play-style-comment: Playstyle comments for TFT champions
- valorant-meta-maps: Valorant map meta data
- valorant-meta-characters: Valorant character meta data
- valorant-leaderboard: Valorant leaderboard by region
- valorant-agents-composition-with-map: Agent composition data for a Valorant map
- valorant-characters-statistics: Character statistics for Valorant (optionally by map)
- valorant-player-matches: Valorant player match history

## Pricing
No pricing information is provided; the project is open source and licensed under MIT.

## License
MIT License