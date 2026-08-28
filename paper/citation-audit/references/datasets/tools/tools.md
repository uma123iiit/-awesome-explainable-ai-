## 🛠️ Tools and Libraries

The following tools and libraries provide practical support for developing, evaluating, and analyzing Large Language Model (LLM) systems. They are particularly relevant to hallucination detection, factuality evaluation, Retrieval-Augmented Generation (RAG), and overall LLM application evaluation.

| # | Tool / Library | Purpose                                                                                                                                                                                        | Official / Project Link                               |
| - | -------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------- |
| 1 | **Ragas**      | Provides evaluation tools for RAG and LLM applications, with metrics for evaluating aspects such as response quality and the relationship between generated answers and retrieved information. | [Official Documentation](https://docs.ragas.io/)      |
| 2 | **DeepEval**   | Provides an open-source framework for evaluating LLM applications with metrics for hallucination, faithfulness, relevance, safety, and other evaluation criteria.                              | [Official Documentation](https://deepeval.com/)       |
| 3 | **TruLens**    | Provides tools for evaluating and monitoring LLM applications, including RAG systems, with metrics, feedback functions, and runtime evaluation capabilities.                                   | [Official Documentation](https://www.trulens.org/)    |
| 4 | **LangChain**  | Provides frameworks and components for building LLM applications, including retrieval pipelines and RAG systems that can ground model responses in external information.                       | [Official Documentation](https://docs.langchain.com/) |
| 5 | **LlamaIndex** | Provides tools for connecting LLMs with external data and building RAG applications, enabling retrieval of relevant context before generating responses.                                       | [Official Documentation](https://docs.llamaindex.ai/) |

### 🔎 Relevance to Hallucination Research

* **Ragas** — Useful for evaluating RAG systems and assessing whether generated responses are supported by retrieved information.
* **DeepEval** — Directly provides hallucination and faithfulness metrics for evaluating LLM-generated outputs.
* **TruLens** — Supports evaluation and runtime checks for LLM applications, including RAG and agent-based systems.
* **LangChain** — Provides retrieval and RAG building blocks that can ground LLM responses using external knowledge.
* **LlamaIndex** — Provides RAG functionality for connecting LLMs with external data and retrieving relevant context for generation.

> **Note:** These are external open-source tools and libraries maintained by their respective projects. Their source code, documentation, and licenses remain subject to the terms specified by each project.

