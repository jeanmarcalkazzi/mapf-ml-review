# Contributing to the Living MAPF-ML Review

Thank you for helping keep this survey alive!
Contributions of new papers, corrections, and link fixes are all welcome.

## Adding a paper

1. **Check it's not already listed.** Search the README for the paper title (and common abbreviations).
2. **Pick the right section.** Sections follow the taxonomy of the [original survey](https://ieeexplore.ieee.org/abstract/document/10506521). Rough guide:
   - *Representation*: learned representations of the environment or instance (roadmaps, env optimization/generation, algorithm selection).
   - *Augmenting Existing Solvers*: ML assists a classical solver (CBS, PP, LNS, PIBT, ...). The classical solver produces the solution; ML guides it.
   - *Learning-based Policies*: a learned model produces the actions/paths. Use **Decentralized** for per-agent policies (even if search post-processes their outputs, e.g. CS-PIBT), and **Centralized** for joint/centralized generation (diffusion planners, unified policies, foundation models with global state, e.g., DeepFleet).
   - *Execution*: modeling of real-world dynamics, delays, congestion, uncontrollable agents, or failure/replanning prediction.
   - *Simulation Environments and Testbeds*, *Interpretable ML*, *Surveys & Benchmarks* are self-explanatory.
   - If a paper genuinely spans two sections, list it **once** in the primary section and open an issue if you think a cross-reference is warranted. No duplicate rows please.
3. **Add the row** in reverse-chronological order within its table:

   ```markdown
   | [Paper Title](https://www.semanticscholar.org/paper/<paper-id>) | VENUE | YYYY | [code](...), [project](...) |
   ```

   - **Paper link**: prefer the Semantic Scholar page (stable IDs); OpenReview for workshop papers without an S2 entry.
   - **Venue**: use the acronym (AAAI, ICRA, RAL, ...); `arXiv` for preprints. Update the venue when a preprint gets published.
   - **Links**: full URLs including `https://`. Only include links that work; use `-` if no additional links are relevant.
4. **Add the BibTeX entry** to `references.bib`. Use the key format `FirstAuthorYYYYshortname` (e.g., Alkazzi2024mlmapf) under its relevant section.

## Scope

In scope: papers using machine learning for MAPF or closely related multi-robot navigation/motion planning, plus simulators, benchmarks, and surveys used by this community.  
Out of scope: single-agent path planning (unless it is a widely used MAPF training environment), general MARL papers without a pathfinding component.

