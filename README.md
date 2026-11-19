# Awesome Quantum [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of papers on quantum machine learning, with a focus on quantum methods for deep learning, information retrieval (IR), and retrieval-augmented generation (RAG) with large language models.

## Contents

- [Quantum Deep Learning for LLMs](#quantum-deep-learning-for-llms)
- [Quantum IR and QNLP Surveys](#quantum-ir-and-qnlp-surveys)
- [Quantum-Inspired Retrieval and RAG](#quantum-inspired-retrieval-and-rag)
- [Quantum Search and Dequantization Foundations](#quantum-search-and-dequantization-foundations)
- [RAG for Quantum Computing](#rag-for-quantum-computing)
- [Classical RAG Background](#classical-rag-background)

## Quantum Deep Learning for LLMs

| Title | Authors | Year | Link |
|-------|---------|------|------|
| How Can Quantum Deep Learning Improve Large Language Models? | Emily Jimin Roh, Hyojun Ahn, Samuel Yen-Chi Chen, Soohyun Park, Joongheon Kim | 2025 | [arXiv](https://arxiv.org/abs/2509.16244) |

## Quantum IR and QNLP Surveys

Background on quantum-theoretic representations, ranking, and language processing. Quantum-inspired models can run on classical hardware; they should be distinguished from algorithms executed on quantum processors.

| Title | Authors | Year | Link |
|-------|---------|------|------|
| A Survey of Quantum Theory Inspired Approaches to Information Retrieval | Sagar Uprety, Dimitris Gkoumas, Dawei Song | 2020 | [arXiv](https://arxiv.org/abs/2007.04357) |
| Natural Language Processing Meets Quantum Physics: A Survey and Categorization | Sixuan Wu, Jian Li, Peng Zhang, Yue Zhang | 2021 | [EMNLP](https://aclanthology.org/2021.emnlp-main.254/) |
| A Systematic Survey of Quantum Natural Language Processing: Models, Encoding Paradigms, and Evaluation Methods | Arpita Vats, Rahul Raja, Ashish Kattamuri, Abhinav Bohra | 2025 | [QuantumNLP](https://aclanthology.org/2025.quantumnlp-1.8/) |
| A Survey of Quantum Natural Language Processing: From Compositional Models to NISQ-Era Empiricism | Arpan Phukan, Asif Ekbal | 2025 | [QuantumNLP](https://aclanthology.org/2025.quantumnlp-1.9/) |

## Quantum-Inspired Retrieval and RAG

Methods and evaluations related to document representations, retrieval adaptation, ranking, and RAG. The following entries are linked to arXiv preprints; inclusion does not establish hardware execution or quantum computational advantage.

| Title | Authors | Year | Link |
|-------|---------|------|------|
| Quantum-RAG and PunGPT2: Advancing Low-Resource Language Generation and Retrieval for the Punjabi Language | Jaskaranjeet Singh, Rakesh Thakur | 2025 | [arXiv](https://arxiv.org/abs/2508.01918) |
| On the Representational Limits of Quantum-Inspired 1024-D Document Embeddings: An Experimental Evaluation Framework | Dario Maio | 2026 | [arXiv](https://arxiv.org/abs/2604.09430) |
| QuPID: Quantum Parameter-Efficient Input-Dependent Retrieval Adaptation for Medical RAG | Hyojun Ahn, Emily Jimin Roh, Soohyun Park, Walid Saad, Hyung-Chul Lee, Joongheon Kim | 2026 | [arXiv](https://arxiv.org/abs/2609.33351) |
| Quantum-Inspired Pairwise Ranking Aggregation via Active LLM Feedback | Quan Mai, Susan Gauch, Gibson Nkhata | 2026 | [arXiv](https://arxiv.org/abs/2610.38683) |

- **Punjabi Quantum-RAG:** Combines sparse, dense, and quantum-inspired kernel retrieval for a low-resource language.
- **Representational limits:** Evaluates quantum-inspired embeddings and reports weak or unstable standalone ranking signals on the studied corpora; useful context for baseline selection.
- **QuPID:** Uses input-dependent circuit transformations and measurement readouts to adapt frozen image features. The reported implementation trains with classical circuit simulation and performs inference on a GPU.
- **LLM-IRA:** Uses selective pairwise LLM feedback to learn retrieval-score fusion weights within a quantum-inspired ranking aggregation framework.

## Quantum Search and Dequantization Foundations

Foundational context for assessing computational claims. Oracle-query complexity and data-access assumptions must be distinguished from end-to-end retrieval cost; these papers are not RAG implementations.

| Title | Authors | Year | Link |
|-------|---------|------|------|
| A fast quantum mechanical algorithm for database search | Lov K. Grover | 1996 | [arXiv](https://arxiv.org/abs/quant-ph/9605043) |
| A quantum-inspired classical algorithm for recommendation systems | Ewin Tang | 2019 | [STOC](https://doi.org/10.1145/3313276.3316310), [arXiv](https://arxiv.org/abs/1807.04271) |

Tang's paper first appeared as a preprint in 2018; the year above refers to the STOC publication.

## RAG for Quantum Computing

Applications of retrieval-augmented language models to quantum software and code generation. Here, quantum computing is the application domain; these entries should not be treated as evidence of quantum-accelerated retrieval.

| Title | Authors | Year | Link |
|-------|---------|------|------|
| Model-Driven Quantum Code Generation Using Large Language Models and Retrieval-Augmented Generation | Nazanin Siavash, Armin Moin | 2025 | [MODELS](https://doi.org/10.1109/MODELS67397.2025.00031), [arXiv](https://arxiv.org/abs/2508.21097) |
| Quantum-Rag: Retrieval-Augmented Generation Framework for Quantum Circuit Code Generation | Nicholas Stapleton, Sharmin Afrose, Ethan Seefried, Vicente Leyton Ortega, Travis S. Humble, Tirthankar Ghosal | 2026 | [DCAS](https://doi.org/10.1109/DCAS69364.2026.11544968), [ORNL](https://impact.ornl.gov/en/publications/quantum-rag-retrieval-augmented-generation-framework-for-quantum-/) |

## Classical RAG Background

A foundational reference for the retrieval-generation interface, included as background rather than a quantum method.

| Title | Authors | Year | Link |
|-------|---------|------|------|
| Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks | Patrick Lewis, Ethan Perez, Aleksandra Piktus, Fabio Petroni, Vladimir Karpukhin, Naman Goyal, Heinrich Küttler, Mike Lewis, Wen-tau Yih, Tim Rocktäschel, Sebastian Riedel, Douwe Kiela | 2020 | [NeurIPS](https://papers.neurips.cc/paper/2020/file/6b493230205f780e1bc26945df7481e5-Paper.pdf), [arXiv](https://arxiv.org/abs/2005.11401) |

## Contributing

Contributions are welcome. Please open a pull request with the paper title, authors, year and link.
