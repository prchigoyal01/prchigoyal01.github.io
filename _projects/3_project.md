---
layout: page
title: Image-to-Image Translation
description: Deep Learning
img: assets/img/7.jpg
importance: 3
category: work
---

<div style="font-family: Arial, sans-serif; line-height: 1.6;">
  
  <h3 style="text-decoration: underline; font-weight: bold;">Project Overview:</h3>
  <p>
    This project involved the development and evaluation of advanced deep learning models for 
    <b>Reverse Semantic Segmentation</b> and <b>Super Resolution tasks</b>, utilizing cutting-edge neural network architectures. 
    The primary objective was to generate high-quality outputs with enhanced detail and accuracy while optimizing for fast convergence during training.
  </p>
  
  <h3 style="text-decoration: underline; font-weight: bold;">Key Achievements:</h3>
  <ul>
    <li>
      <b>Model Implementation:</b> Successfully implemented and fine-tuned state-of-the-art models, including 
      <b>Pix2Pix</b>, <b>pSp Encoder</b>, and <b>SRGAN</b>, to address diverse challenges in reverse semantic segmentation and super-resolution tasks. 
      Delivered solutions that produced visually compelling and technically accurate results across different datasets.
    </li>
    <li>
      <b>Dataset Utilization:</b> Applied models to widely-used benchmark datasets such as <b>Cityscapes</b> for urban semantic 
      segmentation tasks and <b>CelebA-HQ</b> for high-resolution facial imagery, ensuring robustness and generalizability.
    </li>
    <li>
      <b>Optimization for Efficiency:</b> Designed and executed workflows to accelerate model convergence and reduce 
      computational overhead, achieving significant performance improvements. Enhanced the quality of output images by 
      refining loss functions and applying advanced training techniques.
    </li>
  </ul>

  <h3 style="text-decoration: underline; font-weight: bold;">Tools & Technologies:</h3>
  <p>
    <b>Deep Learning Frameworks:</b> Leveraged powerful neural network architectures like <b>Pix2Pix</b>, <b>pSp Encoder</b>, and <b>SRGAN</b>, 
    enabling accurate image-to-image translation and upscaling.<br>
    <b>Programming Languages:</b> Utilized <b>C#</b>, <b>.NET</b>, and <b>SQL</b> for data processing, backend implementation, and integration 
    with databases.<br>
    <b>Data Handling:</b> Employed <b>XML</b> for efficient data representation and manipulation, streamlining model evaluation workflows.
  </p>

  <h3 style="text-decoration: underline; font-weight: bold;">Impact:</h3>
  <p>
    Produced high-quality super-resolution images and semantically segmented reconstructions with exceptional fidelity, 
    setting a strong foundation for applications in computer vision and graphics. Demonstrated expertise in adapting 
    state-of-the-art AI techniques for practical applications, reinforcing a commitment to excellence in research and development.
  </p>

  <h3 style="text-decoration: underline; font-weight: bold;">Datasets:</h3>
  <p>
    <b>Cityscapes:</b> Addressed challenges in urban landscape segmentation, enabling precise modeling of complex environments.<br>
    <b>CelebA-HQ:</b> Focused on achieving photorealistic results for high-resolution human imagery, catering to advanced 
    use cases in image restoration and enhancement.


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
