---
layout: post
title:  "PointNet for Keras"
image: /images/pointnet.png
categories: project
code: https://github.com/HPInc/pointnet-keras
---
Keras implementation of the PointNet 3D classification network.
- Includes orthogonal regularization of features
- Optimized for fast training (1D convolutions and fast 2D max-pooling)
- Achieves similar rates of original paper (~88%-89% accuracy)