# scSCCNIA
We propose a novel contrastive clustering framework called scSCCNIA (Similarity-matrix-based Contrastive Clustering with Neighbor Information Aggregation), for accurate identify cell clusters from scRNA-seq data. scSCCNIA adopts a Laplacian filter to conduct neighbor information aggregation, constructs different graph views by using special un-shared parameters Siamese encoders for data augmentation, and learns the latent low-dimensional embedding representations via similarity-matrix-based contrastive learning. 

See details in our paper: "scSCCNIA: Similarity matrix based Contrastive Clustering with Neighbor Information Aggregation for Single-Cell RNA sequencing Data". 

Quick start:  
Download the datasets from the website as the paper described, and download the code files in this repository and import functions in them.  
1.Preprocess datasets  
scSCCNIA takes preprocessed data as input. Single cell data preprocessing can be done with preprocess.py.  
2.Run scSCCNIA algorithm with train.py. 

Requirements: 

python---3.7 
scanpy---1.7.2
numpy --- 1.21.2  
pandas --- 1.3.4
cosg---1.0.1
scikit-learn --- 1.0.2
matplotlib --- 3.5.0
torch==1.8.0
tqdm==4.61.2
munkres==1.1.4
scikit_learn==1.0
