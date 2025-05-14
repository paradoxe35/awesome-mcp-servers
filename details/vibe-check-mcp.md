# Vibe Check MCP

**Category:** AI Integration MCP Servers  
**Tags:** mcp, ai-integration, workflow, open-source  
**Source:** [mcpservers.org](https://mcpservers.org/servers/PV-Bhat/vibe-check-mcp-server)

## Description
Vibe Check MCP is an open-source MCP server designed to add a metacognitive oversight layer to AI agent workflows. Its aim is to prevent cascading errors, tunnel vision, scope creep, overengineering, and misalignment in AI-driven coding or workflow scenarios by implementing strategic pattern interrupts and self-improving feedback loops.

## Features
- **Pattern Interrupts:** Uses a "vibe_check" tool to break tunnel vision and force agents to reconsider their approach at planning, implementation, or review phases.
- **Plan Simplification:** Implements "vibe_distill" to anchor and recalibrate workflows, encouraging plan simplification and reducing overengineering.
- **Self-Improving Feedback:** Includes "vibe_learn" for agents to log mistakes and corrections, building a feedback loop to improve future oversight.
- **LearnLM 1.5 Pro Integration:** Uses Gemini API, fine-tuned for pedagogy and metacognition, to enhance complex workflow strategy.
- **API Reference & Documentation:** Complete API documentation, agent prompting strategies, and advanced integration techniques are provided.
- **Easy Installation:** Available via Smithery CLI or manual npm installation. Integrates with Claude Desktop and configurable via environment variables.
- **Open Source:** Licensed under MIT, contributions are welcome.
- **Architecture:** Dual-layer metacognitive design with recursive oversight, phase-resonant interrupts, authority structure integration, anchor compression, and recursive feedback loops.
- **Agent Prompting Guide:** Specific guidelines for integrating with agent prompts for optimal pattern interrupt usage.

## Integration & Setup
- **Smithery CLI:** `npx -y @smithery/cli install @PV-Bhat/vibe-check-mcp-server --client claude`
- **Manual Installation:** Clone repo, install dependencies, build, and start the server using npm.
- **Claude Integration:** Add configuration to `claude_desktop_config.json` and set up `GEMINI_API_KEY` in `.env`.

## Usage Tools
| Tool            | Purpose                                                                                   |
|-----------------|-------------------------------------------------------------------------------------------|
| 🛑 vibe_check   | Pattern interrupt during planning, implementation, or review                              |
| ⚓ vibe_distill | Simplifies and recalibrates complex plans                                                 |
| 🔄 vibe_learn   | Logs mistakes and corrections for self-improving feedback                                 |

## License
MIT

## Pricing
No pricing information provided; the project is open-source under the MIT license.

## Related Links
- [GitHub Repository](https://github.com/PV-Bhat/vibe-check-mcp-server)
- [Technical Reference](https://mcpservers.org/servers/PV-Bhat/vibe-check-mcp-server)

## Documentation
- Agent Prompting Strategies
- Advanced Integration
- Technical Reference
- Philosophy
- Case Studies