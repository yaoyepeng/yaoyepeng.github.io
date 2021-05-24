---
title: "Understanding the Influence of Graph Kernels on Deep Learning Architecture: A Case Study of Flow-Based Network Attack Detection"
collection: publications
permalink: /publication/2019-08-05-paper-Understanding
date: 2019-08-05
venue: 'TrustCom/BigDataSE IEEE'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/8887382'
citation: 'Liya Su, Yepeng Yao, Zhigang Lu, Baoxu Liu: Understanding the Influence of Graph Kernels on Deep Learning Architecture: A Case Study of Flow-Based Network Attack Detection[C]//2019 18th IEEE International Conference On Trust, Security And Privacy In Computing And Communications/13th IEEE International Conference On Big Data Science And Engineering (TrustCom/BigDataSE). IEEE, 2019: 312-318.'
---

[Download paper here](https://ieeexplore.ieee.org/abstract/document/8887382)

Recommended citation: Liya Su, Yepeng Yao, Zhigang Lu, Baoxu Liu: Understanding the Influence of Graph Kernels on Deep Learning Architecture: A Case Study of Flow-Based Network Attack Detection[C]//2019 18th IEEE International Conference On Trust, Security And Privacy In Computing And Communications/13th IEEE International Conference On Big Data Science And Engineering (TrustCom/BigDataSE). IEEE, 2019: 312-318.

## Abstract

Network communication data are high-dimensional and spatiotemporal, and their information content is often degraded by common traffic analysis methods. For long-term network attack detection based on network flows, it is important to extract a discriminative, high-dimensional intrinsic representation of such flows. This work focuses on a hybrid deep neural network design using a combination of a convolutional neural network (CNN) and long short-term memory (LSTM) with graph similarity measures to learn high-dimensional representations from the network traffic. In particular, examining a set of network flows, we commence by constructing a temporal communication graph and then computing graph kernel matrices. Having obtained the kernel matrices, for each graph, we use the kernel value between graphs and calculate graph characterization vectors by graph signal processing. This vector can be regarded as a kernel-based similarity embedding vector of the graph that integrates structural similarity information and leverages efficient graph kernel using the graph Laplacian matrix. Our approach exploits graph structures as the additional prior information, the graph Laplacian matrix for feature extraction and hybrid deep learning models for long-term information learning on communication graphs.
Experiments on two real-world network attack datasets show that our approach can extract more discriminative representations, leading to an improved accuracy in a supervised classification task. The experimental results show that our method increases the overall accuracy by approximately 10%-15%.