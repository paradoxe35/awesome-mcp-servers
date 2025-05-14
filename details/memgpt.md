# MemGPT

**Description:**
MemGPT is an open-source, modular MCP-aligned server/framework designed for building custom memory agents with a hybrid of vector and symbolic memory. It is ideal for developers who require full control over their MCP server setup and agent logic. MemGPT originated as a research project and is now integrated into the Letta framework, which supports creating advanced stateful agents.

## Features
- **Memory Management:** Dynamically moves data in and out of the LLM's context window to efficiently manage memory.
- **Memory Hierarchy:** Divides agent memory into in-context (core) and out-of-context (archival) memory, similar to virtual memory in operating systems.
- **Self-Editing Memory via Tool Calling:** The agent can edit its own memory using designated tools, allowing updates to both agent persona and user information.
- **Multi-Step Reasoning with Heartbeats:** Supports sequential multi-step reasoning where the agent can request additional processing cycles (heartbeats) to continue complex thought processes.
- **Chat-Focused Core Memory:** Separates core memory into agent persona and user information, enabling dynamic updates and personalization.
- **Vector Database Archival Memory:** Uses vector databases (e.g., Chroma, pgvector) for long-term memory storage; can be swapped for other database types or even flat files.
- **Modular Architecture:** Allows for the creation of custom agent architectures, including multi-threaded agents (e.g., conscious and subconscious threads) and advanced memory types (e.g., task memory).
- **REST API Exposure:** Agents can be deployed as services accessible over REST APIs, supporting integration into other AI applications.
- **Open Source:** Freely available for modification and integration.

## Pricing
No pricing information is provided; MemGPT is open-source.

## Links
- [Documentation & Concepts](https://docs.letta.com/concepts/memgpt)