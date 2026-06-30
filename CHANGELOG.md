# Changelog

All notable additions to this living survey are documented here. Versions are
date-based (`YYYY.MM`).

## 2026.06 — 2026-06-27

First catch-up release since the original survey 2024.04.
Adds **80 new papers** (81 table rows; one is cross-listed) published
between ~end-2023 and mid-2026, bringing the database from 39 to **120**
references.

### Added

| Section | # Additions |
|---------|:--:|
| Environment Optimization (OQ 2) | 8 |
| Environment Generation for MAPF Algorithm Evaluation *(new)* | 2 |
| Representation for Selection (OQ 3,4) | 3 |
| Enhancing Conflict-Based Search (OQ 5,6) | 3 |
| Enhancing Prioritized Planning (OQ 5,6) | 2 |
| Enhancing other MAPF solvers (OQ 5,6) | 12 |
| Learning-based Policies — Decentralized (OQ 7–12) | 31 |
| Learning-based Policies — Centralized (OQ 7–12) *(new)* | 9 |
| Travel and Action Time Modeling (OQ 13) | 3 |
| Failure Prediction (OQ 14) | 1 |
| Simulation Environments and Testbeds | 4 |
| Interpretable ML for MAPF *(new)* | 1 |
| Surveys & Benchmarks *(new)* | 2 |

By publication year: 2023 × 5, 2024 × 25, 2025 × 28, 2026 × 22.

### New sections
- **Learning-based Policies** (Planning): the former "Learning Decentralized
  Policies" section was renamed and split into **Decentralized** and
  **Centralized** subsections.
- **Environment Generation for MAPF Algorithm Evaluation** (under Representation)
  Environment generation aimed at evaluating/benchmarking solvers.
  This would include research on what it means for an instance to be hard for a solver.
- **Interpretable ML for MAPF**: explainability/policy distillation.
- **Surveys & Benchmarks**: learning-relevant surveys and evaluation studies.
- **Failure Prediction (OQ 14)** is now populated (was nearly placeholder).
- **Simulation Environments** was renamed **Simulation Environments and Testbeds**
  considering that some papers like SMART are meant for better benchmarking.

### Fixed
- **Learn to Follow**: title corrected to the published AAAI 2024 form
  ("...Decentralized Lifelong ... via Planning and Learning") in README and bib.
- **POGEMA**: bib entry replaced (was the 2022 arXiv "grid environment"
  version) with the ICLR 2025 "A Benchmark Platform for Cooperative MAPF" paper,
  matching the README row.
- Pre-existing `references.bib` syntax errors (missing comma after `Kita2023`;
  stray braces in venue macros).
- **From Discrete Plans to Real-World Execution** (REMAP): entry initially
  carried the stale arXiv v1 title ("Bridging Planning and Execution: ...Under
  Real-World Deadlines"); corrected to the current title and the author list
  fixed (the revision added He Jiang).
- **Confidence-Based Curricula**: its Semantic Scholar link initially pointed
  to a *different* 2024 paper ("Confidence-Based Curriculum Learning...");
  repointed to the correct JAAMAS paper.
- **Neural Neighborhood Search for MAPF** (ICLR 2024, Yan & Wu): back-filled
  the missing `references.bib` entry for this pre-existing README row.

### Highlights
- **MAPF-GPT** (AAAI 2025): a transformer foundation model trained on ~1B
  LaCAM observation–action pairs, reported to generalize zero-shot.
  Large-scale imitation learning for decentralized MAPF.
- **Deploying Ten Thousand Robots / SILLM** (ICRA 2025): imitation-learning
  lifelong MAPF scaling to 10,000 agents.
- **Guidance Graph Optimization line**: GGO (IJCAI 2024) -> Online GGO
  (AAAI 2025) -> Mixed-edge GGO (2026): a new sub-area within
  environment optimization.
- **Diffusion models for multi-robot motion planning**: MMD (ICLR 2025),
  SMD (ICML 2025), Discrete-Guided Diffusion (AAAI 2026), and others.
- **Failure Prediction (OQ 14)** receives its first entry ("Should I Replan?",
  learned replanning-timing), an open question that was previously unaddressed.

### Trends (2024–2026, from this update's set)
- Large-scale imitation learning is becoming more of interest for
  decentralized policies (MAPF-GPT, SILLM, CS-PIBT).
- Hybrid ML + classical search is the most active area
  (LNS2+RL, BALANCE, ADDRESS, DiffLNS, HMAGAT, LaGAT, etc..).
- Generative models (diffusion) and LLMs/foundation models appear as less frequent
  but seemingly fast-growing directions.


## 2024.04

The 2024.04 release is a 1-to-1 replica of [the original review paper](https://ieeexplore.ieee.org/abstract/document/10506521)
