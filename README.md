# Self-Supervised Learning for Avian Diversity Monitoring SC22

This repository contains several Jupyter notebooks as well as python scripts to replicate all the experiments shown in the poster presented in SC22.


All the sofware in this repo is devoted to running experiments on the data generated by running inference on a teacher network from DINO [1].

DINO is a Joint-Embedding approach using Vision Transformers (ViTs).

Basically here you will have:

* `Attention` Run a pre-trained teacher to generate attentional maps
* `Attentional Maps and Clusters Visualization` Clusters and Maps visualizations
* `Clustered Data Set` Locate spectrograms from different clusters in different folders
* `Clusterization` Generate the clusterization from the data
* `Find Similar Samples` Find similar spectrograms to one *chosen* spectrogram in the output space from DINOs inference


[1] Mathilde Caron, Hugo Touvron, Ishan Misra, Herve Jegou, Julien Mairal, Piotr Bojanowski,
and Armand Joulin. Emerging properties in self-supervised vision transformers, 2021.
