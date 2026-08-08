---
name: ai-glasses-system
description: Master project skill for building the AI glasses system. Use for cross-cutting work involving vision, tracking, world modeling, reasoning, voice, hardware, state, safety, or end-to-end pipeline changes.
---
# AI Glasses System

## Mission
Build a reliable real-time assistive AI glasses system from modular, testable components.

## Architecture boundaries
- Perception: camera input, detection, tracking, OCR and scene understanding.
- World model: structured representation of objects, spatial relations, confidence, and temporal state.
- Reasoning: user intent, contextual interpretation, and response planning.
- Interaction: speech recognition, text-to-speech, controls, and haptics.
- Hardware: cameras, microphones, speakers, sensors, connectivity, and compute adapters.
- Infrastructure: configuration, logging, persistence, APIs, model services, and deployment.

## Engineering rules
1. Inspect existing code and tests before changing anything.
2. Preserve working behavior and existing interfaces unless a change is justified.
3. Separate facts, estimates, uncertainty, and model predictions.
4. Never fabricate sensor readings, detections, distances, actions, or tool results.
5. Keep latency-sensitive paths bounded and observable.
6. Hardware must be replaceable by mocks/simulators for tests.
7. Add regression tests for bugs and behavior changes.
8. Never commit secrets or sensitive user data.
9. Prefer incremental changes over large rewrites.
10. Run tests and report what was actually verified.

## Development loop
Inspect -> plan -> implement -> test -> measure -> review -> document.

For major architecture changes, explain the proposed data flow and failure modes before implementation.
