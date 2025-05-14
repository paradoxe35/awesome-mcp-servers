# mcp-agent

**Source:** [https://github.com/lastmile-ai/mcp-agent](https://github.com/lastmile-ai/mcp-agent)

**Category:** mcp-middleware-orchestration

**Tags:** ai-agent, middleware, mcp, open-source

---

mcp-agent is an open-source, Python-based framework for building effective AI agents using the Model Context Protocol (MCP). It provides simple, composable patterns for constructing robust, production-ready agent applications that can interact with various MCP servers and expose their tools to large language models (LLMs).

## Features

- **Composable Agent Framework:** Build AI agents by chaining together simple workflow patterns. Agents can access a set of MCP servers and expose their tools to LLMs.
- **MCP Server Management:** Handles the lifecycle of MCP server connections, simplifying integration and orchestration.
- **Workflow Patterns:** Implements all workflow patterns from Anthropic's "Building Effective Agents" (e.g., Augmented LLM, Parallel, Router, Intent-Classifier, Orchestrator-Workers, Evaluator-Optimizer) and OpenAI's Swarm pattern in a model-agnostic way.
- **Multi-Agent Orchestration:** Supports collaborative multi-agent workflows and human-in-the-loop operations.
- **Augmented LLMs:** Enhance LLMs with tools and memory from connected MCP servers. Supports both OpenAI and Anthropic models.
- **Router and Intent Classification:** Route tasks to the most relevant agents or servers, using embedding or LLM-based classification.
- **Evaluator-Optimizer Loops:** Implement iterative refinement and quality control using separate evaluator and optimizer agents.
- **Orchestrator-Workers Pattern:** Automatically parallelizes steps and manages dependencies between agent tasks.
- **Swarm Pattern:** Reference implementation for multi-agent orchestration, model-agnostic and composable with other workflows.
- **Human Input and Signaling:** Pause/resume workflows for human input or external signals, supporting human-in-the-loop tasks.
- **App Configuration:** Flexible YAML-based configuration for servers, logging, execution, and LLM providers.
- **Persistent and Managed Server Connections:** Fine-grained control over server connection lifecycles, supporting both ephemeral and persistent connections.
- **MCP Aggregator:** Aggregate multiple MCP servers into a single interface, exposing all tools to LLMs with optional namespacing.
- **Example Applications:** Includes ready-to-use examples such as Gmail agent, RAG chatbot, Swarm-based customer support, Streamlit and Marimo integrations.
- **Open Source and Extensible:** Contributions are welcomed. Licensed under Apache-2.0.

## Example Use Cases
- Multi-agent collaborative workflows
- Human-in-the-loop processes
- Retrieval-Augmented Generation (RAG) pipelines
- Automated evaluation and optimization loops
- Custom AI agent applications with file, web, or email access via MCP servers

## Pricing

mcp-agent is open source and free to use under the Apache-2.0 license.

## License

[Apache-2.0](https://github.com/lastmile-ai/mcp-agent#Apache-2.0-1-ov-file)

## Resources
- [GitHub Repository](https://github.com/lastmile-ai/mcp-agent)
- [Documentation & Examples](https://github.com/lastmile-ai/mcp-agent#readme-ov-file)

---

**Note:** mcp-agent is under active development and welcomes contributions from the community.