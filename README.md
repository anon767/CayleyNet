# Torch Geometric CayleyNet

CayleyNet is a Graph Convolutional Layer with complex rational spectral filters.
https://arxiv.org/pdf/1705.07664.pdf

The convolutional layer is integrated as a Pytorch Geometric Module. It is based on following implementations:

-  https://github.com/amoliu/CayleyNet/blob/master/CayleyNet.ipynb
-  https://github.com/WhiteNoyse/SiGCN/blob/master/models/spectral_nn.py

It uses the Jacobi method for an approximate eigen decomposition

## Requirements

- Pytorch Geometric

