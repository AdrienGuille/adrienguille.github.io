# Graph-Based NLP

In this series of works we revisit classical natural language processing tasks by casting them as tasks defined on graphs.

## Contributions

In one research direction, we've proposed a graph-based approach to document classification, using a hierarchical GNN operating in the hyperbolic space ; we've also proposed a GNN-RNN architecture for extractive document summarization (presented at ECIR 2024). In another research direction, we've highlighted the capacity of pre-trained language models to linearly encode parts of the structure of AMR (abstract meaning representation) graphs in the attention mechanism (presented at *SEM 2024); we've also developped a GNN-based approach to learn to map the internal attention graphs computed by LLMs to AMR graphs (presentend at NLPIR 2025). Recently, we've started started working on automatic AMR parsing, specifically for the French language (work presented at TALN 2026).

### Selected Publications
- [Un décodeur pour l’analyse sémantique AMR en français](#) by Thomas Checchin, Julien Jacques, Adrien Guille. *33e Conférence sur le Traitement Automatique des Langues Naturelles (TALN)*, Nantes (France), 2026
- [Probing Attention in Pre-Trained LLMs to Detect Semantics](https://link.springer.com/book/9783032208965) by Frédéric Charpentier, Jairo Cugliari, Adrien Guille. *9th International Conference on Natural Language Processing and Information Retrieval (NLPIR)*, Fukuoka (Japan), 2025 - **Best student paper award**
- [Interactive Document Summarization with GNN-RNN](publications/ecir2024.pdf) by Raoufdine Said, Adrien Guille. *European Conference on Information Retrieval (ECIR)*, 2024 - **Core A**
- [Exploring Semantics in Pretrained Language Model Attention]() by Frédéric Charpentier, Jairo Cugliari, Adrien Guille. *13th Joint Conference on Lexical and Computational Semantics, co-located with NAACL (StarSEM @ NAACL)*, 2024
- [Classification de documents par un réseau de neurones opérant sur des graphes dans l'espace hyperbolique](publications/egc_hhgnn.pdf) by Adrien Guille, Hugo Attali. *Conférence sur l'Extraction et la Gestion des Connaissances (EGC)*, 2023
- [Document Classification with Hierarchical Graph Neural Networks](publications/docgat.pdf) by Adrien Guille, Hugo Attali. *18th International Workshop on Mining and Learning with Graphs (MLG @ ECML-PKDD)*, 2022

### Code & Models
- Interactive Document Summarization with GNN-RNN: [https://github.com/Baragouine/radsum]()
- Exploring Semantics in Pretrained Language Model Attention: [https://anonymous.4open.science/r/sem_LM_att-322F/]()
- Probing Attention in Pre-Trained LLMs to Detect Semantics: [https://github.com/frcharpentier/GAS]()
- Un décodeur pour l’analyse sémantique AMR en français: [v1 (16 bit)](https://huggingface.co/AdrienGuille/GemmAMR-fr-v1), [v1 (8 bit GPTQ)](https://huggingface.co/AdrienGuille/GemmAMR-fr-v1-w8a16), [v1 (4 bit GPTQ)](https://huggingface.co/AdrienGuille/GemmAMR-fr-v1-w4a16)
