---
layout: single
title: "Towards Autoformalization of LLM-generated Outputs for Requirement Verification"
permalink: /papers/towards-autoformalization/
author_profile: true
date: 2025-11-14
excerpt: "Can LLMs be used to formally verify their own outputs?"
toc: true
toc_label: "Contents"
---

## Abstract

Autoformalization, the process of translating informal statements into formal logic, has gained renewed interest with the emergence of powerful Large Language Models (LLMs). While LLMs show promise in generating structured outputs from natural language (NL), such as Gherkin Scenarios from NL feature requirements, there's currently no formal method to verify if these outputs are accurate. This paper takes a preliminary step toward addressing this gap by exploring the use of a simple LLM-based autoformalizer to verify LLM-generated outputs against a small set of natural language requirements. We conducted two distinct experiments. In the first one, the autoformalizer successfully identified that two differently-worded NL requirements were logically equivalent, demonstrating the pipeline's potential for consistency checks. In the second, the autoformalizer was used to identify a logical inconsistency between a given NL requirement and an LLM-generated output, highlighting its utility as a formal verification tool. Our findings, while limited, suggest that autoformalization holds significant potential for ensuring the fidelity and logical consistency of LLM-generated outputs, laying a crucial foundation for future, more extensive studies into this novel application.

## Key Contributions

- Proposed a preliminary framework for the formal verification of LLM-generated outputs by leveraging autoformalization to bridge the gap between Natural Language (NL) requirements and formal logic.
- Demonstrated that LLM-based autoformalizers can effectively detect logical equivalence between semantically diverse but logically identical NL requirements.

## Links

- [arXiv Paper](https://arxiv.org/pdf/2511.11829) - Full paper PDF

## Citation

```
Gupte, Mihir. "Towards autoformalization of llm-generated outputs for requirement verification." arXiv preprint arXiv:2511.11829 (2025).
```
