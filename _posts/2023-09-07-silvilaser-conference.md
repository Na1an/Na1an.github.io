---
layout: post
title: "An oral presentation on SilviLaser: LEAF/WOOD DISCRIMINATION IN ULS LIDAR USING NEURAL NETWORK"
--

I was invited to give an oral presentation on the conference SilviLaser 2023. The topic is: 

LEAF/WOOD DISCRIMINATION IN ULS LIDAR USING NEURAL NETWORK

Separating leaf from wood returns in forest lidar point cloud is a commonly required pre-processing step to estimate leaf area or wood volume. This key step is particularly challenging in tall dense hyper-diverse evergreen forests.

Unmanned aerial vehicle laser scanning (ULS) has emerged as a premium solution to collect high density point clouds (~10^3/m2) rapidly over several hectares of forest. However, the level of detail remains much lower than what is typically achieved using multiple TLS positions (~10^5/m2). In particular in the lower canopy.

In this study, we compared three semantic segmentation procedures applied to TLS and DLS point cloud over one-ha of moist tropical forest in French Guiana. Both point clouds were acquired in October 2021. A subset of 418 trees were manually isolated in the TLS point cloud and a semi-automatic segmentation of leaf and wood returns was conducted on each isolated tree. Labels were then transferred to the co-registered ULS point cloud based on nearest neighbours. These two datasets (TLS and ULS) were used as a reference to evaluate the three algorithms.

The three procedures to evaluate were 1) A geometric leaf-wood classification method (Lewos) 2) a deep learning (DL) approach (Forest Structural Complexity Tool: FSCT) and 3) A DL algorithm we developed. The latter was based on PointNet++ that combines convolution networks on 3D point clouds, quantitative information attached to each point and prior spatial and geometrical and topological information related to the neighbourhood of each point.

We compare the three models in terms of their performance in separating leaf from wood, in TLS and DLS point clouds. We further discuss which features of our DL approach allow it to outperform the other two methods for the designated task.
