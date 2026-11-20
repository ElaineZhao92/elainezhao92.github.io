---
title:          "FilingLoop: Evaluating and Evolving LLM Agents for Corporate Disclosure Review and Revision"
date:           2026-10-27
selected:       true
tags:           ["# AI4Finance", "# LLM Agents", "# Self-evolving Systems"]
# pub:            "Proceedings of SIGKDD Conference on Knowledge Discovery and Data Mining (KDD), 2026"
# presentation:     "Poster"
# pub_pre:        "Submitted to "
pub_post:       'Under review.'
# pub_date:       "2026"
# semantic_scholar_id: 204e3073870fae3d05bcbc2f6a8e263d9b72e776  # use this to retrieve citation count
abstract: >-
  Public disclosure repositories such as SEC EDGAR support informed investment through web access to corporate filings. Supporting their review with language model agents requires discovering unstated deficiencies across related documents, acquiring missing company facts, and verifying that requested revisions satisfy evidence-backed requirements. Existing financial question-answering evaluations provide limited evidence of these interactive capabilities. We introduce FilingLoop, an interactive benchmark and a self-evolving agent framework for corporate disclosure review and revision. Grounded in historical U.S. Securities and Exchange Commission correspondence, FilingLoop reconstructs 380 predominantly IPO review tasks from 96 companies under distinct information constraints. An evaluator separate from the acting agents scores final filings and responses against 6,099 eligible requirements and audits unsupported claims and harmful revisions. Our framework couples iterative review and revision within each case with procedural learning across cases, converting requirement-level evaluation feedback into role-specific guidance without updating model weights. Updates affect only subsequent cases, allowing procedural adaptation to be assessed without retrying scored tasks. On the evaluated stream, evolution increases requirement fulfillment from 24.28% to 27.96% and full comment resolution from 16.90% to 20.75%, with a 5.8% increase in total cost over the fixed-policy variant. FilingLoop connects the concerns an agent discovers with the company facts it obtains and the revisions it commits, providing requirement-level feedback for procedures used in later review tasks.

cover:          /images/filingloop.png
authors:
  - Wentao Zhang
  - Yilei Zhao
  - Guangyan Gan
  - Shuo Sun
  - Lin William Cong#
links:
  Paper: https://arxiv.org/pdf/2610.37905
---