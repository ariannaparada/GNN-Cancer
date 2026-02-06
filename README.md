# GNN-Cancer
MSc Thesis on use of GNNs for pancreatic cancer tumor grades, grades I-IV, classification utilizing histopathology whole slide images (WSIs)


This project investigates whether graph neural networks (GNNs), in combination with advanced feature extraction strategies,
can improve the automated grading of pancreatic cancer from haematoxylin and eosin (H&E) whole slide images (WSIs). 
A complete pipeline was developed using The Cancer Genome Atlas (TCGA) dataset, encompassing tiling of WSIs, 
feature extraction, graph construction, and GNN training. Three feature extraction methods were compared:
a visual constrastive learning framework (SimCLR) with a ResNet18 framework, a convolutional baseline (ResNet50), and a
histopathology-specific foundation model (UNI). Two graph construction strategies were evaluated: spatial graphs preserving morphological adjacency,
and embedding graphs linking patches by feature similarity.

<img width="806" height="354" alt="Screenshot 2026-02-06 at 15 54 52" src="https://github.com/user-attachments/assets/1a651be7-75dd-4887-a58d-a9ce738c1b78" />
