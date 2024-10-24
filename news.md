---
title: News
permalink: /news/
logo: images/news/mpu_logo.png
---

# Join Us

<img width="50" src="{{site.baseurl}}/{{page.logo}}" data-action="zoom"> 

<strong style="color:#000000;font-weight:bold;font-size:40px;line-height:1.25">
  Fully-Funded PhD Opportunity in Deep Learning & Big Data Analysis for Elderly Care and Rehabilitation (Macau)
</strong>

<a href="../PDF/PhD student recuritment AD_2024-10-11.pdf" target="_blank">PhD student recuritment AD_2024-10-11.pdf</a>. 

## Project overview

Our group in Faculty of Applied Sciences, Macao Polytechnic University, Macao is excited to offer a fully-funded PhD candidate in the rapidly growing fields of deep learning and big data analysis, specially tailored for towards advancements in elderly care and rehabilitation (Computer Science & Bioinformatics, & Mathematics or related areas). 

The project brings a unique opportunity to leverage our electronic health records (EHRs), containing detailed large-scale clinical information, by using multimodal deep learning. Data content includes both structured data (treatments, laboratory tests, omics data etc.) as well as unstructured data (written clinical notes and brain scans). 

This project aims to discover novel ground-breaking insights into aging curves, identify clinical state markers and biomarkers associated with the decline in exercise function and exercise injuries among the elderly, as well as develop digital twin mapping technologies for important functions and multiple physiological parameters in the elderly population.

## Team Environment

You will be part of a vibrant, multidisciplinary group composed of PhD candidates, postdoctoral researchers, and professors specializing in public health, statistics, bioinformatics, multi-modal deep learning, and large language models (LLMs). The typical duration of the PhD program at Macao Polytechnic University is 3-4 years, contingent upon performance.

## About you (Requirements)

+ A master’s degree in Computer Science, Bioinformatics, artificial intelligence, or related fields. 
+ In-depth experience on at least one of the areas including Multi-Omics, Deep Learning, Reinforcement Learning, LLMs, Computer Vision, GenAI, and Multi-Modal Modeling.
+ Demonstrations of deep learning experience via technical publications in conferences or journals, or impactful Open-Source Projects.
+ Fluency in English, with excellent spoken and written communication abilities.
+ Willing to perform teaching and service duties (Generally severing a teaching assistant for one semester and guiding masters and undergraduate students)

## Your Benefits

+ We offer competitive PhD scholarship (120,000 - 240,000 MOP/Year, commensurate with qualifications., approx. 15,000 to 30,000 USD). Please note that tuition and related fees, approximately 8,125 USD (2024) for international students, are not covered by the scholarship. For more details, please visit  <a href="https://www.mpu.edu.mo/student_corner_p/en/fs_tuitionfees.php" target="_blank">https://www.mpu.edu.mo/student_corner_p/en/fs_tuitionfees.php</a>. 
+ Work-Life Balance: Enjoy additional 22 days of annual leave with full-time employment in addition to public holidays, allowing for an optimal balance between your professional and personal life. Public holidays in Macau include both Eastern (e.g. Chinese New Year, Mid-Autumn Festival, etc.) and Western (e.g. Christmas, etc.) festivals, as well as religious festivals (e.g. The Buddha's Birthday (Feast of Buddha) and Feast of Immaculate Conception, etc.). Please refer to the government website <a href="https://www.gov.mo/en/public-holidays/year-2024/" target="_blank">https://www.gov.mo/en/public-holidays/year-2024/</a>. 

## About Macao Polytechnic University (MPU)

Located in the heart of Macao, <a href="https://www.mpu.edu.mo/en/mpu_introduction.php" target="_blank">Macao Polytechnic University (MPU)</a> is a leading public institution known for its academic excellence and innovative research. The university boasts state-of-the-art facilities and a supportive academic community that fosters the intellectual and personal growth of its students. As a beacon of knowledge that attracts scholars from around the globe, MPU is committed to molding future leaders and advancing research that impacts the global community.

## About Macao and the Great Bay Area

Macao is a vibrant city strategically located near major Asian hubs, such as Hong Kong, Taiwan, Japan, and Korea, making it an excellent gateway for exploring the region. Part of the dynamic Greater Bay Area, Macao offers a unique blend of Chinese and Portuguese cultural heritage complemented by a modern lifestyle. This city-state is renowned for its high quality of life, multicultural environment, and as a center of entertainment and leisure. Residents and visitors in Macao often enjoy visa-free access to mainland China, providing a wonderful opportunity to explore the nearby city of Shenzhen and other beautiful locations across the country. Macao is known gambling as “Las Vegas of Asia. Macau's gambling industry is the largest in the world, generating over MOP195 billion (US$24 billion) in revenue and about seven times larger than that of Las Vegas. Living in Macao, you will experience a unique blend of modernity and tradition, with access to world-class entertainment, dining, and cultural experiences. Macau is super safe to live and is full of night life. 

## Application process

Interested candidates should submit a CV and a cover letter outlining relevant experiences and motivations for applying to Dr. Kefeng Li at kefengl@mpu.edu.mo. Ensure all documents are in PDF format. Applications are accepted on a rolling basis until the position is filled.

<br/>

<br/>

<br/>

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

