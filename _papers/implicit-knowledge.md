---
layout: single
title: "Is Implicit Knowledge Enough for LLMs? A RAG Approach for Tree-based Structures"
permalink: /papers/implicit-knowledge/
author_profile: true
date: 2025-10-12
excerpt: "Generating Implicit Knowledge results in more efficient vector database storage especially for hierarchial structures."
toc: true
toc_label: "Contents"
---

## Abstract

Large Language Models (LLMs) are adept at generating responses based on information within their context. While this ability is useful for interacting with structured data like code files, another popular method, Retrieval-Augmented Generation (RAG), retrieves relevant documents to augment the model's in-context learning. However, it is not well-explored how to best represent this retrieved knowledge for generating responses on structured data, particularly hierarchical structures like trees. In this work, we propose a novel bottom-up method to linearize knowledge from tree-like structures (like a GitHub repository) by generating implicit, aggregated summaries at each hierarchical level. This approach enables the knowledge to be stored in a knowledge base and used directly with RAG. We then compare our method to using RAG on raw, unstructured code, evaluating the accuracy and quality of the generated responses. Our results show that while response quality is comparable across both methods, our approach generates over 68% fewer documents in the retriever, a significant gain in efficiency. This finding suggests that leveraging implicit, linearized knowledge may be a highly effective and scalable strategy for handling complex, hierarchical data structures.

## Key Contributions

- Introduced a novel "bottom-up" summarization framework that converts tree-structured data (e.g., repository directory structures) into a linearized format suitable for standard RAG pipelines.
- Demonstrated a 68% reduction in the number of retrieved documents required for response generation without compromising the qualitative accuracy of the model's output.

## Links

- [arXiv Paper](https://arxiv.org/pdf/2510.10806) - Full paper PDF

## Citation

```
Gupte, Mihir, and Paolo Giusto. "Is Implicit Knowledge Enough for LLMs? A RAG Approach for Tree-based Structures." arXiv preprint arXiv:2510.10806 (2025).
```
