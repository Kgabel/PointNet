# PointNet

This repository contains a PyTorch implementation of PointNet for point cloud classification and segmentation.

Overview
PointNet is a pioneering deep learning architecture that directly operates on point clouds by learning point-wise features and combining them through max pooling operations. This allows the network to be invariant to input permutation.

Key components implemented:

PointNetEncoder - Encodes point features through linear layers
PointNetModule - Combines global and local point features
PointNetFull - Implements a T-Net to learn input transforms
IoU - Computes per-class and mean IoU for evaluation
KITTI dataset loading and preprocessing

##Getting Started
##Dependencies
PyTorch
NumPy
OS file operations

@article{qi2017pointnet,
  title={Pointnet: Deep learning on point sets for 3d classification and segmentation},
  author={Qi, Charles R and Su, Hao and Mo, Kaichun and Guibas, Leonidas J},
  journal={Proc. Computer Vision and Pattern Recognition (CVPR), IEEE},
  year={2017}
}
