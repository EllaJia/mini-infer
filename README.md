# mini-infer

Async inference serving platform - queue, fault tolerance, observability. Stepping stone to vLLM-backed production serving.

## Architecture
```mermaid
flowchart 

```

## Task State Machine
Pending -> Queued -> Running -> Completed

## Roadmap
- [ ] Phase 1: submit -> queue -> worker -> poll
- [ ] Phase 2: heartbeat, timeout, retry
- [ ] Phase 3: batch + metrics
- [ ] Phase 4: load test + vLLM backend

