# Knowledge Graph Memory by Anthropics (Graphiti)

**Source:** [Graphiti: Knowledge Graph Memory for a Post-RAG Agentic World](https://neo4j.com/blog/developer/graphiti-knowledge-graph-memory/)

## Overview
Knowledge Graph Memory, also known as Graphiti, is an MCP server designed to provide real-time, dynamic, and temporally-aware contextual memory for agentic AI systems. Built on Neo4j, it enables developers to track relationships between data entities, maintain continuity across sessions, and manage evolving data in complex projects.

## Features
- **Real-Time, Incremental Updates**: Continuously ingests and integrates new data episodes (events/messages) without requiring batch recomputation of the entire knowledge graph.
- **Temporally-Aware Knowledge Graph**: Tracks both when events occur and when they are ingested, maintaining explicit validity intervals for each relationship (t_valid, t_invalid).
- **Conflict Resolution with Temporal Metadata**: Uses temporal information to update or invalidate outdated knowledge, preserving historical accuracy and enabling historical queries.
- **Handles Multiple Data Types**: Supports ingestion of chat histories, structured JSON, and unstructured text, allowing unified or multiple graphs within a single setup.
- **Fast Query Retrieval**: Achieves low-latency (P95 ~300ms) retrieval using hybrid search (semantic embeddings, BM25 keyword search, direct graph traversal) without requiring LLM calls at query time.
- **Scalable Indexing**: Utilizes vector and BM25 indexes for near-constant time access to nodes and edges, regardless of graph size.
- **Custom Ontology and Entity Types**: Automatically generates ontologies and supports the definition of custom, domain-specific entities using Pydantic models.
- **Historical Query Capability**: Enables users to reconstruct the state of knowledge at any point in time or analyze data evolution.
- **Unified Context for Agents**: Provides a continuously updated, unified memory layer for agentic applications, improving context management and continuity.

## Use Cases
- Autonomous AI agents requiring dynamic, up-to-date memory
- Applications where data changes frequently
- Scenarios needing accurate historical state reconstruction
- Complex workflows and multi-session interactions

## Pricing
No pricing information is provided in the available content.

## Tags
- knowledge-graph
- memory
- context-management
- developer-tools

## Category
ai-integration-mcp-servers

---
**Note:** For technical details and implementation, see the [original blog post](https://neo4j.com/blog/developer/graphiti-knowledge-graph-memory/) and related resources.