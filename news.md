---
title: News
permalink: /news/
logo: images/news/mpu_logo.png
---

# Join Us

<img width="50" src="{{site.baseurl}}/{{page.logo}}" data-action="zoom"> 

```html
<div>
<strong style="font-size:20px">Fully-Funded PhD Opportunity in Deep Learning & Big Data Analysis for Elderly Care and Rehabilitation (Macau)<strong >
</div>
```

## Project overview

Our group in Faculty of Applied Sciences, Macao Polytechnic University, Macao is excited to offer a fully-funded PhD candidate in the rapidly growing fields of deep learning and big data analysis, specially tailored for towards advancements in elderly care and rehabilitation (Computer Science & Bioinformatics, & Mathematics or related areas). 

The project brings a unique opportunity to leverage our electronic health records (EHRs), containing detailed large-scale clinical information, by using multimodal deep learning. Data content includes both structured data (treatments, laboratory tests, omics data etc.) as well as unstructured data (written clinical notes and brain scans). 

This project aims to discover novel ground-breaking insights into aging curves, identify clinical state markers and biomarkers associated with the decline in exercise function and exercise injuries among the elderly, as well as develop digital twin mapping technologies for important functions and multiple physiological parameters in the elderly population.

## Team Environment

You will be part of a vibrant, multidisciplinary group composed of PhD candidates, postdoctoral researchers, and professors specializing in public health, statistics, bioinformatics, multi-modal deep learning, and large language models (LLMs). The typical duration of the PhD program at Macao Polytechnic University is 3-4 years, contingent upon performance.



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
