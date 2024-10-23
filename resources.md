---
title: Reference
permalink: /resources/
datavis_builder1: images/resources/datavis_builder1.png
datavis_builder2: images/resources/datavis_builder2.png
---

# Upcoming lab teachings

....



# DataVis Builder

<img width="300" src="{{site.baseurl}}/{{page.datavis_builder1}}" data-action="zoom"> 

DataVis Builder ([http://bioinformatics.vip/](http://bioinformatics.vip/)) is an intuitive drag-and-drop web tool for creating interactive, customizable data visualizations without coding expertise. It offers a variety of bioinformatics analysis and visualization tools to assist researchers in processing and interpreting biological data.

<img width="300" src="{{site.baseurl}}/{{page.datavis_builder2}}" data-action="zoom"> 

Using the DataVis Builder web tool, you can perform various bioinformatics analyses such as genome sequence analysis, transcriptome analysis, protein structure prediction, and more. Additionally, it provides several commonly used data visualization tools, allowing you to present your analysis results in the form of charts or graphs for better understanding and communication of your research findings.

With this tool, you can utilize its functionalities and algorithms to process, analyze, and visualize biological data to support your research work. Remember to reference and cite the DataVis Builder website and the algorithms and tools used to ensure the accuracy and credibility of your research.

# Older Blog posts from the lab

<div class="content list">
  {% for post in site.posts %}
    {% if post.categories contains 'newblog' %}
    <div class="list-item">
      <p class="list-post-title">
        <a href="{{ site.baseurl }}{{ post.url }}">- {{ post.title }}</a> (<small>{{post.date | date: "%m/%d/%y" }}</small>)
      </p>
    </div>
    {% endif %}
  {% endfor %}
  {% for post in site.posts %}
    {% if post.categories contains 'blog' %}
    <div class="list-item">
      <p class="list-post-title">
        <a href="{{ site.baseurl }}{{ post.url }}">- {{ post.title }}</a> (<small>{{post.date | date: "%m/%d/%y" }}</small>)
      </p>
    </div>
​    {% endif %}
  {% endfor %}
</div>


<hr>

