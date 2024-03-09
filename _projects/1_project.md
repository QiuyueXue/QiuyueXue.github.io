---
layout: page
title: Thermal Earring
description: a project with a background image
img: assets/img/12.jpg
importance: 1
category: work
related_publications: true
---

Body temperature is an important vital sign which can indicate fever and is known to be correlated with activities such as eating, exercise and stress. However, continuous temperature monitoring poses a significant challenge.

We present Thermal Earring, a first-of-its-kind smart earring that enables a reliable wearable solution for continuous temperature monitoring. The Thermal Earring takes advantage of the unique position of earrings in proximity to the head, a region with tight coupling to the body unlike watches and other wearables which are more loosely worn on extremities. We develop a hardware prototype in the form factor of real earrings measuring a maximum width of 11.3 mm and a length of 31 mm, weighing 335 mg, and consuming only 14.4 uW which enables a battery life of 28 days in real-world tests. We demonstrate this form factor is small and light enough to integrate into real jewelry with fashionable designs. Additionally, we develop a dual sensor design to differentiate human body temperature change from environmental changes. We explore the use of this novel sensing platform and find its measured earlobe temperatures are stable within ±0.32 °C during periods of rest. Using these promising results, we investigate its capability of detecting fever by gathering data from 5 febrile patients and 20 healthy participants. Further, we perform the first-ever investigation of the relationship between earlobe temperature and a variety of daily activities, demonstrating earlobe temperature changes related to eating and exercise. We also find the surprising result that acute stressors such as public speaking and exams cause measurable changes in earlobe temperature. We perform multi-day in-the-wild experiments and confirm the temperature changes caused by these daily activities in natural daily scenarios. This initial exploration seeks to provide a foundation for future automatic activity detection and earring-based wearables.



    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/publication_preview/ThermalEarring.jpg
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
<!-- 
You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.
 -->
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
