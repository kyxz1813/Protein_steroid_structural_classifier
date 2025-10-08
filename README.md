# Protein Steroid Structural Classifier
A structural classifier that predicts binding between protein steroid pair.

## Steps:
### 1. Clustering
- Given the [postive dataset](positive_steroids_2025-07-01.csv) that contains pairs of proteins and steroids that are known to bind and [negative dataset](negative_steroids_2025-07-01.csv) that contains pairs of proteins and random molecules that not known to bind, apply [Protein Language Visualization (PLVis) Colab Notebook](https://colab.research.google.com/drive/1qCTuk2p9ow7efmYwUoZivqRcd1--ek14?usp=sharing) to cluster the data and get the centroid pairs to create [representative positive pairs](positive_centroids_2025-07-01.csv) and [representative negative pairs](negative_centroids_2025-07-01.csv).

### 2. Create Yaml Files to run Boltz