## 💻 GitHub Implementations

This section provides publicly available GitHub implementations related to Large Language Model (LLM) hallucination detection, factuality evaluation, benchmarking, and mitigation. These implementations support practical understanding and reproducibility of the concepts discussed in this taxonomy.

| # | Repository       | What It Implements                                                                                                                                                           | Why It Is Relevant                                                                                                                                                                                    | Link                                                  |
| - | ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------- |
| 1 | **FActScore**    | Implements fine-grained factuality evaluation by breaking long-form generated text into atomic facts and measuring the proportion of facts supported by reliable sources.    | Directly supports the evaluation of factual hallucinations and provides a practical method for measuring factual precision in LLM-generated content.                                                  | [GitHub](https://github.com/shmsw25/FActScore)        |
| 2 | **TruthfulQA**   | Implements a benchmark for testing whether language models produce truthful answers to questions designed to trigger common misconceptions and false beliefs.                | Relevant for studying factual and knowledge-based hallucinations and evaluating whether an LLM generates false or misleading information.                                                             | [GitHub](https://github.com/sylinrl/TruthfulQA)       |
| 3 | **RAGAS**        | Implements evaluation metrics and tools for Retrieval-Augmented Generation (RAG) systems, including measures related to faithfulness, context relevance, and answer quality. | Relevant to hallucination mitigation because RAG grounds LLM responses in retrieved information and provides methods for evaluating whether generated answers are supported by the retrieved context. | [GitHub](https://github.com/explodinggradients/ragas) |
| 4 | **SelfCheckGPT** | Implements a black-box hallucination detection approach that compares multiple sampled responses from an LLM to identify inconsistencies in generated claims.                | Relevant to detecting hallucinations without requiring access to the model's internal probabilities or hidden states, making it useful for practical black-box evaluation.                            | [GitHub](https://github.com/potsawee/selfcheckgpt)    |
| 5 | **HaluEval**     | Implements a benchmark and evaluation framework containing hallucinated and non-hallucinated examples across multiple NLP tasks and domains.                                 | Relevant for studying different hallucination patterns and evaluating the ability of models or detection systems to identify hallucinated content.                                                    | [GitHub](https://github.com/RUCAIBox/HaluEval)        |

### 🔎 Implementation Categories

The repositories can be broadly categorized according to their role in hallucination research:

* **Hallucination Detection:** SelfCheckGPT, HaluEval
* **Factuality Evaluation:** FActScore, TruthfulQA
* **RAG Evaluation:** RAGAS
* **Benchmarking:** TruthfulQA, HaluEval
* **Hallucination Mitigation:** RAGAS

> **Note:** These are external GitHub implementations maintained by their respective authors or organizations. Their source code, datasets, documentation, and licenses remain subject to the terms specified in their respective repositories.
