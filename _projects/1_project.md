---
layout: page
title: Intersection Problem in Highway-Env (Multi-Agent Deep Reinforcement Github Learning)
description: Nazreen Shah*; Prachi Goyal*; Ranjitha Prasad
img: assets/img/12.jpg
importance: 1
category: work
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

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
