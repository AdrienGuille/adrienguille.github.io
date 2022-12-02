# Natural Language Processing

The course will start with a general introduction to NLP and its applications, either for natural language understanding or natural language generation. The course will provide the needed theoretical tools to understand the foundations (i.e. elements of statistical learning & computer science) of modern NLP techniques. As the class advances, the impact of NLP on society and the related ethical issues will be discussed.

## Learning vector space representations of words
- Distributional semantics
- Skip-Gram with negative sampling
  - Data
  - Model
  - Estimation procedure via contrastive leanring
    - Penalized likelihood maximization
    - Stochastic gradient descent
- Link with the pointwise mutual information
- Connection with GloVe

## Supervised learning from text with convolutional neural networks
- Convolution 
  - Definition of convolution in the temporal domain
  - Definition of convolution in the Fourier domain
    - Discrete Fourier transform
    - Convolution theorem
    - Fast Fourier transform
- Convolution-based architecture
  - Input
  - Word representation layer
  - Parallel convolution-based layers
  - Pooling layer
  - Classification layer

## Supervised learning from text with recurrent neural networks
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
  - Classificaiton layer

## Multi-head self-attention and Transformer networks
- Multi-head self-attention
- Transformer block
- General architecture for text encoding
- Deep language models
  - Pre-training
  - Fine-tuning
