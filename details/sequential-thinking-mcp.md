# Sequential Thinking MCP

Implements a step-by-step reasoning framework for LLMs, supporting structured problem-solving and complex task execution. Includes implementation by hemangjoshi37a.

- **Source:** [@modelcontextprotocol/server-sequential-thinking on npm](https://www.npmjs.com/package/@modelcontextprotocol/server-sequential-thinking)
- **Category:** ai-integration-mcp-servers
- **Tags:** mcp, llm, reasoning, ai-integration
- **License:** MIT

## Features
- Provides a tool for dynamic and reflective problem-solving through a structured thinking process.
- Breaks down complex problems into manageable steps.
- Allows revision and refinement of thoughts as understanding deepens.
- Supports branching into alternative paths of reasoning.
- Adjusts the total number of thoughts dynamically.
- Generates and verifies solution hypotheses.
- Facilitates detailed, step-by-step thinking for problem-solving and analysis.
- Maintains context over multiple reasoning steps.
- Filters out irrelevant information during analysis.
- Supports planning, design, and tasks where the problem scope may not be initially clear.

### Sequential Thinking Tool Inputs
- `thought` (string): The current thinking step.
- `nextThoughtNeeded` (boolean): Whether another thought step is needed.
- `thoughtNumber` (integer): Current thought number.
- `totalThoughts` (integer): Estimated total thoughts needed.
- `isRevision` (boolean, optional): Whether this revises previous thinking.
- `revisesThought` (integer, optional): Which thought is being reconsidered.
- `branchFromThought` (integer, optional): Branching point thought number.
- `branchId` (string, optional): Branch identifier.
- `needsMoreThoughts` (boolean, optional): If more thoughts are needed.

## Configuration
- Can be integrated with Claude Desktop via configuration in `claude_desktop_config.json` using the npx command.

## Pricing
- No pricing information provided. The package is open source under the MIT License.

## License
MIT License (free to use, modify, and distribute under the license terms).