---
title:          "Agentorchestra: A Hierarchical Multi-agent Framework for General-purpose Task Solving"
date:           2025-06-10
selected:       false
tags:           ["# LLM Agents", "# deep research", "# hierarchical multi-agent systems"]
pub:            "arXiv preprint, 2025"
# pub_pre:        "Submitted to "
#pub_post:       'Under review.'
#pub_date:       "2026"
# semantic_scholar_id: 204e3073870fae3d05bcbc2f6a8e263d9b72e776  # use this to retrieve citation count
abstract: >-
  Recent advances in LLMs-based agent systems have demonstrated remarkable capabilities in solving complex tasks. Nevertheless, current protocols (e.g., A2A and MCP) suffer from insufficient capabilities in context management, limited adaptability to diverse environments, and the absence of dynamic agent architectures. To address these limitations, we propose the Tool-Environment-Agent (TEA) Protocol, which establishes a principled basis for integrating environments, agents, and tools into an unified system. The TEA protocol treats environments and agents as first-class resources, enabling comprehensive context management and adaptive environment integration. Based on this protocol, we introduce AgentOrchestra, a hierarchical multi-agent framework with a central planning agent that decomposes complex objectives and coordinates specialized agents. Each sub-agent is dedicated to specific functions, providing capabilities for data analysis, file operations, web navigation, and interactive reasoning. Notably, AgentOrchestra introduces a tool manager agent that supports intelligent evolution through dynamic tool creation, retrieval, and reuse mechanisms. Experiments on three widely used benchmarks show that AgentOrchestra consistently outperforms existing baselines, achieving state-of-the-art performance of 83.39% on GAIA and ranking among the top general-purpose LLM-based agents. These results highlight the effectiveness of the TEA Protocol and hierarchical organization in building general-purpose multi-agent systems.
cover:          /images/AgentOrchestra.png
authors:
  - Wentao Zhang
  - Ce Cui
  - Yilei Zhao
  - Rui Hu
  - Yang Liu
  - Yahui Zhou
  - Bo An#
links:
  Paper: https://arxiv.org/abs/2506.12508
  Code: https://github.com/SkyworkAI/DeepResearchAgent
---
