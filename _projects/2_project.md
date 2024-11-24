---
layout: page
title: Multi-Agent Deep Reinforcement Github Learning)
description: Intersection Problem in Highway-Env
img: assets/img/3.jpg
importance: 2
category: work
giscus_comments: true
---


    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<b>Overview:</b>
<br>
This project focuses on applying multi-agent deep reinforcement learning (MARL) techniques to address the critical challenge of safe and efficient intersection handling in autonomous vehicle systems within complex highway environments. The goal was to enable multiple intelligent agents (representing autonomous vehicles) to interact cooperatively and navigate through busy intersections without colliding or violating traffic rules, ensuring both safety and efficiency.

<b>Key Contributions:</b>
<br>
Design & Architecture: Developed a robust multi-agent reinforcement learning model utilizing state-of-the-art architectures like Double Q-Networks (DQN) with hard-parameter sharing. The model enabled agents to effectively learn and optimize their decision-making process in a shared environment, where each agent's actions impacted others, ensuring a cooperative and coordinated approach to intersection navigation.

Cooperative Decision-Making: Implemented hard-parameter sharing across multiple agents, allowing them to share a common neural network architecture. This approach improved training efficiency and encouraged collaborative behavior, where agents were incentivized to cooperate for mutual benefits such as minimizing wait times and avoiding collisions.

Reward Shaping & Performance Optimization: Custom-designed reward functions to improve agent behavior by incentivizing safe, efficient driving while penalizing undesirable actions (e.g., accidents, traffic violations). These tailored rewards enhanced the overall performance of the system and facilitated faster convergence to optimal policies.

Algorithm Enhancements: Utilized advanced reinforcement learning techniques, including Double Q-Learning, to mitigate overestimation bias in action-value functions, leading to more stable and reliable training. Further optimized the model with techniques such as experience replay and target network updates to improve learning efficiency and agent coordination.

<b>Tools & Technologies:</b>
<br>
Python: Developed the full pipeline for data processing, training, and evaluation using Python.
Gym: Used OpenAI Gym for simulating complex highway environments, providing a customizable and flexible interface for multi-agent system development.
Stable Baselines: Leveraged Stable Baselines for efficient implementation and training of reinforcement learning models, ensuring fast prototyping and reliable results.
Keras: Utilized Keras for building and training deep neural networks, enabling efficient model training and evaluation.
Outcome & Impact:

Achieved significant improvements in agent performance, with trained models successfully navigating intersections without collisions and minimizing traffic delays.
Demonstrated the feasibility of cooperative decision-making in complex, dynamic environments, highlighting the potential for real-world applications in autonomous driving and traffic management systems.
Optimized the model for scalability, allowing for easy adaptation to more complex environments and larger-scale traffic systems.



<a href="https://github.com/prchigoyal01/RL_PROJECT_HIGHWAY">Github link</a>

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

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
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
