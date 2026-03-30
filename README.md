# A (LIVE) Comprehensive Review on Leveraging Machine Learning for Multi-Agent Path Finding

A living survey tracking Machine Learning approaches to solving the MAPF Problem.


🕐 Last updated: -

📄 [Original Survey (Alkazzi & Okumura - IEEE Access 2024)](https://ieeexplore.ieee.org/abstract/document/10506521)

📚 [All BibTeX](references.bib)

---

## Representation

### Representation for Planning - OQ 1

| Paper | Venue | Year | Links |
|-------|-------|------|:--:|
| [CTRMs: Learning to Construct Cooperative Timed Roadmaps for Multi-Agent Path Planning in Continuous Spaces](https://www.semanticscholar.org/paper/CTRMs%3A-Learning-to-Construct-Cooperative-Timed-for-Okumura-Yonetani/e26cdb91017be4fd83d98ee0a75ce8dcb797464a?sort=pub-date) | AAMAS | 2022 | [code](https://github.com/omron-sinicx/ctrm/), [project](https://omron-sinicx.github.io/ctrm/) |
| [Avoidance Critical Probabilistic Roadmaps for Motion Planning in Dynamic Environments](https://www.semanticscholar.org/paper/Avoidance-Critical-Probabilistic-Roadmaps-for-in-Arias-Ichter/242930b85d5323d3e74395073da44649984c2369) | ICRA | 2021 | - |

### Environment Optimization - OQ 2

| Paper | Venue | Year | Links |
|-------|-------|------|:--:|
| [Arbitrarily Scalable Environment Generators via Neural Cellular Automata](https://www.semanticscholar.org/paper/Arbitrarily-Scalable-Environment-Generators-via-Zhang-Fontaine/0ed66bbc7c30552b80f1e5fcc76ce74816cba5c6) | NeurIPS | 2023 | [code](https://github.com/lunjohnzhang/warehouse_env_gen_nca_public) |
| [Multi-Robot Coordination and Layout Design for Automated Warehousing](https://www.semanticscholar.org/paper/Multi-Robot-Coordination-and-Layout-Design-for-Zhang-Fontaine/98b6f0b58177b679cff92f916abc04eea5cc3a86) | IJCAI | 2023 | [code](https://github.com/lunjohnzhang/warehouse_env_gen_public) |
| [Constrained Environment Optimization for Prioritized Multi-Agent Navigation](https://www.semanticscholar.org/paper/Constrained-Environment-Optimization-for-Navigation-Gao-Prorok/031ffab4164a5a832b603a49c7577e7fabac5316) | IEEE Open Journal of Control Systems | 2023 | - |
| [Environment Optimization for Multi-Agent Navigation](https://www.semanticscholar.org/paper/Environment-Optimization-for-Multi-Agent-Navigation-Gao-Prorok/eb5616b50a2e12f5cc3f8e8bf80e6108d1bd4cbb) | ICRA | 2023 | - |

### Representation for Selection OQ 3,4

| Paper | Venue | Year | Links |
|-------|-------|------|:--:|
| [MAPFASTER: A Faster and Simpler take on Multi-Agent Path Finding Algorithm Selection](https://www.semanticscholar.org/paper/MAPFASTER%3A-A-Faster-and-Simpler-take-on-Multi-Agent-Alkazzi-Rizk/a0e0f528da5e10d68d81b1b64dbf8d36655c345c) | IROS | 2022 | [code](https://github.com/jeanmarcalkazzi/mapfaster) |
| [MAPFAST: A Deep Algorithm Selector for Multi Agent Path Finding using Shortest Path Embeddings](https://www.semanticscholar.org/paper/MAPFAST%3A-A-Deep-Algorithm-Selector-for-Multi-Agent-Ren-Sathiyanarayanan/2cad646b21b172fbfbd62e82208be676c53116d1) | AAMAS | 2021 | [code](https://github.com/USC-ACTLab/MAPFAST) |
| [Algorithm Selection for Optimal Multi-Agent Pathfinding](https://www.semanticscholar.org/paper/Algorithm-Selection-for-Optimal-Multi-Agent-Kaduri-Boyarski/ee2feec737391ea97374c03ac3bdf263cc2a3d7f) | ICAPS | 2020 | [code](https://github.com/OmriKaduri/MAPF-Classification) |
| [Automatic algorithm selection in multi-agent pathfinding](https://www.semanticscholar.org/paper/Automatic-Algorithm-Selection-In-Multi-agent-Sigurdson-Bulitko/ec1393b702c9b530a5edb2959851f65bcd467e3f) | arXiv | 2019 | - |

## Planning

### Augmenting Existing Solvers - OQ 5,6

#### Enhancing Conflict-Based Search

| Paper | Venue | Year | Links |
|-------|-------|------|:--:|
| [Accelerating Multi-Agent Planning Using Graph Transformers with Bounded Suboptimality](https://www.semanticscholar.org/paper/Accelerating-Multi-Agent-Planning-Using-Graph-with-Yu-Li/fca667cf815f5a5c52c2269d81d9f9e7e1ef666c) | ICRA | 2023 | - |
| [Learning Node-Selection Strategies in Bounded-Suboptimal Conflict-Based Search for Multi-Agent Path Finding](https://www.semanticscholar.org/paper/Learning-Node-Selection-Strategies-in-Search-for-Huang-Dilkina/2880dcda763ae53fb3dbc7b0fe0e2e642c7215c4) | AAMAS | 2021 | - |
| [Learning to Resolve Conflicts for Multi-Agent Path Finding with Conflict-Based Search](https://www.semanticscholar.org/paper/Learning-to-Resolve-Conflicts-for-Multi-Agent-Path-Huang-Dilkina/c6a24e9ef8d78128c78406dd33597ad080ce2772) | AAAI | 2021 | (TBF) |

#### Enhancing Prioritized Planning

| Paper | Venue | Year | Links |
|-------|-------|------|:--:|
| [Synthesizing priority planning formulae for multi-agent pathfinding](https://www.semanticscholar.org/paper/Synthesizing-Priority-Planning-Formulae-for-Wang-Bulitko/3c80978256dacf8cbde8cdf56bda8b4fc367c406) | AIIDE | 2023 | - |
| [Learning a Priority Ordering for Prioritized Planning in Multi-Agent Path Finding](https://www.semanticscholar.org/paper/Learning-a-Priority-Ordering-for-Prioritized-in-Zhang-Li/b3df18bc728823eb50fd4b1d1994ad4483777da0) | SoCS | 2022 | - |

#### Enhancing other MAPF solvers 

| Paper | Venue | Year | Links |
|-------|-------|------|:--:|
| [Neural Neighborhood Search for Multi-agent Path Finding](https://www.semanticscholar.org/paper/Neural-Neighborhood-Search-for-Multi-agent-Path-Yan-Wu/f529bd992435763061a51502559db8dd54d0b4aa) | ICLR | 2024 | [code](https://github.com/mit-wu-lab/mapf_neural_neighborhood_search) |
| [Anytime Multi-Agent Path Finding via Machine Learning-Guided Large Neighborhood Search](https://www.semanticscholar.org/paper/Anytime-Multi-Agent-Path-Finding-via-Machine-Large-Huang-Li/81e43d43c6ae0fb9696b39c2d29cc1987a2b58c8) | AAAI | 2022 | - |
| [Subdimensional Expansion Using Attention-Based Learning For Multi-Agent Path Finding](https://www.semanticscholar.org/paper/Subdimensional-Expansion-Using-Attention-Based-For-Virmani-Ren/1b0e308f3f5bf0613dcf2d61027e4fd98afeb178) | arXiv | 2021 | [code](https://github.com/lakshayvirmani/learning-assisted-mstar) |

### Learning Decentralized Policies - OQ 7,8,9,10,11,12

| Paper | Venue | Year | Links |
|-------|-------|------|:--:|
| [Decentralized Monte Carlo Tree Search for Partially Observable Multi-agent Pathfinding](https://www.semanticscholar.org/paper/Decentralized-Monte-Carlo-Tree-Search-for-Partially-Skrynnik-Andreychuk/380bebc106baa23e14189a213509b4181389c419) | AAAI | 2024 | [code](https://github.com/Cognitive-AI-Systems/mats-lp) |
| [Learn to Follow: Lifelong Multi-agent Pathfinding with Decentralized Replanning](https://www.semanticscholar.org/paper/Learn-to-Follow%3A-Lifelong-Multi-agent-Pathfinding/79e08f9c1cfc85950fac58409c57fa549b4c1b37) | AAAI | 2024 | [code](https://github.com/Cognitive-AI-Systems/learn-to-follow) |
| [SCRIMP: Scalable Communication for Reinforcement- and Imitation-Learning-Based Multi-Agent Pathfinding](https://www.semanticscholar.org/paper/SCRIMP%3A-Scalable-Communication-for-Reinforcement-Wang-Xiang/8370bfa2d4c6f6a4c6413f59b82a81c63e15f1f0) | AAMAS | 2023 | [code](https://github.com/marmotlab/SCRIMP) |
| [SACHA: Soft Actor-Critic with Heuristic-Based Attention for Partially Observable Multi-Agent Path Finding](https://www.semanticscholar.org/paper/SACHA%3A-Soft-Actor-Critic-With-Heuristic-Based-for-Lin-Ma/68593cf344979abb70b8ece3e8f4528f35e8e4ae) | RAL | 2023 | [code](https://github.com/Qiushi-Lin/SACHA) |
| [Learning Selective Communication for Multi-Agent Path Finding](https://www.semanticscholar.org/paper/Learning-Selective-Communication-for-Multi-Agent-Ma-Luo/ce49edee97d03f99c6965e22b0f858b0e65dd29c) | RAL | 2022 | [code](https://github.com/ZiyuanMa/DCC) |
| [Multi-agent path finding with prioritized communication learning](https://www.semanticscholar.org/paper/Multi-Agent-Path-Finding-with-Prioritized-Learning-Li-Chen/7701a7b03deee3a22215ee49956ee65d8adcc835) | ICRA | 2022 | [code](https://github.com/mail-ecnu/PICO) |
| [Distributed Heuristic Multi-Agent Path Finding with Communication](https://www.semanticscholar.org/paper/Distributed-Heuristic-Multi-Agent-Path-Finding-with-Ma-Luo/ce9bf2957d9c1ff2782a585915d6632464246dae) | ICRA | 2021 | [code](https://github.com/ZiyuanMa/DHC) |
| [Message-Aware Graph Attention Networks for Large-Scale Multi-Robot Path Planning](https://www.semanticscholar.org/paper/Message-Aware-Graph-Attention-Networks-for-Path-Li-Lin/2e36207b32127b240d3dd9706f094dd2b7c08e74) | RAL | 2021 | [code](https://github.com/proroklab/magat_pathplanning) |
| [PRIMAL2: Pathfinding Via Reinforcement and Imitation Multi-Agent Learning - Lifelong](https://www.semanticscholar.org/paper/PRIMAL%24_2%24%3A-Pathfinding-Via-Reinforcement-and-Damani-Luo/793c012801865f90d6e49dbb39008a1eb1723811) | RAL | 2021 | [code](https://github.com/marmotlab/PRIMAL2) |
| [Mobile robot path planning in dynamic environments through globally guided reinforcement learning](https://www.semanticscholar.org/paper/Mobile-Robot-Path-Planning-in-Dynamic-Environments-Wang-Liu/91128b705c5292d2a9e09a36047de90e9d59bc06) | RAL | 2020 | - |
| [Mapper: Multi-agent path planning with evolutionary reinforcement learning in mixed dynamic environments](https://www.semanticscholar.org/paper/MAPPER%3A-Multi-Agent-Path-Planning-with-Evolutionary-Liu-Chen/c93e14a8b63b9a01cba388b153b5c0ad3561a5d0) | IROS | 2020 | - |
| [Graph Neural Networks for Decentralized Multi-Robot Path Planning](https://www.semanticscholar.org/paper/Graph-Neural-Networks-for-Decentralized-Multi-Robot-Li-Gama/8284195cf32a24beeff5b1aa262093435dddbdad) | IROS | 2019 | [code](https://github.com/proroklab/magat_pathplanning) |
| [PRIMAL: Pathfinding via Reinforcement and Imitation Multi-Agent Learning](https://www.semanticscholar.org/paper/PRIMAL%3A-Pathfinding-via-Reinforcement-and-Imitation-Sartoretti-Kerr/4fe9142a47b35638edcc59013ad5e9e87bd93ea7) | RAL | 2019 | [code](https://github.com/gsartoretti/PRIMAL) |

## Execution

### Travel and Action Time Modeling - OQ 13

| Paper | Venue | Year | Links |
|-------|-------|------|:--:|
| [Online Re-Planning and Adaptive Parameter Update for Multi-Agent Path Finding with Stochastic Travel Times](https://www.semanticscholar.org/paper/Online-Re-Planning-and-Adaptive-Parameter-Update-Kita-Suenari/6b58d735ddb8874497b2758bdf035a0aad66a4ca) | AAMAS | 2023 | - |
| [Congestion Prediction for Large Fleets of Mobile Robots](https://www.semanticscholar.org/paper/Congestion-Prediction-for-Large-Fleets-of-Mobile-Yu-Wolf/2c4cfbc66639754dae13059492a4e1910481e21d) | ICRA | 2023 | [project](https://www.amazon.science/blog/predicting-congestion-in-fleets-of-robots) |
| [Reinforcement Learning for Zone Based Multiagent Pathfinding under Uncertainty](https://www.semanticscholar.org/paper/Reinforcement-Learning-for-Zone-Based-Multiagent-Ling-Gupta/6f8d9d24b833c76680c3fdff3ed545a5681a2e86) | ICAPS | 2020 | [code](), [project]() |

### Failure Prediction - OQ 14

| Paper | Venue | Year | Links |
|-------|-------|------|:--:|
| [Paper Title](url) | Venue | Year | [code](), [project]() |


## Simulation Environments

| Paper | Venue | Year | Links |
|-------|-------|------|:--:|
| [POGEMA: Partially observable grid environment for multiple agents](https://www.semanticscholar.org/paper/POGEMA%3A-Partially-Observable-Grid-Environment-for-Skrynnik-Andreychuk/7cb4d02172ac0326d08a303c17f2b7c243f95568) | ICLR | 2025 | [code](https://github.com/Cognitive-AI-Systems/pogema) |
| [VMAS: A Vectorized Multi-Agent Simulator for Collective Robot Learning](https://www.semanticscholar.org/paper/VMAS%3A-A-Vectorized-Multi-Agent-Simulator-for-Robot-Bettini-Kortvelesy/cc9dd80da2d7e4b55033d93d509bd8f98fb4c450) | DARS | 2022 | [code](https://github.com/proroklab/VectorizedMultiAgentSimulator) |
| [Minigrid & Miniworld: Modular & Customizable Reinforcement Learning Environments for Goal-Oriented Tasks](https://www.semanticscholar.org/paper/Minigrid-%26-Miniworld%3A-Modular-%26-Customizable-for-Chevalier-Boisvert-Dai/8bb7cecd1bc3fa470aa882158e7553705b1a6141) | NeurIPS | 2023 | [MiniGrid](https://github.com/Farama-Foundation/Minigrid), [MiniWorld](https://github.com/Farama-Foundation/Miniworld) |
| [RWARE](https://www.semanticscholar.org/paper/Shared-Experience-Actor-Critic-for-Multi-Agent-Christianos-Sch%C3%A4fer/4ae72ead4ac780327217221a632b3f8383542b29) | NeurIPS | 2020 | [code](https://github.com/uoe-agents/robotic-warehouse) |
| [Flatland-rl: Multi-agent reinforcement learning on trains](https://www.semanticscholar.org/paper/Flatland-RL-%3A-Multi-Agent-Reinforcement-Learning-on-Mohanty-Nygren/457bd31e0657010918b3400ca43c63c9f93a5be2) | arXiv | 2020 | [code](https://gitlab.aicrowd.com/flatland/flatland), [project](https://flatland.aicrowd.com/intro.html) |

---

## Note

In 2024, we published "A Comprehensive Review on Leveraging Machine Learning for Multi-Agent Path Finding - Alkazzi & Okumura" which you can find [as open access on the IEEE Access Journal](https://ieeexplore.ieee.org/abstract/document/10506521).

Given the nature of research papers, this is now stuck in time. All newer papers and approaches tackling MAPF through Machine Learning techniques are not included, and this pushes the field for someone to eventually re-write such a review to keep the information up to date.

I feel that an incrementally updated review would benefit the community more than a complete new re-write every few years.

(Dream) Ideally, I would love for this to be an actually fully written paper that is being updated monthly with new references or even sections (think a mini booklet style). As an initial step, I am designing it as a list of references under the same structure proposed in the original paper. Once this is updated at a stable rate, I will hopefully move on to the full paper endeavour.

## Open Questions

Each section includes open questions worthy of future investigation as originally proposed in our review. For simplicity, we keep them in this table and reference them as `OQ X`.

| OQ | Question |
|:--:|----------|
| 1 | What can be beneficial criteria and reliable benchmarks for assessing the quality of environment representation? |
| 2 | What are efficient transition mechanisms between offline and online environment optimization? |
| 3 | What is the appropriate input instance representation for algorithm selection? |
| 4 | What is the appropriate representation for MAPF on non-grid worlds? |
| 5 | How can learning from experience be transferred from smaller to larger instances? |
| 6 | How can we identify and extract effective features to maximize the performance of ML-assisted MAPF algorithms? |
| 7 |  Which benchmarking suite of environments and evaluation metrics would best reflect the performance of different techniques? |
| 8 | Which communication strategy is most effective in real-world environments with their inherent challenges? |
| 9 | How can effectively learned implicit communication minimize the need and overhead of explicit communication while achieving comparable outcomes? |
| 10 | How could more advanced IL methods improve the performance of agent-based approaches beyond naive behavior cloning (BC)? |
| 11 | How can we avoid reward shaping to eliminate human bias in the learning process? |
| 12 | How can one construct a dataset of MAPF instances that progressively increases in difficulty? |
| 13 | To what extent should the real-world agent dynamics captured by ML be reflected in MAPF? |
| 14 | How can ML enhance the fault tolerance of MAPF systems? |

---

## Citation
```bibtex
@article{Alkazzi2024mlmapf,
  author={Alkazzi, Jean-Marc and Okumura, Keisuke},
  journal={IEEE Access}, 
  title={A Comprehensive Review on Leveraging Machine Learning for Multi-Agent Path Finding}, 
  year={2024},
  doi={10.1109/ACCESS.2024.3392305}
}
```
