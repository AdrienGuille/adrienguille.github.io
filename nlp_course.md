# Representation Learning for NLP - 2024/2025 course

This course provides a general overview of natural language processing. 
We first review seminal works regarding vector space representation of words and deep neural network. 
We then study the foundations of modern NLP, i.e. principles of large language models and how to adapt them to diverse tasks.

### Pre-LLM Era

#### Learning vector space representations of words

- Skip-Gram with Negative Sampling: [Distributed Representations of Words and Phrases and their Compositionality](https://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf)
- Glove: [Global Vectors for Word Representation](https://nlp.stanford.edu/pubs/glove.pdf)
- Link between Skip-Gram with Negative Sampling, GloVe & PMI: [Neural Word Embedding as Implicit Matrix Factorization](https://papers.nips.cc/paper/5477-neural-word-embedding-as-implicit-matrix-factorization.pdf)

#### Leveraging pre-trained word representations for supervised learning

##### Basic architectures for text classification 

- Basic Convolutional Architecture: [Convolutional Neural Networks for Sentence Classification](https://arxiv.org/pdf/1408.5882.pdf)
- Gated Recurrent Unit: [Learning Phrase Representations using RNN Encoder-Decoder for Statistical Machine Translation](https://arxiv.org/pdf/1406.1078.pdf)

##### Advanced architecture for text generation

- Encoder-Decoder Architecture: [Sequence to Sequence Learning with Neural Networks](https://papers.nips.cc/paper/2014/file/a14ac55a4f27472c5d894ec1c3c743d2-Paper.pdf)
- Attention Mechanism: [Effective Approaches to Attention-based Neural Machine Translation](https://arxiv.org/pdf/1508.04025.pdf)

### LLM Era

#### Foundation models 

- Attention-based Encoder-Decoder (Transformer): [Attention is All You Need](https://arxiv.org/pdf/1706.03762.pdf)
- Pre-trained Encoder (BERT): [Bidirectional Encoder Representations from Transformers](https://arxiv.org/pdf/1810.04805.pdf)
- Pre-trained Decoder (GPT): [Language Models are Unsupervised Multitask Learners](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf)
- Pre-trained Encoder-Decoder (T5): [Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer](https://arxiv.org/pdf/1910.10683)

#### Adapting foundation models

- Reinforcement Learning from Human Feedback (RLHF): [Training language models to follow instructions with human feedback](https://arxiv.org/pdf/2203.02155)
- Direct Preference Optimization (DPO): [Your Language Model is Secretly a Reward Model](https://arxiv.org/pdf/2305.18290)
- Retrieval-Augmented Generation (RAG): [Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks](https://arxiv.org/pdf/2005.11401)
- Low-Rank Adaptation (LoRA): [Low-Rank Adaptation of Large Language Models](https://arxiv.org/pdf/2106.09685)
