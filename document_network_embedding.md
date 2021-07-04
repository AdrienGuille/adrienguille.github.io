Adrien Guille — [Index](index.html) - [Research](research.html) - [Teaching](teaching.html) - [Publications](publications.html) - [Code](code.html)

# Document Network Embedding

Document network embedding aims at learning low dimensional representations of documents that are connected by links, taking their content and the network structure into account.  These representations can then serve in downstream tasks, such as document clustering or link prediction.

## Contributions

First, we've designed a matrix factorization-based method that learns document and word embeddings jointly, GVNR-t (presented at WWW 2019). Second, we've developped a neural, attention-based, approach that also learns document and word embeddings jointly, while learning topics that help reducing the computational cost and help improving interpretability, IDNE (presented at ECIR 2020). We've also studied how to efficiently project documents in a pre-trained word embedding space (work presented at ECIR 2020), and how to embed documents when csome ontent and/or links are partially missing (work presented at SAC 2020).

### Selected Publications
- [Global Vectors for Node Representations](https://arxiv.org/pdf/1902.11004.pdf) by Robin Brochier, Adrien Guille, Julien Velcin. *International ACM World Wide Web Conference (WWW)*, 2019 - **Core A\***
- [Inductive Document Network Embedding with Topic-Word Attention](https://arxiv.org/pdf/2001.03369.pdf) by Robin Brochier, Adrien Guille, Julien Velcin. *European Conference on Information Retrieval (ECIR)*, 2020 - **Core A**
- [Document Network Projection in Pretrained Word Embedding Space](https://arxiv.org/pdf/2001.05727.pdf) by Antoine Gourru, Adrien Guille, Julien Velcin, Julien Jacques. *European Conference on Information Retrieval (ECIR)*, 2020 - **Core A**
- [Document Network Embedding: Coping for Missing Links and Missing Content](https://arxiv.org/pdf/1912.03048.pdf) by Jean Dupuy, Adrien Guille, Julien Jacques. Presented at the student competition, *International ACM Symposium on Applied Computing (SAC)*, 2020 - **Core B**

### Code
- Global Vectors for Node Representations: https://github.com/brochier/gvnr
- Inductive Document Network Embedding with Topic-Word Attention: https://github.com/brochier/idne
- Document Network Projection in Pretrained Word Embedding Space: https://github.com/AntoineGourru/DNEmbedding