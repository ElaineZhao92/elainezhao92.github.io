---
title:          "AlphaForgeBench: Benchmarking End-to-End Trading Strategy Design with Large Language Models"
date:           2026-02-25
selected:       false
tags:           ["# AI4Finance", '# factor models', "# benchmark and datasets"]
pub:            "Proceedings of SIGKDD Conference on Knowledge Discovery and Data Mining (KDD), 2026"
# pub_pre:        "Submitted to "
#pub_post:       'Under review.'
# pub_date:       "2026"
# semantic_scholar_id: 204e3073870fae3d05bcbc2f6a8e263d9b72e776  # use this to retrieve citation count
abstract: >-
  The rapid advancement of Large Language Models (LLMs) has led to a surge of financial benchmarks, evolving from static knowledge tests to interactive trading simulations. However, current evaluations of real-time trading performance overlook a critical failure mode: severe behavioral instability in sequential decision-making under uncertainty. We empirically show that LLM-based trading agents exhibit extreme run-to-run variance, inconsistent action sequences even under deterministic decoding, and irrational action flipping across adjacent time steps. These issues stem from stateless autoregressive architectures lacking persistent action memory, as well as sensitivity to continuous-to-discrete action mappings in portfolio allocation. As a result, many existing financial trading benchmarks produce unreliable, non-reproducible, and uninformative evaluations. To address these limitations, we propose AlphaForgeBench, a principled framework that reframes LLMs as quantitative researchers rather than execution agents. Instead of emitting trading actions, LLMs generate executable alpha factors and factor-based strategies grounded in financial reasoning. This design decouples reasoning from execution, enabling fully deterministic and reproducible evaluation while aligning with real-world quantitative research workflows. Experiments across multiple state-of-the-art LLMs show that AlphaForgeBench eliminates execution-induced instability and provides a rigorous benchmark for assessing financial reasoning, strategy formulation, and alpha discovery.
cover:          /images/alphaforge.png
authors:
  - Wentao Zhang*
  - Mingxuan Zhao*
  - Jinchen Guo*
  - Jieshun You
  - Huaiyu Jia
  - Yilei Zhao
  - Bo An
  - Shuo Sun#
links:
  Paper: https://arxiv.org/pdf/2602.18481
---