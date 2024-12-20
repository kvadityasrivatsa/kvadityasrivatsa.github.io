---
title: "SelectLLM: Query-Aware Efficient Selection Algorithm for Large Language Models"
collection: publications
category: preprints
permalink: /publication/selectllm
excerpt: 'Introduces SelectLLM, a novel query-aware algorithm that optimally selects LLM subsets to efficiently leverage their diverse strengths, achieving competitive accuracy with significantly reduced latency on reasoning benchmarks.'
date: 2024-08-16
venue: 'arXiv'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://arxiv.org/abs/2412.09416'
citation: 'M. K. Kumar, K. A. Srivatsa, and E. Kochmar, “SelectLLM: Query-Aware Efficient Selection Algorithm for Large Language Models,” arXiv.org, 2024. https://arxiv.org/abs/2408.08545'
---

Large language models (LLMs) have gained increased popularity due to their remarkable success across various tasks, which has led to the active development of a large set of diverse LLMs. However, individual LLMs have limitations when applied to complex tasks because of such factors as training biases, model sizes, and the datasets used. A promising approach is to efficiently harness the diverse capabilities of LLMs to overcome these individual limitations. Towards this goal, we introduce a novel LLM selection algorithm called SelectLLM. This algorithm directs input queries to the most suitable subset of LLMs from a large pool, ensuring they collectively provide the correct response efficiently. SelectLLM uses a multi-label classifier, utilizing the classifier's predictions and confidence scores to design optimal policies for selecting an optimal, query-aware, and lightweight subset of LLMs. Our findings show that the proposed model outperforms individual LLMs and achieves competitive performance compared to similarly sized, computationally expensive top-performing LLM subsets. Specifically, with a similarly sized top-performing LLM subset, we achieve a significant reduction in latency on two standard reasoning benchmarks: 13% lower latency for GSM8K and 70% lower latency for MMLU. Additionally, we conduct comprehensive analyses and ablation studies, which validate the robustness of the proposed model. 