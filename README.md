# Coding-agent evaluation work: portfolio

Freelance work evaluating frontier AI coding agents on hard software-engineering tasks for AI training data platforms, Jun 2026 to Oct 2026.

| | |
|---|---|
| Tasks | **59** distinct engineering tasks |
| Runs | **219** evaluation runs, counting re-runs, alternative runs and QA revisions |
| Languages and stacks | Python (40), Rust (5), Kotlin (3), TypeScript (3), Mixed (3), C (3), C++ (3), JavaScript/Node.js (2), Godot (GDScript) (1), Erlang/OTP (1) |
| Task types | New system build (35), Feature in existing codebase (9), Migration / porting (6), Performance optimisation (4), Debugging / root-cause analysis (3), Code comprehension (2) |

> **Confidentiality.** This repository records the scope and method of the work only. Task specifications, prompts, model outputs, code, rankings, client names and platform material are not included, because they are covered by confidentiality obligations. Task titles are given so the range of work can be seen.

## What the work involved

In each task I drove two AI coding agents, side by side, through a multi-stage engineering problem in a real or realistic codebase. Then I judged which one did better, and why, with evidence.

1. **Task design and gating.** I broke each problem into milestones with objective pass conditions: builds, tests, numerical outputs, performance budgets, files that must not change.
2. **Multi-turn prompting.** I wrote and sent the prompts for each milestone, including probes, redirects and corrections when an agent claimed success it had not earned.
3. **Verification.** I ran the agents' code and tests myself to check claims against actual behaviour, and recorded the evidence: screenshots, logs, outputs, diffs.
4. **Comparative ranking.** I ranked the two agents per milestone and overall, with a written rationale tied to the evidence.
5. **Annotation and QA.** I completed structured annotation forms and revised them through reviewer QA rounds, keeping version notes per run.
6. **Tooling.** I used Python and shell checks to validate prompts and annotations before submission, and coding agents throughout my own workflow.

## Machine-learning, data and numerical tasks

- Real-time EMG Gesture Onset Detector (Python)
- Migrate Perception Pipeline from Titan to Coral Framework (Python)
- Add Synchronized Graph Scheduler for Asynchronous Multi-Sensor Pipeline (C++, Python)
- Add Tune VMAF Support with Unsharp Filtering in SVT-AV1 Encoder (C)
- Dynamic Congestion Charge System with Rate Lock-in, Fairness Cap, and Rebate (Python)
- Geodesic Heat Method in Rust (Rust)
- Generate ASCII Architecture Diagrams for score_sde (Python)
- A-B Test Lift Analysis with Mid-Experiment Upsizing (Python)
- Ad Delivery Optimizer with User Sentiment Simulation (Python)
- Vacation Property Platform: SQL to pgvector Hybrid Migration for AI Auto-Reply (PostgreSQL/pgvector)
- NCAA D3 Dual Meet Swim Lineup Optimizer (Python)
- Stock Dividend Schedule Estimator (Python)
- Build a Prompt Optimization Comparison Framework with Hybrid Strategy (Python)
- Add OpenTelemetry Distributed Tracing to Stable-Baselines3 (Python)
- Add Data Models, API Schema, and Gemini Client to Fake News Detector (Python)
- Build a Data Placement Library (Python)
- Path Tracing CLI with Rust and WGPU (Rust)
- Build an Image Forensics CLI with EXIF Analysis, ELA, and Tampering Detection (Python)
- Home Service Daily Dispatch Optimizer (Python)

## Most-iterated tasks

- Add a Plugin System with Runtime Toggling to json-server: 23 runs, Jul 2026 to Oct 2026
- Add JSON-to-JSON Reference Support to SMAX Mocks: 19 runs, Jul 2026 to Oct 2026
- A-B Test Lift Analysis with Mid-Experiment Upsizing: 13 runs, Jul 2026 to Oct 2026
- Add Aggregated Bucket Support to Social Feed Generator: 13 runs, Aug 2026 to Sep 2026
- Add swift package why Subcommand to SwiftPM: 10 runs, Jul 2026 to Oct 2026
- Add Retry-Backoff Policies to Dexto Orchestration Layer: 8 runs, Jul 2026 to Oct 2026

## All tasks

See [TASKS.md](TASKS.md) for the full list.
