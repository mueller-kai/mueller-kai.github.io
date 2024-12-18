---
layout: archive
permalink: /publications/
author_profile: true
---

<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
 -->

# Projects
## Imageminer
In Imageminer we are learning causal relations from artificially generated high-dimensional production line data. 
For this we designed image generator functions that generate images based on a DAG where causal relations are known.
We learn the causal relations between the images back from the images/ timeseries data.
This research serves to establish concepts applicable to real-world production lines.
Manufacturers are particularly eager to pinpoint aspects within their production data, 
that influence whethera part is classified as OK or NOK
<img src="../images/imageminer.png" alt="imageminer" style="width: 70%;">

## Lineflow

In our project Lineflow, we are developing a flexible and extensible Python framework for simulating production lines. 
Our simulation can be controlled by an AI. The production line with the state of the cells and the parts as well as
the AI's actions are visualized.
We can use our framework to train an AI that automatically optimizes this production line towards a metric i.e. produced parts.

<img src="../images/line_flow.png" alt="Lineflow" style="width: 50%;">

## Masterthesis

My Masters thesis, also under the supervision of Tobias Windisch, 
focused on the optimization of production lines at Robert Bosch GmbH. I 
created a production line simulation using Python allowing me to simulate and 
predict potential line jams in advance using machine learning.

## Teaching
Furthermore, I am actively involved in academia, where I have the privilege of supervising students in a lecture dedicated to the use of AI in production systems.
