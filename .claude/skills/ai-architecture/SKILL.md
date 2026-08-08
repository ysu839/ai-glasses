---
name: ai-architecture
description: Design and evolve the AI glasses system architecture. Use when planning components, interfaces, data flow, state management, or major refactors.
---
# AI Architecture
- Inspect the existing repository before changing architecture.
- Prefer small modular components with explicit interfaces.
- Preserve working behavior unless a change is justified.
- Document data flow, ownership, failure modes, and latency-sensitive paths.
- Separate perception, world state, reasoning, interaction, hardware, and infrastructure layers.
- For major changes, propose the design and verification plan before implementation.
