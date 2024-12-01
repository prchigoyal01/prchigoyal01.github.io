---
layout: page
title: Handwriting Recognition
description: Deep Learning
img:
importance: 4
category: Development/Industrial Projects
---

<div style="font-family: Arial, sans-serif; line-height: 1.6;">
  <h2 style="text-decoration: underline; font-weight: bold;">Handwriting Recognition Model Development</h2>
  
  <h3 style="text-decoration: underline; font-weight: bold;">Project Overview:</h3>
  <p>
    Developed a handwriting recognition model, achieving an accuracy of <b>85%</b>. The project applied advanced concepts from 
    Andrew Ng’s <b>Deep Learning Specialization</b> to address the challenges of recognizing sequential handwritten text data.
  </p>
  
  <h3 style="text-decoration: underline; font-weight: bold;">Key Achievements:</h3>
  <ul>
    <li>
      <b>Model Architecture:</b> Implemented a hybrid <b>CNN-BLSTM</b> (Convolutional Neural Network with Bidirectional Long Short-Term Memory) 
      architecture, combining spatial feature extraction with sequential data analysis for high accuracy.
    </li>
    <li>
      <b>Advanced Loss Function:</b> Utilized <b>Connectionist Temporal Classification (CTC)</b> for effective sequential data recognition, 
      allowing the model to handle variable-length sequences without requiring pre-segmented data.
    </li>
    <li>
      <b>Performance Evaluation:</b> Achieved 85% accuracy, demonstrating the model’s capability to reliably interpret handwritten text.
    </li>
  </ul>

  <h3 style="text-decoration: underline; font-weight: bold;">Tools & Technologies:</h3>
  <p>
    <b>Programming Language:</b> Developed the model using <b>Python</b>, showcasing proficiency in deep learning and data processing.<br>
    <b>Framework:</b> Leveraged <b>Keras</b> for building and training the neural network, ensuring efficient prototyping and evaluation.
  </p>

  <h3 style="text-decoration: underline; font-weight: bold;">Impact:</h3>
  <p>
    Delivered a robust handwriting recognition system capable of interpreting sequential data, setting a foundation for applications in 
    document digitization and automated text processing. This project strengthened expertise in deep learning architectures 
    and sequential data modeling techniques.
  </p>
</div>


    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

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
