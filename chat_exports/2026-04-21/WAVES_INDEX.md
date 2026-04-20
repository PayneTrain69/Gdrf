# GDRF chat wave exports

This folder stores raw, labeled exports of code snippets produced in the chat.

## Waves currently being exported
- Wave 20 — Parameter Coalition Detection
- Wave 21 — Parameter Negotiation / Arbitration
- Wave 22 — Parameter Reputation System
- Wave 23 — Parameter Maintenance Planner
- Wave 24 — Parameter Contamination Tracking
- Wave 25 — Parameter Capability Packing

## Intended normalized repo paths
- `gdrf/parameters/`
- `gdrf/benchmarks/`
- `tests/`
- patch snippets for:
  - `gdrf/parameters/__init__.py`
  - `gdrf/benchmarks/benchmark_runner.py`
  - `gdrf/debug/query_packet.py`
  - `gdrf/debug/geometry_debugger.py`
  - `gdrf/maturity/registry.py`

## Export convention
- `wave-XX-*.md` files preserve the chat-produced code snippets verbatim or near-verbatim.
- These exports are labeled source captures, not yet guaranteed to be fully merged into a runnable repo tree.
