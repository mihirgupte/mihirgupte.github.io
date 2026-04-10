---
layout: single
title: "What Works for 'Lost-in-the-Middle' in LLMs? A Study on GM-Extract and Mitigations"
permalink: /papers/lost-in-middle/
author_profile: true
date: 2025-11-17
excerpt: "Creating a benchmark to test 'Lost-In-The-Middle' phenomenon and studying mitigations."
toc: true
toc_label: "Contents"
---

## Abstract

The diminishing ability of large language models (LLMs) to effectively utilize long-range context-the "lost-in-the-middle" phenomenon-poses a significant challenge in retrieval-based LLM applications. To study the impact of this phenomenon in a real-world application setting, we introduce GM-Extract, a novel benchmark dataset meticulously designed to evaluate LLM performance on retrieval of control variables. To accurately diagnose failure modes, we propose a simple yet elegant evaluation system using two distinct metrics: one for spatial retrieval capability (Document Metric) and the other for semantic retrieval capability (Variable Extraction Metric). We conduct a systematic evaluation of 7-8B parameter models on two multi-document tasks (key-value extraction and question-answering), demonstrating a significant change in retrieval performance simply by altering how the data is represented in the context window. While a distinct U-shaped curve was not consistently observed, our analysis reveals a clear pattern of performance across models, which we further correlate with perplexity scores. Furthermore, we perform a literature survey of mitigation methods, which we categorize into two distinct approaches: black-box and white-box methods. We then apply these techniques to our benchmark, finding that their efficacy is highly nuanced. Our evaluation highlights scenarios where these strategies successfully improve performance, as well as surprising cases where they lead to a negative impact, providing a comprehensive understanding of their utility in a practical context.

## Key Contributions

- Introduced GM-Extract benchmark for evaluating lost-in-the-middle phenomenon
- Proposed two evaluation metrics for spatial and semantic retrieval
- Systematic evaluation of 7-8B parameter models
- Comprehensive survey and analysis of mitigation strategies

## Links

- [arXiv Paper](https://arxiv.org/pdf/2511.13900) - Full paper PDF

## Citation

```
Gupte, Mihir, Eshan Dixit, Muhammad Tayyab, and Arun Adiththan. "What Works for'Lost-in-the-Middle'in LLMs? A Study on GM-Extract and Mitigations." arXiv preprint arXiv:2511.13900 (2025).
```
