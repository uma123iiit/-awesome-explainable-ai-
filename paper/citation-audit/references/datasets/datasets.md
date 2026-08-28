## 📊 Datasets

The following datasets and benchmarks are selected for studying and evaluating hallucinations in Large Language Models (LLMs). They cover different aspects of hallucination research, including factuality, truthfulness, hallucination detection, and evaluation across multiple tasks.

| # | Dataset / Benchmark | What It Contains                                                                                                                                                                             | Why It Is Relevant                                                                                                                                                                            | Official Link                                       |
| - | ------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------- |
| 1 | **HaluEval**        | A large-scale benchmark containing **35,000 generated and human-annotated samples**, covering question answering, knowledge-grounded dialogue, text summarization, and general user queries. | Directly relevant to hallucination research because it provides labeled hallucinated and non-hallucinated examples for studying hallucination detection and different hallucination patterns. | [HaluEval](https://github.com/RUCAIBox/HaluEval)    |
| 2 | **TruthfulQA**      | A benchmark containing questions designed to test whether language models produce truthful answers rather than answers based on common misconceptions.                                       | Relevant for evaluating **factual and knowledge-based hallucinations** and measuring whether an LLM produces false or misleading information.                                                 | [TruthfulQA](https://github.com/sylinrl/TruthfulQA) |
| 3 | **FActScore Data**  | Human-annotated factuality data and supporting resources for evaluating factual precision in long-form language-model generation.                                                            | Relevant for **factuality evaluation** because it enables researchers to examine whether individual claims in generated text are supported by reliable knowledge sources.                     | [FActScore](https://github.com/shmsw25/FActScore)   |

### 🔎 Dataset Selection Criteria

The datasets were selected based on:

* **Relevance to LLM hallucination research**
* **Availability of data and annotations**
* **Research-paper association**
* **Usefulness for hallucination detection or factuality evaluation**
* **Reproducibility and accessibility**
* **Coverage of different LLM generation tasks**

> **Note:** The datasets are external resources maintained by their respective authors or organizations. Users should refer to the official repositories and accompanying research papers for dataset licenses, terms of use, and citation requirements.
