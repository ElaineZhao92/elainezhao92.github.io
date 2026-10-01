---
title:          "Agentorchestra: Orchestrating Multi-Agent Intelligence with the Tool-Environment-Agent(TEA) Protocol"
date:           2026-09-30
selected:       false
tags:           ["# LLM Agents", "# deep research"]
pub:            "The Fortieth Annual Conference on Neural Information Processing Systems (NeurIPS) AgenticOS Workshop, 2026"
# pub_pre:        "Submitted to "
#pub_post:       'Under review.'
#pub_date:       "2026"
presentation:     "Poster"
# semantic_scholar_id: 204e3073870fae3d05bcbc2f6a8e263d9b72e776  # use this to retrieve citation count
abstract: >-
  Recent advances in LLM-based agent systems have shown promise on complex, long-horizon tasks, but existing agent protocols (e.g., A2A and MCP) do not adequately support lifecycle-aware coordination across agents, tools, and environments. To address this limitation, we introduce the Tool-Environment-Agent (TEA) protocol, a unified abstraction that models these components as first-class, versioned resources with explicit lifecycles. TEA supports end-to-end context and version management, improving traceability and reproducibility, while also enabling continual self-evolution of agent-associated components\footnote{Here, components include prompts, memory, tools, agents, environments, code, and outputs.}. Building on TEA, we present AgentOrchestra, a hierarchical multi-agent framework in which a central planner coordinates specialized sub-agents and dynamically extends capabilities during execution. Experiments on four challenging benchmarks, spanning expert-level agent tasks and scientific/mathematical reasoning, show that AgentOrchestra consistently outperforms strong baselines; in particular, it achieves 89.04% on the GAIA Test set, placing it among the leading methods to the best of our knowledge. These results demonstrate the value of explicit protocol design and hierarchical orchestration for robust, adaptive multi-agent systems.
cover:          /images/AgentOrchestra.png
authors:
  - Wentao Zhang
  - Liang Zeng
  - Yuzhen Xiao
  - Yongcong Li
  - Yilei Zhao
  - Ce Cui
  - Yang Liu
  - Bo An#
links:
  Paper: https://arxiv.org/abs/2506.12508
  Code: https://github.com/SkyworkAI/DeepResearchAgent
---
