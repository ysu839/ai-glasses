# AI Glasses System

## Project purpose
Build a reliable, real-time assistive AI glasses software system that can connect perception, world modeling, reasoning, voice interaction, and physical hardware.

## Required workflow
1. Inspect the existing repository before changing code.
2. Identify the smallest safe change.
3. Implement modularly and preserve existing interfaces where possible.
4. Add or update tests for behavior changes.
5. Run relevant tests and report actual results.
6. Document architecture or configuration changes.

## Engineering principles
- Do not fabricate sensor readings, detections, distances, actions, or tool results.
- Preserve uncertainty and confidence explicitly.
- Keep real-time paths bounded and measurable.
- Keep hardware adapters separate from core logic and provide mocks for tests.
- Never commit credentials, API keys, private keys, or sensitive user data.
- Avoid unnecessary rewrites and dependencies.

## Project skills
Use the project skills under `.claude/skills/` when their task matches:
- ai-glasses-system: master cross-cutting rules
- ai-architecture: architecture and design
- python-engineering: Python implementation
- computer-vision: perception and tracking
- ml-inference: model integration and evaluation
- testing: tests and regression coverage
- debugging: root-cause diagnosis
- realtime-performance: latency and resource optimization
- audio-voice: speech and audio interaction
- edge-hardware: physical device integration
- security: secure engineering
- git-workflow: safe version control
- api-backend: backend and service interfaces
- ai-agents: tool-using reasoning systems
- documentation: project documentation

## Definition of done
A change is not complete merely because code was written. It must be tested, integrated with the existing architecture, and honestly reported as verified or unverified.
