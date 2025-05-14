# HF Trending MCP

An MCP server designed to track trending AI models, datasets, and spaces on Hugging Face. It provides tools and prompts for fetching trending content, searching specific items, and analyzing current trends.

**Source:** [https://github.com/kukapay/hf-trending-mcp](https://github.com/kukapay/hf-trending-mcp)

## Features
- **Trending Tools:** Retrieve the top trending models, datasets, and spaces on Hugging Face with customizable limits.
- **Search Functionality:** Search trending items by query across models, datasets, or spaces.
- **Trend Analysis Prompt:** Built-in prompt to analyze and summarize current AI trends on Hugging Face.
- **API Tools:**
    - `get_trending_models(limit)`: Fetch trending models with downloads, likes, and tags.
    - `get_trending_datasets(limit)`: Fetch trending datasets with downloads, likes, and tags.
    - `get_trending_spaces(limit)`: Fetch trending spaces with likes, SDK info, and tags.
    - `search_trending(query, type, limit)`: Search trending items by query and type (models, datasets, spaces).
    - `analyze_trends()`: Guides the analysis of trending items with a structured prompt.
- **MCP Server Architecture:** Follows the Model Context Protocol server design for integration and extensibility.

## Installation
- Clone the repository: `git clone https://github.com/kukapay/hf-trending-mcp.git`
- Install dependencies: `pip install mcp[cli] httpx`
- Configure an MCP client to connect to the server.

## Usage Examples
- Fetch top N trending models, datasets, or spaces.
- Search for trending items by keyword or type.
- Analyze and summarize current trends using built-in prompts.

## License
MIT License

## Pricing
No pricing information is provided. The project is open source under the MIT License.