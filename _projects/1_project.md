---
layout: page
title: Federated Learning with unannotated data
description: Nazreen Shah*; Prachi Goyal*; Ranjitha Prasad
img: assets/img/12.jpg
importance: 1
category:
related_publications: true
---

<section id="abstract">
  <h2><b>Abstract</b></h2>
  <p>
    The era of pervasive intelligence, driven by AI, has brought smart devices into everyday life. Federated Learning (FL) enables machine learning at the edge without sharing private user data with untrusted third parties. While traditional FL relies on supervised methods and annotated data, our approach focuses on learning representations from unlabelled data for downstream tasks.
  </p>
  <p>
    We introduce <b>IS-FedVAE</b>, a novel FL framework using importance sampling to federate a global Variational AutoEncoder (VAE). This framework learns a global latent space distribution from local edge distributions. The representations are evaluated using a linear probe, showing superior performance compared to state-of-the-art unsupervised FL baselines. IS-FedVAE is scalable, robust to heterogeneity, and efficient across varying numbers of clients and local epochs.
  </p>
  <h3><b>Key Highlights:</b></h3>
  <ul>
    <li><b>Innovative Algorithm Design:</b> Utilized VAEs to model clients' unlabelled, non-IID data as Gaussian distributions.</li>
    <li><b>Advanced Aggregation Technique:</b> Employed mean-field formulation and importance sampling for precise loss computation.</li>
    <li><b>Performance Excellence:</b> Achieved faster convergence and higher accuracy, surpassing SoTA FL baselines.</li>
  </ul>
  <p>
    This work, published in <b>ICASSP 2024</b>, combines cutting-edge machine learning with robust mathematics, advancing FL for personalized and unsupervised tasks.
  </p>
</section>


<a href="https://ieeexplore.ieee.org/abstract/document/10447119">Paper Link</a>
<a href="https://ieeexplore.ieee.org/abstract/document/10447119">Github Link</a>
