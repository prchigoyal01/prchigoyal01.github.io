---
layout: page
title: Color Switch Game
description: JavaFX Game Development
img:
importance: 3
category: fun
---

<div style="font-family: Arial, sans-serif; line-height: 1.6;">
  <h2 style="text-decoration: underline; font-weight: bold;">Interactive Color-Switching Game Development</h2>
  
  <h3 style="text-decoration: underline; font-weight: bold;">Project Overview:</h3>
  <p>
    Designed and developed an engaging interactive color-switching game as a first full-scale project using <b>JavaFX</b>. 
    The project emphasized implementing user-friendly interface diagrams and structured class hierarchies to ensure a 
    smooth and interactive gaming experience.
  </p>
  
  <h3 style="text-decoration: underline; font-weight: bold;">Key Achievements:</h3>
  <ul>
    <li>
      <b>Game Development:</b> Built a dynamic and visually appealing game interface, leveraging <b>JavaFX</b> for creating 
      animations, event handling, and color-switching mechanics.
    </li>
    <li>
      <b>Object-Oriented Design:</b> Applied core Object-Oriented Programming (OOP) principles, including 
      <b>inheritance</b> and <b>abstraction</b>, to design robust and reusable gameplay mechanics.
    </li>
    <li>
      <b>User Interface Design:</b> Created and implemented detailed UI diagrams to enhance user engagement and 
      improve the overall gaming experience.
    </li>
  </ul>

  <h3 style="text-decoration: underline; font-weight: bold;">Tools & Technologies:</h3>
  <p>
    <b>Programming Language:</b> Developed the game using <b>Java</b>, showcasing strong proficiency in foundational programming concepts.<br>
    <b>Framework:</b> Utilized the <b>JavaFX library</b> for building the graphical user interface (GUI) and handling gameplay interactions.
  </p>

  <h3 style="text-decoration: underline; font-weight: bold;">Impact:</h3>
  <p>
    Successfully delivered a fully functional game, gaining hands-on experience in full-cycle development, from 
    conceptualization to implementation. This project served as a foundation for mastering JavaFX and OOP principles, 
    highlighting the ability to build interactive applications with well-structured code and efficient design.
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
