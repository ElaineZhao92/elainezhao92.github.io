---
title:          "STORM: A Spatio-Temporal Factor Model Based on Dual Vector Quantized Variational Autoencoders for Financial Trading"
date:           2025-10-24
selected:       true
type:           publication
tags:           ["# AI4Finance", "# spatio-temporal learning", "# factor models", "# portfolio management", "# quantitative trading"]
pub:            "Proceedings of the Nineteenth ACM International Conference on Web Search and Data Mining (WSDM) "
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_date:       "2026"
# semantic_scholar_id: 204e3073870fae3d05bcbc2f6a8e263d9b72e776  # use this to retrieve citation count
abstract: >-
  In financial trading, factor models are widely used to price assets and capture excess returns from mispricing. Recently, we have witnessed the rise of variational autoencoder-based latent factor models, which learn latent factors self-adaptively. While these models focus on modeling overall market conditions, they often fail to effectively capture the temporal patterns of individual stocks. Additionally, representing multiple factors as single values simplifies the model but limits its ability to capture complex relationships and dependencies. As a result, the learned factors are of low quality and lack diversity, reducing their effectiveness and robustness across different trading periods. To address these issues, we propose a Spatio-Temporal factOR Model based on dual vector quantized variational autoencoders, named STORM, which extracts features of stocks from temporal and spatial perspectives, then fuses and aligns these features at the fine-grained and semantic level, and represents the factors as multi-dimensional embeddings. The discrete codebooks cluster similar factor embeddings, ensuring orthogonality and diversity, which helps distinguish between different factors and enables factor selection in financial trading. To show the performance of the proposed factor model, we apply it to two downstream experiments: portfolio management on two stock datasets and individual trading tasks on six specific stocks. The extensive experiments demonstrate STORM's flexibility in adapting to downstream tasks and superior performance over baseline models.
cover:          /images/STORM.png
authors:
  - Yilei Zhao*
  - Wentao Zhang*
  - Tingran Yang
  - Yong Jiang
  - Fei Huang
  - Wei Yang Bryan Lim#
links:
  Paper: https://arxiv.org/pdf/2412.09468
  Code: https://github.com/DVampire/Storm
---
