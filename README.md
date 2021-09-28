# GNN-Implementation

Graph Neural Networks (GNNs) are a class of neural network architectures used for deep learn ing on graph-structured data. Broadly, GNNs aim to generate high-quality embeddings of nodes by iteratively aggregating feature information from local graph neighborhoods using neural net works; embeddings can then be used for recommendations, classification, link prediction or other downstream tasks. Two important types of GNNs are GCNs (graph convolutional networks) and GraphSAGE (graph sampling and aggregation).

In the project, the GCN (Graph Convolutional Network), GAT (Graph Attention Network) and GraphSage is implemented. Also each layer of all these architectures is been implemented. 

Have run GNN training for node classification task on the CORA and graph classification task on ENZYMES dataset, for all three architectures. Used Torch Geometric implementation for GCN, and my own implementations for
GraphSage and GAT. 

During the analysis, it was found that for CORA dataset GAT outperformed the rest while for ENZYMES dataset GraphSage was showing better results that the other two
