---
name: realtime-performance
description: Optimize latency, throughput, memory, CPU/GPU usage, and responsiveness for real-time AI glasses workloads.
---
# Real-Time Performance
- Measure before optimizing.
- Track end-to-end latency, frame rate, inference time, queue depth, and resource usage.
- Avoid blocking work on latency-sensitive paths.
- Prefer bounded queues, backpressure, batching only when it improves the target workload, and graceful degradation.
- Keep performance tests reproducible where possible.
