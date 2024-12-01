---
layout: page
title: Federated Learning with unannotated data
description: Nazreen Shah*; Prachi Goyal*; Ranjitha Prasad
img: assets/img/12.jpg
importance: 1
category: Research Projects
related_publications: true
---

<b>Abstract:</b>
The use of AI has led to the era of pervasive intelligence, marked by a proliferation of smart devices in our daily lives. Federated Learning (FL) enables machine learning at the edge without having to share user-specific private data with an untrusted third party. Conventional FL techniques are supervised learning methods, where a fundamental challenge is to ensure that data is reliably annotated at the edge. Another approach is to obtain rich and informative representations of unlabeled data, which is suitable for downstream tasks. We propose a novel IS-FedVAE framework where we use importance sampling to federate a global VAE framework, allowing us to learn the global latent space distribution using local latent space distributions at the edge. We evaluate the representation in a stand-alone manner using linear probe, where we freeze the backbone representation and measure the accuracy of a downstream classifier. Furthermore, we demonstrate that IS-FedVAE outperforms state-of-the-art unsupervised FL learning baselines. We also show that IS-FedVAE is insensitive to varying levels of heterogeneity, scalable to varying numbers of clients, and robust to the changing number of local epochs.


This project introduced Is-FedVAE, a novel Federated Learning (FL) algorithm for unsupervised and personalized representation learning, published in ICASSP 2024. The algorithm addresses challenges posed by unlabelled and non-IID data in federated environments, achieving faster convergence and superior accuracy compared to state-of-the-art (SoTA) FL baselines.

Key highlights of the project include:

Innovative Algorithm Design: Developed a novel approach leveraging Variational AutoEncoders (VAEs) to model clients' unlabelled and non-IID data as Gaussian distributions.
Advanced Aggregation Technique: Employed mean-field formulation to aggregate distributions and used importance sampling-based weights for precise reconstruction loss computation.
Performance Excellence: Demonstrated significantly faster convergence and higher accuracy, setting a new benchmark for FL algorithms.
This work combines advanced machine learning techniques with robust mathematical formulations, showcasing the potential of federated learning for personalized and unsupervised representation tasks.

<a href="https://ieeexplore.ieee.org/abstract/document/10447119">Paper Link</a>
<a href="https://ieeexplore.ieee.org/abstract/document/10447119">Github Link</a>
