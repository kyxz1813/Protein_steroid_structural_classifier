# Protein_steroid_structural_classifier
A structural classifier that predicts binding between protein steroid pair.

Steps:
1. Given the [postive dataset](positive_steroids_2025-07-01.csv) that contains pairs of proteins and steroids that are known to bind and [negative dataset](negative_steroids_2025-07-01.csv) that contains pairs of proteins and random molecules that not known to bind, apply [Protein Language Visualization (PLVis) Colab Notebook](https://colab.research.google.com/drive/1qCTuk2p9ow7efmYwUoZivqRcd1--ek14?usp=sharing) to cluster the data and get the centroid pairs for each of the positive and negative dataset.

2. 