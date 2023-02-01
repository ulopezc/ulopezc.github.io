---
layout: page
title: Tableau practice
description: Covid19 Data Visualization
img: assets/img/TableauDashboard1cortado.png
importance: 3
category: fun
---

I embarked on this project with the intention of refreshing my Tableau skills and indulging in some creative exploration through the use of its visualizations.

This project focuses on analyzing and presenting insights on the Covid-19 vaccine distribution globally. To start, I created three key performance indicators (KPIs) to measure the progress of the vaccine distribution: partially vaccinated individuals, fully vaccinated individuals, and the percentage of unvaccinated individuals.
Additionally, I created a bar graph that showcases, in descending order, the countries with the highest number of vaccinated individuals, both partially and fully. This provides a clear visual of the leading countries in terms of vaccine distribution.
Furthermore, I utilized a map to display the level of vaccine distribution across countries, with a darker shade indicating higher levels of full vaccination.
Lastly, I plotted a trend line graph of vaccinated individuals per Gross Domestic Product (GDP) to present a comprehensive analysis of the relationship between vaccine distribution and economic prosperity."


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/TableauDashboard1.png" title="Dashboard1" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The dashboard with my three KPI and 3 graphs to showcase information about people fully, partly and not vaccinated
</div>

This Dashboard represents the final outcome of the project, where you can manipulate and customize the view by selecting different continents and date ranges through the use of filters.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
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
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
