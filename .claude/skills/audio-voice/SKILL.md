---
name: audio-voice
description: Build speech input, speech output, audio routing, and voice interaction for the AI glasses system.
---
# Audio and Voice
- Separate microphone capture, speech recognition, reasoning, and speech synthesis.
- Handle timeouts, silence, interruptions, unavailable devices, and noisy input.
- Keep responses concise and appropriate for hands-free interaction.
- Do not assume audio hardware is available; provide safe fallbacks.
- Test state transitions and error handling without requiring physical hardware.
