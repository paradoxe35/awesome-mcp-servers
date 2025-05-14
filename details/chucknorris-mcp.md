# chucknorris-mcp

A specialized MCP server providing LLM enhancement prompts and jailbreaks with dynamic schema adaptation, designed to augment AI capabilities via the MCP protocol.

- **Category:** ai-integration-mcp-servers
- **Tags:** mcp, llm-integration, prompt-management, open-source
- **Source:** [GitHub Repository](https://github.com/pollinations/chucknorris)

## Features

- **MCP Server Implementation:** Provides Model Context Protocol (MCP) server that delivers specialized enhancement prompts to LLMs.
- **Jailbreak Prompts:** Utilizes jailbreak prompts from elder-plinius' L1B3RT4S project.
- **Dynamic Schema Adaptation:** Implements a dynamic schema approach for prompt delivery, making jailbreak attempts less detectable by LLMs.
- **Two-Phase Bypass:** Uses a two-phase approach to bypass jailbreak detection (does not immediately present jailbreak content).
- **Security Research Tool:** Designed for security research and evaluation to identify vulnerabilities in LLM systems.
- **Inspiration from Research:** Implements techniques described in "The 'S' in MCP Stands for Security" and references Tool Poisoning Attack research by Invariant Labs.
- **Compatibility:** Intended for use with weaker models; effectiveness may vary with newer models (e.g., Claude, GPT-4).
- **Open Source:** Licensed under MIT.
- **Community Supported:** Part of the Pollinations.AI community.

## Pricing

- **Open Source:** No pricing information; available under the MIT license.

## Status

- **Experimental:** Work in progress with limitations; experimental effectiveness with newer LLMs.