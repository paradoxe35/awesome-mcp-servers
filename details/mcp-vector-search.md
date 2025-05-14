# mcp-vector-search

**Category:** Data Access Integration MCP Servers  
**Tags:** mcp, semantic-search, vector-database, ai-integration, data-access

## Description
mcp-vector-search is a Model Context Protocol (MCP) server that enables semantic data search using vector embeddings and similarity matching. It facilitates AI-powered, context-aware data retrieval, specifically designed for querying transcript segments stored in a Turso database. Users can ask questions and receive relevant transcript segments, with results ranked by semantic similarity.

## Features
- **Vector similarity search** for transcript segments using embeddings
- **Relevance scoring** based on cosine similarity
- **Transcript metadata** in results (episode title, timestamps)
- **Configurable search parameters:**
  - Limit number of results (default 5, max 50)
  - Minimum similarity score threshold (default 0.5, range 0-1)
- **Efficient database connection pooling** for performance
- **Comprehensive error handling**
- **Performance optimized** for quick responses
- **API endpoint:** `search_embeddings` for semantic search
- **Expects a Turso database** with tables for embeddings and transcripts
- **Complete development workflow** (clone, install, build, run dev, publish)

## API Details
- **Endpoint:** `search_embeddings`
  - **Parameters:**
    - `question` (string, required): Query text
    - `limit` (number, optional): Number of results
    - `min_score` (number, optional): Minimum similarity
  - **Response:** JSON array of results including episode title, segment text, start/end time, similarity score

## Database Schema
Expects a Turso database with two tables:
- `embeddings`: id, transcript_id, embedding (vector)
- `transcripts`: id, episode_title, segment_text, start_time, end_time

## Source Code
[GitHub: spences10/mcp-embedding-search](https://github.com/spences10/mcp-embedding-search)

## Pricing
No pricing information provided; open source under MIT License.