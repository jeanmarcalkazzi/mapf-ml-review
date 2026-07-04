# A (LIVE) Comprehensive Review on Leveraging Machine Learning for Multi-Agent Path Finding

A living survey tracking Machine Learning approaches to solving the MAPF Problem.


🕐 Last updated: 2026-06-30

📄 [Original Survey (Alkazzi & Okumura - IEEE Access 2024)](https://ieeexplore.ieee.org/abstract/document/10506521)

📚 [All BibTeX](references.bib)

📋 [Changelog](CHANGELOG.md) — latest: `2026.06` (+79 papers)

---

## Representation

### Representation for Planning - OQ 1

| Paper | Venue | Year | Links |
|-------|-------|------|:--:|
| CTRMs: Learning to Construct Cooperative Timed Roadmaps for Multi-Agent Path Planning in Continuous Spaces | AAMAS | 2022 | [paper](https://www.semanticscholar.org/paper/e26cdb91017be4fd83d98ee0a75ce8dcb797464a) • [code](https://github.com/omron-sinicx/ctrm/) • [project](https://omron-sinicx.github.io/ctrm/) |
| Avoidance Critical Probabilistic Roadmaps for Motion Planning in Dynamic Environments | ICRA | 2021 | [paper](https://www.semanticscholar.org/paper/242930b85d5323d3e74395073da44649984c2369) |

### Environment Optimization - OQ 2

| Paper | Venue | Year | Links |
|-------|-------|------|:--:|
| Scaling Multi-Agent Environment Co-Design with Diffusion Models | ICML | 2026 | [paper](https://www.semanticscholar.org/paper/79c34b99e4208e92b2117ae4fa5616b13a33796e) • [code](https://github.com/MarkHaoxiang/diffusion-co-design) |
| Optimization of Edge Directions and Weights for Mixed Guidance Graphs in Lifelong Multi-Agent Path Finding | arXiv | 2026 | [paper](https://www.semanticscholar.org/paper/109f0005f70874d0537c4c602c4ca8caf1ea323a) |
| Differentiable Environment-Trajectory Co-Optimization for Safe Multi-Agent Navigation | arXiv | 2026 | [paper](https://www.semanticscholar.org/paper/e80a12ebeb05e55d22b628318ebcdd1d1c0afb0b) |
| Online Guidance Graph Optimization for Lifelong Multi-Agent Path Finding | AAAI | 2025 | [paper](https://www.semanticscholar.org/paper/3648f96f0ab2d2851a3f9f59edb7cf12f1aa27ee) • [code](https://github.com/zanghz21/OnlineGGO) |
| Generative Curricula for Multi-Agent Path Finding via Unsupervised and Reinforcement Learning | JAIR | 2025 | [paper](https://www.semanticscholar.org/paper/04fc21df599830b61c9d2302d9ab13f318f70296) • [code](https://github.com/thomyphan/gen-curricula-mapf) |
| Co-Optimizing Reconfigurable Environments and Policies for Decentralized Multi-Agent Navigation | TRO | 2025 | [paper](https://www.semanticscholar.org/paper/1db6628bf02fc5a12f2f8cc624e16a5e4aaa6eb9) • [project](https://www.proroklab.org/publications/co-optimizing-environments-tro2025/) • [video](https://www.youtube.com/watch?v=mmcqC555wgY) |
| Guidance Graph Optimization for Lifelong Multi-Agent Path Finding | IJCAI | 2024 | [paper](https://www.semanticscholar.org/paper/1a308f5b39e70c492ab3f90498f198fa41a7a811) • [code](https://github.com/lunjohnzhang/ggo_public) • [project](https://yulunzhang.net/publication/zhang2024ggo/) |
| Learning Neural Traffic Rules | RA-L | 2024 | [paper](https://www.semanticscholar.org/paper/b7c6c81377f71ebf1ba3d445cff3931d09e3fd26) |
| Arbitrarily Scalable Environment Generators via Neural Cellular Automata | NeurIPS | 2023 | [paper](https://www.semanticscholar.org/paper/0ed66bbc7c30552b80f1e5fcc76ce74816cba5c6) • [code](https://github.com/lunjohnzhang/warehouse_env_gen_nca_public) |
| Multi-Robot Coordination and Layout Design for Automated Warehousing | IJCAI | 2023 | [paper](https://www.semanticscholar.org/paper/98b6f0b58177b679cff92f916abc04eea5cc3a86) • [code](https://github.com/lunjohnzhang/warehouse_env_gen_public) |
| Constrained Environment Optimization for Prioritized Multi-Agent Navigation | IEEE Open Journal of Control Systems | 2023 | [paper](https://www.semanticscholar.org/paper/031ffab4164a5a832b603a49c7577e7fabac5316) |
| Environment Optimization for Multi-Agent Navigation | ICRA | 2023 | [paper](https://www.semanticscholar.org/paper/eb5616b50a2e12f5cc3f8e8bf80e6108d1bd4cbb) |

### Environment Generation for MAPF Algorithm Evaluation

| Paper | Venue | Year | Links |
|-------|-------|------|:--:|
| QD-MAPPER: A Quality Diversity Framework to Automatically Evaluate Multi-Agent Path Finding Algorithms in Diverse Maps | AAMAS | 2026 | [paper](https://www.semanticscholar.org/paper/c246f450b34468dd394801b8e4830e8136972ec6) • [code](https://github.com/AirTClick/QD-MAPPER) • [project](https://airtclick.github.io/qdmapper) |

### Representation for Selection OQ 3,4

| Paper | Venue | Year | Links |
|-------|-------|------|:--:|
| Anytime Automatic Algorithm Selection for the Multi-Agent Path Finding Problem | IEEE Access | 2024 | [paper](https://www.semanticscholar.org/paper/4ba64e940721a86e7fa6cba25b0b231bf099a0ca) |
| No Panacea in Planning: Algorithm Selection for Suboptimal Multi-Agent Path Finding | arXiv | 2024 | [paper](https://www.semanticscholar.org/paper/ec5d5af09606491e2c7226b007d23d92b5ca3d32) |
| Algorithm Selection for Optimal Multi-Agent Path Finding via Graph Embedding | arXiv | 2024 | [paper](https://www.semanticscholar.org/paper/d44e194e273d35e22991f773218ec857009cf59a) |
| MAPFASTER: A Faster and Simpler take on Multi-Agent Path Finding Algorithm Selection | IROS | 2022 | [paper](https://www.semanticscholar.org/paper/a0e0f528da5e10d68d81b1b64dbf8d36655c345c) • [code](https://github.com/jeanmarcalkazzi/mapfaster) |
| MAPFAST: A Deep Algorithm Selector for Multi Agent Path Finding using Shortest Path Embeddings | AAMAS | 2021 | [paper](https://www.semanticscholar.org/paper/2cad646b21b172fbfbd62e82208be676c53116d1) • [code](https://github.com/USC-ACTLab/MAPFAST) |
| Algorithm Selection for Optimal Multi-Agent Pathfinding | ICAPS | 2020 | [paper](https://www.semanticscholar.org/paper/ee2feec737391ea97374c03ac3bdf263cc2a3d7f) • [code](https://github.com/OmriKaduri/MAPF-Classification) |
| Automatic algorithm selection in multi-agent pathfinding | arXiv | 2019 | [paper](https://www.semanticscholar.org/paper/ec1393b702c9b530a5edb2959851f65bcd467e3f) |

## Planning

### Augmenting Existing Solvers - OQ 5,6

#### Enhancing Conflict-Based Search

| Paper | Venue | Year | Links |
|-------|-------|------|:--:|
| Multi-Agent Path Finding Among Dynamic Uncontrollable Agents with Statistical Safety Guarantees | arXiv | 2025 | [paper](https://www.semanticscholar.org/paper/ca18fb7a8837c0e0bd26a93291db2d4b4c584992) |
| Proactive Conflict Area Prediction for Boosting Search-Based Multi-Agent Pathfinding | IROS | 2025 | [paper](https://www.semanticscholar.org/paper/6bdf45927dd59114a3579d970910317a808864fe) |
| Conflict Area Prediction for Boosting Search-Based Multi-Agent Pathfinding Algorithms | ICRA | 2024 | [paper](https://www.semanticscholar.org/paper/ebb77e4aa25f921e50f4b9dbcacc8dc9f6f35eaa) |
| Accelerating Multi-Agent Planning Using Graph Transformers with Bounded Suboptimality | ICRA | 2023 | [paper](https://www.semanticscholar.org/paper/fca667cf815f5a5c52c2269d81d9f9e7e1ef666c) |
| Learning Node-Selection Strategies in Bounded-Suboptimal Conflict-Based Search for Multi-Agent Path Finding | AAMAS | 2021 | [paper](https://www.semanticscholar.org/paper/2880dcda763ae53fb3dbc7b0fe0e2e642c7215c4) |
| Learning to Resolve Conflicts for Multi-Agent Path Finding with Conflict-Based Search | AAAI | 2021 | [paper](https://www.semanticscholar.org/paper/c6a24e9ef8d78128c78406dd33597ad080ce2772) |

#### Enhancing Prioritized Planning

| Paper | Venue | Year | Links |
|-------|-------|------|:--:|
| Learning-guided Prioritized Planning for Lifelong Multi-Agent Path Finding in Warehouse Automation | JAIR | 2026 | [paper](https://www.semanticscholar.org/paper/deda1d00d22a61b52506de09985d29a0dff62abd) • [code](https://github.com/MikeZheng777/RL-RH-PP) |
| Attention-based Priority Learning for Limited Time Multi-Agent Path Finding | AAMAS | 2024 | [paper](https://www.semanticscholar.org/paper/aea5e8a0d5ad2f7d5f71f072b9c2a761fc1822bd) • [code](https://github.com/marmotlab/S2AN) |
| Synthesizing priority planning formulae for multi-agent pathfinding | AIIDE | 2023 | [paper](https://www.semanticscholar.org/paper/3c80978256dacf8cbde8cdf56bda8b4fc367c406) |
| Learning a Priority Ordering for Prioritized Planning in Multi-Agent Path Finding | SoCS | 2022 | [paper](https://www.semanticscholar.org/paper/b3df18bc728823eb50fd4b1d1994ad4483777da0) |

#### Enhancing other MAPF solvers 

| Paper | Venue | Year | Links |
|-------|-------|------|:--:|
| Graph Attention-Guided Search for Dense Multi-Agent Pathfinding | AAAI | 2026 | [paper](https://www.semanticscholar.org/paper/eb28f3f33315c59f9fe832b7e04fb3f67569ff66) • [code](https://github.com/proroklab/lagat) |
| GRAND: Guidance, Rebalancing, and Assignment for Networked Dispatch in Multi-Agent Path Finding | RAL | 2026 | [paper](https://www.semanticscholar.org/paper/41edd1e66fcade55e5f13d9d98fcbb59bfde2aa9) |
| Truncated Counterfactual Learning for Anytime Multi-Agent Path Finding | AAAI | 2026 | [paper](https://www.semanticscholar.org/paper/167cf3c51cd3aefef86a1868b684acd24b4f7a6c) • [code](https://github.com/thomyphan/counterfactual-mapf-lns) • [video](https://underline.io/lecture/143208-truncated-counterfactual-learning-for-anytime-multi-agent-path-finding) |
| Discrete Diffusion for Complex and Congested Multi-Agent Path Finding with Sparse Social Attention | arXiv | 2026 | [paper](https://www.semanticscholar.org/paper/4a579495142881d8ef54da1f0477f2274dc204d0) |
| LNS2+RL: Combining Multi-Agent Reinforcement Learning with Large Neighborhood Search in Multi-Agent Path Finding | AAAI | 2025 | [paper](https://www.semanticscholar.org/paper/2cc23c90c5718daa8c4f1b5c5071be51cd4e3863) • [code](https://github.com/marmotlab/LNS2-RL) |
| Anytime Multi-Agent Path Finding with an Adaptive Delay-Based Heuristic | AAAI | 2025 | [paper](https://www.semanticscholar.org/paper/d4be38bef4c464682c209227d4179c6f3d3c879c) • [code](https://github.com/JimyZ13/ADDRESS) |
| Enhancing PIBT for Multi-Agent Path Finding via MLP-Based Candidate Selection and Priority Perturbation | IEEE Access | 2025 | [paper](https://www.semanticscholar.org/paper/40943b6fd04d1a0b3481f4a416b1cec24919beb0) |
| Learn to Refine: Synergistic Multi-Agent Path Optimization for Lifelong Conflict-Free Navigation of Autonomous Vehicles | KDD | 2025 | [paper](https://www.semanticscholar.org/paper/9e4a0e8e91c8d0de939a192e03b4149bf4f3ded5) • [code](https://github.com/ByteUser-blues/SMAPO) |
| Neural Neighborhood Search for Multi-agent Path Finding | ICLR | 2024 | [paper](https://www.semanticscholar.org/paper/f529bd992435763061a51502559db8dd54d0b4aa) • [code](https://github.com/mit-wu-lab/mapf_neural_neighborhood_search) |
| Adaptive Anytime Multi-Agent Path Finding Using Bandit-Based Large Neighborhood Search | AAAI | 2024 | [paper](https://www.semanticscholar.org/paper/7d004862004def4c8e2dc2f85fd8f07365ee2dc2) |
| NLNS-MASPF for solving Multi-Agent scheduling and Path-Finding | IROS | 2024 | [paper](https://www.semanticscholar.org/paper/0393c1c950e98ff97c7c822f53b64bca81245664) |
| Anytime Multi-Agent Path Finding via Machine Learning-Guided Large Neighborhood Search | AAAI | 2022 | [paper](https://www.semanticscholar.org/paper/81e43d43c6ae0fb9696b39c2d29cc1987a2b58c8) |
| Subdimensional Expansion Using Attention-Based Learning For Multi-Agent Path Finding | arXiv | 2021 | [paper](https://www.semanticscholar.org/paper/1b0e308f3f5bf0613dcf2d61027e4fd98afeb178) • [code](https://github.com/lakshayvirmani/learning-assisted-mstar) |

### Learning-based Policies - OQ 7,8,9,10,11,12

#### Decentralized

| Paper | Venue | Year | Links |
|-------|-------|------|:--:|
| Confidence-Based Curricula for Multi-Agent Path Finding via Reinforcement Learning | JAAMAS | 2026 | [paper](https://www.semanticscholar.org/paper/5bf27103f43076eb4d93f32006439185e8345ba1) • [code](https://github.com/thomyphan/rl4mapf) |
| Multi-Agent Reinforcement Learning With Spatial Structure Awareness for Topological Map-Based Path-Finding | RAL | 2026 | [paper](https://www.semanticscholar.org/paper/5416c828bd27bec4bfc4d735e58911b554e1ebc0) |
| ORION: Option-Regularized Deep Reinforcement Learning for Cooperative Multi-Agent Online Navigation | RAL | 2026 | [paper](https://www.semanticscholar.org/paper/cc5afa346e0ee7b4ac6b6c1e5aca17682a0cf5e7) • [code](https://github.com/marmotlab/ORION) |
| Pairwise is Not Enough: Hypergraph Neural Networks for Multi-Agent Pathfinding | ICLR | 2026 | [paper](https://www.semanticscholar.org/paper/1e1ee772c8bb8adfb68d14c1601b5936a87cdc20) • [code](https://github.com/proroklab/hmagat) • [project](https://www.proroklab.org/publications/iclr2026-hypergraph-mapf/) |
| Learning to Communicate Locally for Large-Scale Multi-Agent Pathfinding | arXiv | 2026 | [paper](https://www.semanticscholar.org/paper/9be32110a41655563e4aaa27f616e11c8bdca95e) |
| MARL-GPT: Foundation Model for Multi-Agent Reinforcement Learning | AAMAS | 2026 | [paper](https://www.semanticscholar.org/paper/37a37d6a5c3d2026a3c2df1052a7e5aee68578c5) • [code](https://github.com/Cognitive-AI-Systems/marl-gpt) • [weights](https://huggingface.co/nortem/marl-gpt-model/tree/main) • [dataset](https://huggingface.co/datasets/nortem/marl-gpt-datasets) |
| From One to Many: Adaptive Multi-Agent Pathfinding in Heterogeneous Environments | Optical Memory and Neural Networks | 2026 | [paper](https://www.semanticscholar.org/paper/a65e496364d2bc44525561026449daba8b00b57a) |
| SPARC: Spatial-Aware Path Planning via Attentive Agent Communication | arXiv | 2026 | [paper](https://www.semanticscholar.org/paper/6b897466df60f7e634dc48ba5b2b8ee4dda78491) |
| Mean-Field Deep Reinforcement Learning for Multi-Agent Path Finding | RAL | 2026 | [paper](https://www.semanticscholar.org/paper/460e6a316211df013c889e8a71bbba4ba7f4f102) |
| Spatially Grouped Curriculum Learning for Multi-Agent Path Finding | AAAI | 2026 | [paper](https://www.semanticscholar.org/paper/05d1bfb8ce157d6072de05edcb767cddff4c2637) • [code](https://github.com/thomyphan/spatial-curricula-mapf) |
| Simulation-Informed Diffusion for Decentralized Multi-robot Motion Planning | arXiv | 2026 | [paper](https://www.semanticscholar.org/paper/4cb45a60a251ddb8a0ead62e84ed68f70cba9a62) |
| Social Behavior as a Key to Learning-based Multi-Agent Pathfinding Dilemmas | AIJ | 2025 | [paper](https://www.semanticscholar.org/paper/4e12686d6ecdd3f150e4d1a27802550b5e6050b3) • [code](https://github.com/marmotlab/codebase_SYLPH) • [project](https://marmotlab.github.io/mapf_sylph/) |
| MAPF-GPT: Imitation Learning for Multi-Agent Pathfinding at Scale | AAAI | 2025 | [paper](https://www.semanticscholar.org/paper/c9d111549bf92fa45cbd0d1114acff8cbd689339) • [code](https://github.com/CognitiveAISystems/MAPF-GPT) • [project](https://sites.google.com/view/mapf-gpt) • [weights](https://huggingface.co/datasets/aandreychuk/MAPF-GPT/tree/main) • [dataset](https://huggingface.co/datasets/aandreychuk/MAPF-GPT/tree/main) • [notebooks](https://colab.research.google.com/drive/1NMMv89QBUJA_xkYSy2QZKTxHoRxzwqSk?usp=sharing) |
| Work Smarter Not Harder: Simple Imitation Learning with CS-PIBT Outperforms Large Scale Imitation Learning for MAPF | ICRA | 2025 | [paper](https://www.semanticscholar.org/paper/8ed58dc49db0f6c10698c7c09272305ac9602892) • [code](https://github.com/ArthurJakobsson/gnn-mapf) • [project](https://arthurjakobsson.github.io/ssil_mapf/) |
| Deploying Ten Thousand Robots: Scalable Imitation Learning for Lifelong Multi-Agent Path Finding | ICRA | 2025 | [paper](https://www.semanticscholar.org/paper/f297e5fed666e1afba12f3e571ed2ec28c1c9ef3) • [code](https://github.com/DiligentPanda/Scalable-Imitation-Learning-for-LMAPF) • [project](https://diligentpanda.github.io/SILLM/) |
| SRMT: Shared Memory for Multi-agent Lifelong Pathfinding | arXiv | 2025 | [paper](https://www.semanticscholar.org/paper/05a6dfdccbc6def94cd9d6ba79915bbb8b078a8f) • [code](https://github.com/Aloriosa/srmt) |
| SIGMA: Sheaf-Informed Geometric Multi-Agent Pathfinding | ICRA | 2025 | [paper](https://www.semanticscholar.org/paper/a3f78c0fe84269d532ee295c2321a32dcceca7fc) • [code](https://github.com/marmotlab/SIGMA) |
| Learning Verified Safe Neural Network Controllers for Multi-Agent Path Finding | AAAI | 2025 | [paper](https://www.semanticscholar.org/paper/6e881a0ea0c84839b3a2085ef5b760d7efb4bb60) • [video](https://underline.io/lecture/113778-learning-verified-safe-neural-network-controllers-for-multi-agent-path-finding) |
| MARF: Cooperative Multi-Agent Path Finding with Reinforcement Learning and Frenet Lattice in Dynamic Environments | ICRA | 2025 | [paper](https://www.semanticscholar.org/paper/582a447feab6ce9d9ec06aa704d917d033b2c535) |
| Towards Transparent Multi-Agent Autonomous Systems Through Principled Multi-Source Knowledge Distillation | ICRA | 2025 | [paper](https://www.semanticscholar.org/paper/0ee04e055b00b54ceb5b5a58570b3aec2cc2228c) |
| Advancing Learnable Multi-Agent Pathfinding Solvers with Active Fine-Tuning | arXiv | 2025 | [paper](https://www.semanticscholar.org/paper/193535c0da40f81ecf3bffe3e34f552f255687ef) • [code](https://github.com/Cognitive-AI-Systems/MAPF-GPT-DDG) • [project](https://sites.google.com/view/mapf-gpt-ddg) |
| MAPF-World: Action World Model for Multi-Agent Path Finding | arXiv | 2025 | [paper](https://www.semanticscholar.org/paper/952e1888c5cafce5aac9d0be662c37cbfedca98b) |
| Towards Information-Optimized Multi-Agent Path Finding: A Hybrid Framework with Reduced Inter-Agent Information Sharing | arXiv | 2025 | [paper](https://www.semanticscholar.org/paper/d66d0925fdc12b68a311d5c06fa0a85094ff8af7) |
| PC2P: Multi-Agent Path Finding via Personalized-Enhanced Communication and Crowd Perception | IROS | 2025 | [paper](https://www.semanticscholar.org/paper/40f95e2797bc739e788af1a0056b73c5aa7b4be4) |
| STF: Spatio-Temporal Fusion-Based Multi-Agent Path-Finding | RAL | 2025 | [paper](https://www.semanticscholar.org/paper/a3ddea1866d786011c69eaaf2eb0187ed64e6079) |
| Improving Learnt Local MAPF Policies with Heuristic Search | ICAPS | 2024 | [paper](https://www.semanticscholar.org/paper/64f4873aa1c19f36a6d20a3ac5235d5052a61e95) • [extras](https://drive.google.com/drive/folders/1iVSXbMHINnCsMzMPVi4k7P99RZFX6qbQ) |
| Decentralized Monte Carlo Tree Search for Partially Observable Multi-agent Pathfinding | AAAI | 2024 | [paper](https://www.semanticscholar.org/paper/380bebc106baa23e14189a213509b4181389c419) • [code](https://github.com/Cognitive-AI-Systems/mats-lp) |
| Learn to Follow: Decentralized Lifelong Multi-agent Pathfinding via Planning and Learning | AAAI | 2024 | [paper](https://www.semanticscholar.org/paper/0830fbc6e19483e8e3036ab03478dd00b45a2e3f) • [code](https://github.com/Cognitive-AI-Systems/learn-to-follow) |
| When to Switch: Planning and Learning for Partially Observable Multi-Agent Pathfinding | IEEE TNNLS | 2024 | [paper](https://www.semanticscholar.org/paper/48803629958416c71ab01838d44cd63d91d960d2) • [code](https://github.com/AIRI-Institute/when-to-switch) |
| Optimizing Crowd-Aware Multi-Agent Path Finding through Local Communication with Graph Neural Networks | IROS | 2024 | [paper](https://www.semanticscholar.org/paper/99d5d92c9b281497d0982a2f6865eb4a98452bf8) • [project](https://ideas.cs.purdue.edu/research/projects/cramp/) |
| POAQL: A Partially Observable Altruistic Q-Learning Method for Cooperative Multi-Agent Reinforcement Learning | ICRA | 2024 | [paper](https://www.semanticscholar.org/paper/14f1841da268b3a1de3a78e6f7e1bca3d6fe0d93) |
| Crowd Perception Communication-Based Multi-Agent Path Finding With Imitation Learning | RAL | 2024 | [paper](https://www.semanticscholar.org/paper/7af6a9ba4293c92935936fd3e4b3e8e64fe8f558) |
| MFC-EQ: Mean-Field Control with Envelope Q-Learning for Moving Decentralized Agents in Formation | IROS | 2024 | [paper](https://www.semanticscholar.org/paper/9fa234726ba6bf4509f46912e81ce24565c035f7) • [code](https://github.com/Qiushi-Lin/MFCEQ) |
| ALPHA: Attention-based Long-horizon Pathfinding in Highly-structured Areas | ICRA | 2024 | [paper](https://www.semanticscholar.org/paper/a53487102ee0684fc1ab577c92dbd27e3f5f6ea6) • [code](https://github.com/marmotlab/ALPHA) |
| SCRIMP: Scalable Communication for Reinforcement- and Imitation-Learning-Based Multi-Agent Pathfinding | AAMAS | 2023 | [paper](https://www.semanticscholar.org/paper/8370bfa2d4c6f6a4c6413f59b82a81c63e15f1f0) • [code](https://github.com/marmotlab/SCRIMP) |
| SACHA: Soft Actor-Critic with Heuristic-Based Attention for Partially Observable Multi-Agent Path Finding | RAL | 2023 | [paper](https://www.semanticscholar.org/paper/68593cf344979abb70b8ece3e8f4528f35e8e4ae) • [code](https://github.com/Qiushi-Lin/SACHA) |
| Learning Selective Communication for Multi-Agent Path Finding | RAL | 2022 | [paper](https://www.semanticscholar.org/paper/ce49edee97d03f99c6965e22b0f858b0e65dd29c) • [code](https://github.com/ZiyuanMa/DCC) |
| Multi-agent path finding with prioritized communication learning | ICRA | 2022 | [paper](https://www.semanticscholar.org/paper/7701a7b03deee3a22215ee49956ee65d8adcc835) • [code](https://github.com/mail-ecnu/PICO) |
| Distributed Heuristic Multi-Agent Path Finding with Communication | ICRA | 2021 | [paper](https://www.semanticscholar.org/paper/ce9bf2957d9c1ff2782a585915d6632464246dae) • [code](https://github.com/ZiyuanMa/DHC) |
| Message-Aware Graph Attention Networks for Large-Scale Multi-Robot Path Planning | RAL | 2021 | [paper](https://www.semanticscholar.org/paper/2e36207b32127b240d3dd9706f094dd2b7c08e74) • [code](https://github.com/proroklab/magat_pathplanning) |
| PRIMAL2: Pathfinding Via Reinforcement and Imitation Multi-Agent Learning - Lifelong | RAL | 2021 | [paper](https://www.semanticscholar.org/paper/793c012801865f90d6e49dbb39008a1eb1723811) • [code](https://github.com/marmotlab/PRIMAL2) |
| Mobile robot path planning in dynamic environments through globally guided reinforcement learning | RAL | 2020 | [paper](https://www.semanticscholar.org/paper/91128b705c5292d2a9e09a36047de90e9d59bc06) |
| Mapper: Multi-agent path planning with evolutionary reinforcement learning in mixed dynamic environments | IROS | 2020 | [paper](https://www.semanticscholar.org/paper/c93e14a8b63b9a01cba388b153b5c0ad3561a5d0) |
| Graph Neural Networks for Decentralized Multi-Robot Path Planning | IROS | 2019 | [paper](https://www.semanticscholar.org/paper/8284195cf32a24beeff5b1aa262093435dddbdad) • [code](https://github.com/proroklab/magat_pathplanning) |
| PRIMAL: Pathfinding via Reinforcement and Imitation Multi-Agent Learning | RAL | 2019 | [paper](https://www.semanticscholar.org/paper/4fe9142a47b35638edcc59013ad5e9e87bd93ea7) • [code](https://github.com/gsartoretti/PRIMAL) |

#### Centralized

| Paper | Venue | Year | Links |
|-------|-------|------|:--:|
| Discrete-Guided Diffusion for Scalable and Safe Multi-Robot Motion Planning | AAAI | 2026 | [paper](https://www.semanticscholar.org/paper/b0745bce4125a3907d6cb868ddf500bc839e4f1d) |
| Multi-Robot Motion Planning from Vision and Language using Heat-Inspired Diffusion | RAL | 2026 | [paper](https://www.semanticscholar.org/paper/8fbe44cf67faecf3de130b88e35f65395672f7bd) • [code](https://github.com/jebeom/LHD) • [project](https://jebeom.github.io/lhd_project_page/) |
| Train-Small Deploy-Large: Leveraging Diffusion-Based Multi-Robot Planning | arXiv | 2026 | [paper](https://www.semanticscholar.org/paper/ab2bda189c1f482218be09bc13cdada7563a6d16) |
| DeepFleet: Multi-Agent Foundation Models for Mobile Robots | arXiv | 2025 | [paper](https://www.semanticscholar.org/paper/91289298ada03b6080905aa9192084ee7a58db35) |
| RAILGUN: A Unified Convolutional Policy for Multi-Agent Path Finding Across Different Environments and Tasks | IROS | 2025 | [paper](https://www.semanticscholar.org/paper/91a715e4766f60d6e73fa188e1b9b9481a58f58f) • [code](https://github.com/TachikakaMin/RAILGUN) |
| Multi-Robot Motion Planning with Diffusion Models | ICLR | 2025 | [paper](https://www.semanticscholar.org/paper/9bf23228d120a11103ec98023d9ced19270969da) • [code](https://github.com/yoraish/mmd) • [project](https://multi-robot-diffusion.github.io/) |
| Simultaneous Multi-Robot Motion Planning with Projected Diffusion Models | ICML | 2025 | [paper](https://www.semanticscholar.org/paper/bce5601edc9b46cab0e9ab8d6362b839b63d2ef6) • [code](https://github.com/RAISELab-atUVA/Diffusion-MRMP) • [project](https://multi-robot-constrained-diffusion.github.io/) |
| Why Solving Multi-agent Path Finding with Large Language Model has not Succeeded Yet | arXiv | 2024 | [paper](https://www.semanticscholar.org/paper/cf89542d61a7b29da70d7866d651ac5b630f9a35) |
| Multi-Agent Path Finding in Continuous Spaces with Projected Diffusion Models | arXiv | 2024 | [paper](https://www.semanticscholar.org/paper/11718147fe3f768aafb370d09419221908c56e4b) |

## Execution

### Travel and Action Time Modeling - OQ 13

| Paper | Venue | Year | Links |
|-------|-------|------|:--:|
| Conflict Mitigation in Shared Environments using Flow-Aware Multi-Agent Path Finding | ICRA | 2026 | [paper](https://www.semanticscholar.org/paper/9b7a98bdb1a984ac9d7268b444fd132c463ad581) |
| From Discrete Plans to Real-World Execution: A World-Model-Driven Framework for Execution-Aware Multi-Agent Path Finding | arXiv | 2025 | [paper](https://www.semanticscholar.org/paper/5f1e7cfab019d65d22cc034c69368888a1584533) |
| Traffic Flow Learning Enhanced Large-Scale Multi-Robot Cooperative Path Planning Under Uncertainties | ICRA | 2024 | [paper](https://www.semanticscholar.org/paper/a7e45785e69d90e89b471656c906daa58645f659) |
| Online Re-Planning and Adaptive Parameter Update for Multi-Agent Path Finding with Stochastic Travel Times | AAMAS | 2023 | [paper](https://www.semanticscholar.org/paper/6b58d735ddb8874497b2758bdf035a0aad66a4ca) |
| Congestion Prediction for Large Fleets of Mobile Robots | ICRA | 2023 | [paper](https://www.semanticscholar.org/paper/2c4cfbc66639754dae13059492a4e1910481e21d) • [project](https://www.amazon.science/blog/predicting-congestion-in-fleets-of-robots) |
| Reinforcement Learning for Zone Based Multiagent Pathfinding under Uncertainty | ICAPS | 2020 | [paper](https://www.semanticscholar.org/paper/6f8d9d24b833c76680c3fdff3ed545a5681a2e86) |

### Failure Prediction - OQ 14

| Paper | Venue | Year | Links |
|-------|-------|------|:--:|
| Should I Replan? Learning to Spot the Right Time in Robust MAPF Execution | arXiv | 2026 | [paper](https://www.semanticscholar.org/paper/0ac7749773b75f56a5e4431045c861ff5030bb16) |


## Simulation Environments and Testbeds

| Paper | Venue | Year | Links |
|-------|-------|------|:--:|
| CAMAR: Continuous Actions Multi-Agent Routing | AAAI | 2026 | [paper](https://www.semanticscholar.org/paper/6ba0f2b4907d14f22ea0254c2f132d84ca2c1343) • [code](https://github.com/AIRI-Institute/CAMAR) • [poster](https://underline.io/lecture/142805-camar-continuous-actions-multi-agent-routing) |
| Advancing MAPF Toward the Real World: A Scalable Multi-Agent Realistic Testbed (SMART) | RA-L | 2026 | [paper](https://www.semanticscholar.org/paper/692d6732de52593367ff3bc6405933fe8eff23c2) • [code](https://github.com/smart-mapf/smart) • [project](https://smart-mapf.github.io/demo/) |
| POGEMA: A Benchmark Platform for Cooperative Multi-Agent Pathfinding | ICLR | 2025 | [paper](https://www.semanticscholar.org/paper/929d78fc8eeb50780fa4bd0180d32f5f2e6b2ca8) • [code](https://github.com/Cognitive-AI-Systems/pogema) |
| SkyRover: A Modular Simulator for Cross-Domain Pathfinding | IJCAI | 2025 | [paper](https://www.semanticscholar.org/paper/e1b9a9852aa7e91fda28e8727582a3cb947f61bd) • [project](https://sites.google.com/view/mapf3d/home) |
| 100-Mouse System: Scalable Multi-Robot Testbed with State Management User Interface | Journal of Robotics and Mechatronics | 2025 | [paper](https://www.semanticscholar.org/paper/f66fe1ca555d8565c6f783eded0ee062800727f8) |
| Minigrid & Miniworld: Modular & Customizable Reinforcement Learning Environments for Goal-Oriented Tasks | NeurIPS | 2023 | [paper](https://www.semanticscholar.org/paper/8bb7cecd1bc3fa470aa882158e7553705b1a6141) • [MiniGrid](https://github.com/Farama-Foundation/Minigrid) • [MiniWorld](https://github.com/Farama-Foundation/Miniworld) |
| VMAS: A Vectorized Multi-Agent Simulator for Collective Robot Learning | DARS | 2022 | [paper](https://www.semanticscholar.org/paper/cc9dd80da2d7e4b55033d93d509bd8f98fb4c450) • [code](https://github.com/proroklab/VectorizedMultiAgentSimulator) |
| RWARE | NeurIPS | 2020 | [paper](https://www.semanticscholar.org/paper/4ae72ead4ac780327217221a632b3f8383542b29) • [code](https://github.com/uoe-agents/robotic-warehouse) |
| Flatland-rl: Multi-agent reinforcement learning on trains | arXiv | 2020 | [paper](https://www.semanticscholar.org/paper/457bd31e0657010918b3400ca43c63c9f93a5be2) • [code](https://gitlab.aicrowd.com/flatland/flatland) • [project](https://flatland.aicrowd.com/intro.html) |


## Interpretable ML for MAPF

| Paper | Venue | Year | Links |
|-------|-------|------|:--:|
| Interpretable Multi-Agent Path Finding via Decision Tree Extraction from Neural Policies | AAAI Workshop | 2026 | [paper](https://openreview.net/forum?id=iuXcr6CkDA) • [video](https://doi.org/10.48448/escr-ch42) |

## Surveys & Benchmarks

| Paper | Venue | Year | Links |
|-------|-------|------|:--:|
| Reevaluation of Large Neighborhood Search for MAPF: Findings and Opportunities | SoCS | 2025 | [paper](https://www.semanticscholar.org/paper/d3089daf01c695403b82ceae7a3b0353277b212b) • [code](https://github.com/ChristinaTan0704/mapf-lns-unified) |
| An empirical evaluation of learning-based multi-agent path finding algorithms in warehouse environments | Robotics and Autonomous Systems | 2025 | [paper](https://www.semanticscholar.org/paper/7c79c7a7865a9ff2af1f2c1ed4d85bd7b255b625) |
| Where Paths Collide: A Comprehensive Survey of Classic and Learning-Based Multi-Agent Pathfinding | arXiv | 2025 | [paper](https://www.semanticscholar.org/paper/e48cca77bea5ee651ed3e6af7c68995e99da25bf) |

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

