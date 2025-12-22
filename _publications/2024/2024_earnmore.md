---
title:          "Statistical Feature-Based Memory-Efficient Machine Learning Pipeline for Fake Image Detection"
date:           2024-05-13
selected:       true
tags:           ["# AI4Finance", "# portfolio management", "# reinforcement learning"]
pub:            "Proceedings of the ACM Web Conference (WWW), 2024"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_date:       "2024"
# semantic_scholar_id: 204e3073870fae3d05bcbc2f6a8e263d9b72e776  # use this to retrieve citation count
abstract: >-
  Portfolio management (PM) is a fundamental financial trading task, which explores the optimal periodical reallocation of capitals into different stocks to pursue long-term profits. Reinforcement learning (RL) has recently shown its potential to train profitable agents for PM through interacting with financial markets. However, existing work mostly focuses on fixed stock pools, which is inconsistent with investors' practical demand. Specifically, the target stock pool of different investors varies dramatically due to their discrepancy on market states and individual investors may temporally adjust stocks they desire to trade (e.g., adding one popular stocks), which lead to customizable stock pools (CSPs). Existing RL methods require to retrain RL agents even with a tiny change of the stock pool, which leads to high computational cost and unstable performance. To tackle this challenge, we propose EarnMore, a rEinforcement leARNing framework with Maskable stOck REpresentation to handle PM with CSPs through one-shot training in a global stock pool (GSP). Specifically, we first introduce a mechanism to mask out the representation of the stocks outside the target pool. Second, we learn meaningful stock representations through a self-supervised masking and reconstruction process. Third, a re-weighting mechanism is designed to make the portfolio concentrate on favorable stocks and neglect the stocks outside the target pool. Through extensive experiments on 8 subset stock pools of the US stock market, we demonstrate that EarnMore significantly outperforms 14 state-of-the-art baselines in terms of 6 popular financial metrics with over 40% improvement on profit.
cover:          /assets/images/covers/fake.png
authors:
  - Wentao Zhang
  - Yilei Zhao
  - Shuo Sun
  - Jie Ying
  - Yonggang Xie
  - Zitao Song
  - Xinrun Wang
  - Bo An
links:
  Paper: https://dl.acm.org/doi/abs/10.1145/3589334.3645615
  Code: https://github.com/DVampire/EarnMore
---
