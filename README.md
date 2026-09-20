# Real Time QEC Runtime

## Deadline-Aware Heterogeneous Quantum Error Correction

Research project investigating the real-time classical-compute requirements
of quantum error correction.

The central problem is not simply which decoder executes fastest in isolation.
The project studies how:

- decoder implementation
- CPU/GPU placement
- dispatch
- memory transfer
- batching
- queueing
- workload arrival rate
- contention
- scheduling

combine to determine real end-to-end response time and deadline feasibility.

### Technical areas

- quantum error correction
- surface-code workloads
- Stim
- PyMatching
- CUDA-Q QEC
- modern C++
- CUDA C++
- CPU/GPU heterogeneous computing
- concurrent queues
- scheduling
- batching
- throughput
- tail latency
- deadline analysis
- Nsight profiling
- performance engineering

### Core principle

Fast decoder compute is not automatically equivalent to fast quantum feedback.
