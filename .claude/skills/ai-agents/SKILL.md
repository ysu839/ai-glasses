---
name: ai-agents
description: Design tool-using AI agents and reasoning loops for the AI glasses system.
---
# AI Agents
- Define explicit goals, tools, permissions, state, and termination conditions.
- Prefer deterministic workflows for safety-critical actions.
- Never claim a tool action succeeded without evidence.
- Bound retries, tool calls, context growth, and execution time.
- Preserve uncertainty and ask for confirmation before consequential external actions.
- Log enough structured state to debug agent behavior without leaking sensitive data.
