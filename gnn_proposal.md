# Machine Learning with Graph-Structured Data

The course will start with a quick introduction to graph theory. The course will provide the needed theoretical tools (i.e. elements of statistical learning & computer science) to understand the foundations of modern techniques to learn from graph-structured data.

This is a course I give to CS and Physics M2 students @ ENS Lyon.

## Learning vector space representations of vertices
- Distributional semantics
- Random walks over graphs
- Skip-Gram with negative sampling
  - Data
  - Model
  - Estimation procedure via contrastive learning
    - Penalized likelihood maximization
    - Stochastic gradient descent
- Link with the pointwise mutual information

## (Semi-)Supervised learning from graph data with convolutional neural networks
- Convolution on grid-structured data
  - Definition of convolution in the spatial domain
  - Definition of convolution in the spectral domain
    - Discrete Fourier transform
    - Convolution theorem
- Pseudo-convolution on graph-structured data
  - Graph Fourier transform
  - Spectral analogy
- Convolution-based architectures
  - Chebychev approximation
  - Linear approximation (i.e. GCN)

## (Semi-)Supervised learning from graph data with attentional neural networks
- Attention mechanism
  - Origins
  - Definition
- Graph Attention Layer (i.e. GAT)
  - Issues and limited expressivness
  - Correction (i.e. GATv2)
- Graph Transformer Networks

## Over-squashing and bottleneck phenomenon
- Issues related to the depth of GNNs
- Mitigating over-squashing in GNNs
- Identifying and mitigating bottlenecks via graph curvature

