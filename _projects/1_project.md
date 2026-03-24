---
layout: page
title: mechanics
description: 
img: assets/img/monarch_sequence_small.jpg
importance: 1
category: categories
related_publications: false
---

<strong>Scaling of musculoskeletal performance</strong>. Maximum force output by single muscles scales as body mass<sup>0.67</sup>, similar to how the surface area of an object scales with its mass. One consequence of this is that as (geometrically similar) animal body size increases occur, animal mass may outpace the maximum force production capacity of body mass-supporting muscles. Yet, maximum locomotor performance of whole animals scales as body mass<sup>1.0</sup> across a large range of body size, as demonstrated <a href="https://www.pnas.org/doi/10.1073/pnas.022052899">here</a>. Noteworthy, this study showed that a highly variable set of animal musculoskeletal designs have a remarkably consistent common upper limit to mass-specific force output during maximum performance. Why this is the case is not very evident, nor do we know much about how animals achieve this. 

We have previously examined this question in flying dragonflies (<a href="https://pubmed.ncbi.nlm.nih.gov/14747409/">here</a>), but they are not the only organisms that transmit force output by single muscles via musculoskeletal linkages (tendons and other skeletal components). Internal musculoskeletal dynamics and force distribution mechanisms inside animals are often unknown or at best understudied. We continue to investigate such mechanisms and dynamics in different types of animal motors, for one to establish to what extent the dragonfly “solution” to unequal scaling of single muscle force output and body weight support requirements is unique or more general among animals.

<!-- The maximum force exerted by a muscle is generally considered to be determined by its cross-sectional area, i.e., the number of actomyosin cross-bridges working in parallel. Based on this it is generally expected that locomotion of animals of increasing body size requires adjustments to muscle (mass-specific) performance, relative muscle investment and/or musculoskeletal posture, to facilitate appropriate body weight support across a body size range. 

Muscles rarely exert their forces directly on the environment and use lever systems whose associated mechanical advantage can enhance or reduce the forces required by muscles. Moreover, few musculoskeletal systems move animals using their maximum capacity for generating forces. Force output (needs) by intact musculoskeletal systems may be quite different than that of individual muscles, and the scaling of this force output may differ markedly from mass0.67, especially during locomotion. -->



<!--To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---
-->
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

<strong>Body weight sensation.</strong> A long term goal of the lab is to determine if/how animals know at a physiological level how much they weigh, and, if so, how they make homeostatic adjustments in response to changes in body weight. Skeletal muscle is a likely source tissue for this type of plasticity as well as for the location of required sensors, as weight-bearing muscles receive mechanical feedback regarding body weight and consume ATP in order to generate forces sufficient to (at least) counteract gravity.

We know that skeletal muscle can respond to increased and decreased load by hypertrophy and atrophy, but the molecular and biochemical mechanisms that muscles use to sense and adjust to changes in body weight are poorly understood. We focus our work in this area on the regulation of expression of sarcomere genes encoding proteins that function at the interface between thin and thick filaments. Specifically, we work on mechanisms controlling expression of the troponin complex, and within that, of troponin T. These thin filament regulatory proteins play a large role in regulating muscle force output and energy consumption by controlling the calcium sensitivity of actomyosin cross-bridge activation. The troponin T gene is alternatively spliced and gives rise to several splice variants that differ in way they encode troponin T proteins.

We have made some progress examining mechanisms involved in body weight sensation in rodents (see <a href="https://pubmed.ncbi.nlm.nih.gov/21490260/">here</a>), fruit flies (see <a hfref="https://pubmed.ncbi.nlm.nih.gov/28978639/">here</a>) and are currently extending this project using cockroaches as the study system.

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
