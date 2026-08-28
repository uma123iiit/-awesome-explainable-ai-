# Curated Research Papers: LLM Hallucinations

This collection contains 20 unique scholarly papers related to hallucinations, factuality, detection, evaluation, and mitigation in Large Language Models (LLMs). The papers are organized according to major research directions relevant to the topic **“A Taxonomy of Hallucination Types in Large Language Models for Research Applications.”**

---

## 1. Survey and Review Papers

### 1.1 Survey of Hallucination in Natural Language Generation

**Authors:** Ziwei Ji, Nayeon Lee, Rita Frieske, Tiezheng Yu, Dan Su, Yan Xu, Etsuko Ishii, Ye Jin Bang, Andrea Madotto, Pascale Fung
**Year:** 2023
**Journal:** ACM Computing Surveys

[Paper / DOI](https://doi.org/10.1145/3571730)

Provides a comprehensive survey of hallucination in natural language generation, covering its definitions, causes, detection methods, and mitigation strategies.

---

### 1.2 A Survey on Hallucination in Large Language Models: Principles, Taxonomy, Challenges, and Open Questions

**Authors:** Lei Huang, Weijiang Yu, Weitao Ma, Weihong Zhong, Zhangyin Feng, Haotian Wang, Qianglong Chen, Weihua Peng, Xiaocheng Feng, Bing Qin, Ting Liu
**Year:** 2023
**Venue:** arXiv

[Paper](https://arxiv.org/abs/2311.05232)

Provides an LLM-focused taxonomy of hallucinations and reviews their causes, detection approaches, benchmarks, mitigation techniques, and open research problems.

---

### 1.3 A Survey of Hallucination in Large Foundation Models

**Authors:** Vipula Rawte, Amit Sheth, Amitava Das
**Year:** 2023
**Venue:** arXiv

[Paper](https://arxiv.org/abs/2309.05922)

Reviews hallucination phenomena in large foundation models and discusses hallucination types, evaluation strategies, causes, and mitigation methods.

---

### 1.4 Factuality of Large Language Models: A Survey

**Authors:** Yuxia Wang, Minghan Wang, Muhammad Arslan Manzoor, Fei Liu, Georgi Nenkov Georgiev, Rocktim Jyoti Das, Preslav Nakov
**Year:** 2024
**Venue:** EMNLP 2024

[Paper / DOI](https://doi.org/10.18653/v1/2024.emnlp-main.1088)

Surveys the factuality of LLMs, including causes of factual errors, factuality evaluation, and methods for improving the reliability of generated text.

---

## 2. Foundational Papers

### 2.1 On Faithfulness and Factuality in Abstractive Summarization

**Authors:** Joshua Maynez, Shashi Narayan, Bernd Bohnet, Ryan McDonald
**Year:** 2020
**Venue:** ACL 2020

[Paper / DOI](https://doi.org/10.18653/v1/2020.acl-main.173)

Demonstrates that abstractive summarization systems can generate content that is unsupported by their input documents, providing an important foundation for hallucination research.

---

### 2.2 Evaluating the Factual Consistency of Abstractive Text Summarization

**Authors:** Wojciech Kryscinski, Bryan McCann, Caiming Xiong, Richard Socher
**Year:** 2020
**Venue:** EMNLP 2020

[Paper / DOI](https://doi.org/10.18653/v1/2020.emnlp-main.750)

Introduces a model-based approach for detecting factual inconsistencies between generated summaries and their source documents and releases a factual-consistency dataset and model.

---

### 2.3 FEQA: A Question Answering Evaluation Framework for Faithfulness Assessment in Abstractive Summarization

**Authors:** Esin Durmus, He He, Mona Diab
**Year:** 2020
**Venue:** ACL 2020

[Paper / DOI](https://doi.org/10.18653/v1/2020.acl-main.454)

Introduces a question-answering-based method for evaluating whether generated summaries are faithful to their source documents.

---

### 2.4 Asking and Answering Questions to Evaluate the Factual Consistency of Summaries

**Authors:** Alex Wang, Kyunghyun Cho, Mike Lewis
**Year:** 2020
**Venue:** ACL 2020

[Paper / DOI](https://doi.org/10.18653/v1/2020.acl-main.450)

Introduces QAGS, which evaluates factual consistency by comparing answers derived from a generated summary with answers derived from its source document.

---

## 3. Recent Research Papers

### 3.1 TruthfulQA: Measuring How Models Mimic Human Falsehoods

**Authors:** Stephanie Lin, Jacob Hilton, Owain Evans
**Year:** 2022
**Venue:** ACL 2022

[Paper / DOI](https://doi.org/10.18653/v1/2022.acl-long.229)

Introduces the TruthfulQA benchmark for measuring whether language models produce truthful responses instead of reproducing common misconceptions and false beliefs.

---

### 3.2 HaluEval: A Large-Scale Hallucination Evaluation Benchmark for Large Language Models

**Authors:** Junyi Li, Xiaoxue Cheng, Xin Zhao, Jian-Yun Nie, Ji-Rong Wen
**Year:** 2023
**Venue:** EMNLP 2023

[Paper / DOI](https://doi.org/10.18653/v1/2023.emnlp-main.397)

Introduces HaluEval, a large benchmark of generated and human-annotated hallucinated samples for studying and evaluating hallucination recognition in LLMs.

---

### 3.3 SelfCheckGPT: Zero-Resource Black-Box Hallucination Detection for Generative Large Language Models

**Authors:** Potsawee Manakul, Adian Liusie, Mark Gales
**Year:** 2023
**Venue:** EMNLP 2023

[Paper / DOI](https://doi.org/10.18653/v1/2023.emnlp-main.557)

Proposes a black-box hallucination detection method based on inconsistencies across multiple sampled responses without requiring an external knowledge database.

---

### 3.4 FActScore: Fine-grained Atomic Evaluation of Factual Precision in Long Form Text Generation

**Authors:** Sewon Min, Kalpesh Krishna, Xinxi Lyu, Mike Lewis, Wen-tau Yih, Pang Koh, Mohit Iyyer, Luke Zettlemoyer, Hannaneh Hajishirzi
**Year:** 2023
**Venue:** EMNLP 2023

[Paper / DOI](https://doi.org/10.18653/v1/2023.emnlp-main.741)

Introduces a fine-grained factuality metric that decomposes long-form generated text into atomic facts and checks their support from reliable sources.

---

### 3.5 Enabling Large Language Models to Generate Text with Citations

**Authors:** Tianyu Gao, Howard Yen, Jiatong Yu, Danqi Chen
**Year:** 2023
**Venue:** EMNLP 2023

[Paper / DOI](https://doi.org/10.18653/v1/2023.emnlp-main.398)

Introduces ALCE, a benchmark for evaluating LLM-generated answers with citations in terms of fluency, correctness, and citation quality, making it highly relevant to research reliability.

---

### 3.6 Chain-of-Verification Reduces Hallucination in Large Language Models

**Authors:** Shehzaad Dhuliawala, Mojtaba Komeili, Jing Xu, Roberta Raileanu, Xian Li, Asli Celikyilmaz, Jason Weston
**Year:** 2023
**Venue:** arXiv

[Paper](https://arxiv.org/abs/2309.11495)

Introduces Chain-of-Verification (CoVe), a multi-step verification procedure designed to detect and reduce hallucinated information in generated responses.

---

### 3.7 Detecting Hallucinations in Large Language Models Using Semantic Entropy

**Authors:** Sebastian Farquhar, Jannik Kossen, Lorenz Kuhn, Yarin Gal
**Year:** 2024
**Journal:** Nature

[Paper / DOI](https://doi.org/10.1038/s41586-024-07421-0)

Introduces semantic entropy as an uncertainty-based approach for detecting hallucinations by measuring disagreement in the meanings of generated answers.

---

### 3.8 RAGTruth: A Hallucination Corpus for Developing Trustworthy Retrieval-Augmented Language Models

**Authors:** Cheng Niu, Yuanhao Wu, Juno Zhu, Siliang Xu, KaShun Shum, Randy Zhong, Juntong Song, Tong Zhang
**Year:** 2024
**Venue:** ACL 2024

[Paper / DOI](https://doi.org/10.18653/v1/2024.acl-long.585)

Introduces an annotated corpus for studying hallucinations in retrieval-augmented generation systems and evaluating hallucination detection and mitigation methods.

---

## 4. Methods / Algorithms

### 4.1 Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks

**Authors:** Patrick Lewis, Ethan Perez, Aleksandra Piktus, Fabio Petroni, Vladimir Karpukhin, Naman Goyal, Heinrich Küttler, Mike Lewis, Wen-tau Yih, Tim Rocktäschel, Sebastian Riedel, Douwe Kiela
**Year:** 2020
**Venue:** NeurIPS 2020

[Paper](https://papers.nips.cc/paper/2020/hash/6b493230205f780e1bc26945df7481e5-Abstract.html)

Introduces Retrieval-Augmented Generation (RAG), which combines language models with retrieved external knowledge to improve knowledge-intensive generation and grounding.

---

### 4.2 ReAct: Synergizing Reasoning and Acting in Language Models

**Authors:** Shunyu Yao, Jeffrey Zhao, Dian Yu, Nan Du, Izhak Shafran, Karthik R. Narasimhan, Yuan Cao
**Year:** 2023
**Venue:** ICLR 2023

[Paper](https://openreview.net/forum?id=WE_vluYUL-X)

Combines reasoning traces with external actions such as information retrieval, helping LLMs obtain evidence from external sources and reducing some hallucination and error-propagation problems.

---

### 4.3 Self-RAG: Learning to Retrieve, Generate, and Critique through Self-Reflection

**Authors:** Akari Asai, Zeqiu Wu, Yizhong Wang, Avirup Sil, Hannaneh Hajishirzi
**Year:** 2024
**Venue:** ICLR 2024

[Paper](https://openreview.net/forum?id=hSyW5go0v8)

Introduces a framework that combines adaptive retrieval, generation, and self-reflection to improve factuality and citation accuracy in LLM outputs.

---

### 4.4 FreshLLMs: Refreshing Large Language Models with Search Engine Augmentation

**Authors:** Tu Vu, Mohit Iyyer, Xuezhi Wang, Noah Constant, Jerry Wei, Jason Wei, Chris Tar, Yun-Hsuan Sung, Denny Zhou, Quoc Le, Thang Luong
**Year:** 2024
**Venue:** Findings of ACL 2024

[Paper / DOI](https://doi.org/10.18653/v1/2024.findings-acl.813)

Studies search-engine augmentation as a way to supply LLMs with current information and address errors caused by outdated or incomplete parametric knowledge.

---

## 5. Applications

### 5.1 Lost in the Middle: How Language Models Use Long Contexts

**Authors:** Nelson F. Liu, Kevin Lin, John Hewitt, Ashwin Paranjape, Michele Bevilacqua, Fabio Petroni, Percy Liang
**Year:** 2024
**Journal:** Transactions of the Association for Computational Linguistics

[Paper / DOI](https://doi.org/10.1162/tacl_a_00638)

Shows that LLM performance can degrade when relevant information occurs in the middle of long contexts, highlighting an important reliability issue for document- and research-oriented applications.

---

### 5.2 Measuring Attribution in Natural Language Generation Models

**Authors:** Hannah Rashkin, Vitaly Nikolaev, Matthew Lamm, Lora Aroyo, Michael Collins, Dipanjan Das, Slav Petrov, Gaurav Singh Tomar, Iulia Turc, David Reitter
**Year:** 2023
**Journal:** Computational Linguistics

[Paper](https://aclanthology.org/2023.cl-4.6/)

Introduces the Attributable to Identified Sources (AIS) framework for evaluating whether generated statements about the external world are supported by a provided source, which is highly relevant to trustworthy research generation.

---

## 6. Evaluation Methods / Benchmarks

### 6.1 TRUE: Re-evaluating Factual Consistency Evaluation

**Authors:** Or Honovich, Roee Aharoni, Jonathan Herzig, Hagai Taitelbaum, Doron Kukliansy, Vered Cohen, Thomas Scialom, Idan Szpektor, Avinatan Hassidim, Yossi Matias
**Year:** 2022
**Venue:** NAACL 2022

[Paper / DOI](https://doi.org/10.18653/v1/2022.naacl-main.287)

Provides a standardized evaluation of factual-consistency metrics across diverse datasets and tasks, making it useful for benchmarking hallucination and factuality evaluation methods.

---

### 6.2 SummaC: Re-Visiting NLI-based Models for Inconsistency Detection in Summarization

**Authors:** Philippe Laban, Tobias Schnabel, Paul N. Bennett, Marti A. Hearst
**Year:** 2022
**Journal:** Transactions of the Association for Computational Linguistics

[Paper / DOI](https://doi.org/10.1162/tacl_a_00453)

Introduces SummaC and the SummaCConv method for detecting inconsistencies in generated summaries using natural-language inference.

---

### 6.3 VeriScore: Evaluating the Factuality of Verifiable Claims in Long-Form Text Generation

**Authors:** Yixiao Song, Yekyung Kim, Mohit Iyyer
**Year:** 2024
**Venue:** Findings of EMNLP 2024

[Paper / DOI](https://doi.org/10.18653/v1/2024.findings-emnlp.552)

Introduces a factuality metric designed to evaluate long-form generation containing both verifiable and unverifiable claims, making it relevant to research-oriented text generation.

---

## Summary

The 20 papers in this collection cover the major dimensions of LLM hallucination research:

* **Definitions and taxonomies**
* **Factuality and faithfulness**
* **Hallucination detection**
* **Evaluation and benchmarking**
* **Citation and source attribution**
* **Retrieval and grounding**
* **Hallucination mitigation**
* **Research-oriented reliability**

These papers provide the literature foundation for the research topic **“A Taxonomy of Hallucination Types in Large Language Models for Research Applications.”**

