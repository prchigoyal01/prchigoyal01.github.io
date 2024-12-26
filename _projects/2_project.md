---
layout: page
title: Multi-Agent Deep Reinforcement Learning
description: Intersection Problem in Highway-Env
img: assets/img/3.jpg
importance: 2
category:
---

<section id="overview">
  <h2><b>Overview</b></h2>
  <p>
    This project applies multi-agent deep reinforcement learning (MARL) to tackle the challenge of safe and efficient intersection handling in autonomous vehicle systems. The focus is on enabling multiple intelligent agents (autonomous vehicles) to cooperate and navigate busy intersections safely, adhering to traffic rules while minimizing delays.
  </p>
  <h3><b>Key Contributions</b></h3>
  <ul>
    <li>
      <b>Design & Architecture:</b> Developed a robust MARL model leveraging Double Q-Networks (DQN) with hard-parameter sharing. This architecture enabled agents to learn coordinated decision-making in shared environments, promoting safety and efficiency.
    </li>
    <li>
      <b>Cooperative Decision-Making:</b> Implemented shared neural network architectures across agents to encourage collaborative behavior, minimizing wait times and avoiding collisions.
    </li>
    <li>
      <b>Reward Shaping & Optimization:</b> Designed custom reward functions to incentivize safe driving and penalize undesirable actions, improving overall system performance and accelerating convergence.
    </li>
    <li>
      <b>Algorithm Enhancements:</b> Applied advanced techniques like Double Q-Learning to reduce overestimation bias, and utilized experience replay and target network updates for stable and efficient training.
    </li>
  </ul>
  <h3><b>Tools & Technologies</b></h3>
  <ul>
    <li><b>Python:</b> Full pipeline for data processing, training, and evaluation.</li>
    <li><b>Gym:</b> Simulated complex highway environments using OpenAI Gym.</li>
    <li><b>Stable Baselines:</b> Efficient implementation and training of reinforcement learning models.</li>
    <li><b>Keras:</b> Built and trained deep neural networks for efficient model development.</li>
  </ul>
  <h3><b>Outcome & Impact</b></h3>
  <ul>
    <li>Trained models successfully navigated intersections without collisions and minimized traffic delays.</li>
    <li>Showcased cooperative decision-making in dynamic environments, demonstrating potential for real-world autonomous driving applications.</li>
    <li>Optimized the model for scalability, enabling adaptation to larger and more complex traffic systems.</li>
  </ul>
</section>




<a href="https://github.com/prchigoyal01/RL_PROJECT_HIGHWAY">Github</a>
<br>
<a href="https://drive.google.com/file/d/1EZH6mZrEvem8xYCtHjYQXJLxp7aKg3WB/view?usp=sharing">Slides</a>


