# Representation Learning for Natural Language Processing

The course will start with a general introduction to NLP and its applications, either for natural language understanding or natural language generation. The course will provide the needed theoretical tools (i.e. elements of statistical learning & computer science) to understand the foundations of modern NLP techniques. As the class advances, the impact of NLP on society and the related ethical issues will be discussed.

## Learning vector space representations of words
- Distributional semantics
- Skip-Gram with negative sampling
  - Data
  - Model
  - Estimation procedure via contrastive learning
    - Penalized likelihood maximization
    - Stochastic gradient descent
- Link with the pointwise mutual information
- Connection with GloVe

## Supervised learning from text with convolutional neural networks
- Convolution 
  - Definition of convolution in the temporal domain
  - Definition of convolution in the spectral domain
    - Discrete Fourier transform
    - Convolution theorem
    - Fast Fourier transform
    - Efficient implementation of convolution & generalization to graph-structured data
- Convolution-based architecture
  - Input
  - Word representation layer
  - Parallel convolution-based layers
  - Pooling layer
  - Classification layer

## Supervised learning from text with recurrent neural networks
- Definition of a recurrent neural network
  - Transcoder network
  - Encoder network
  - Exploding/Vanishing gradient
- Gated recurrent unit (GRU)
  - Input
  - Forget gate
  - Candidate hidden state
  - Update gate
  - Output hidden state
- GRU-based architecture
  - Input
  - Word representation layer
  - GRU layer
  - Classification layer

## Text generation with encoder-decoder networks
- Encoder
- Decoder
  - Classification layer
  - Auto-regressive decoding
- Issues
- Cross-attention mechanism
  - Attention layer
  - Classification layer
- Training with teacher forcing
- Decoding with beam-search

## Transformer networks and large language models
- Multi-head self-attention
- Transformer block
- General architecture for text encoding
- Bidirectional language model for text understanding (e.g. BERT)
  - Pre-training
  - Fine-tuning
- Conditional language model for text generation (e.g. ChatGPT)
  - Pre-training
  - Fine-tuning via reinforcement learning with human feedback
