---
title: "Data Analysis of Community Discussions on Security Issues"
description: "Applying data exploratory analysis and an unsupervised Machine Learning algorithm (LDA) on 264.148 text data collected from StackOverflow"
featured_image: 'images/project-4/lda_pyldavis.png'
date: 2023-04-12T21:17:04+02:00
draft: false
tags: ["Python", "NLP", "Data Analytic", "SQL"]
---

# Description:
In this project, I collected ~260.000 text data to figure out the current trend of security-related topics. Due to huge amount of text data, an unsupervised topic discovery algorithm is applied, i.e. Latent Dirichlet Algorithm (LDA). Before applying LDA, it is necessary to preprocess text data and convert it to be compatible as input for LDA. Furthermore I also did data exploratory analysis to figure out the general trend of security topics and general other programming topics. 

My report for this project can be found: {{< rawhtml >}} 
  <a href="/docs/project-4/Gunardis_Paper.pdf" ><img src="/images/siteimages/link_icon.png" style="width:20px;height:20px;"></a>
{{< /rawhtml >}}.

The visualization for my LDA output can be found: {{< rawhtml >}} 
  <a href="/docs/project-4/02_lda_2012-2021_6_topics.html" ><img src="/images/siteimages/link_icon.png" style="width:20px;height:20px;"></a>
{{< /rawhtml >}}.

# Future Articles:
I will write Medium articles to document the following important steps for this project:
{{< rawhtml >}} 
<center>
  <img style="border:2px solid black;" src="/images/project-4/project_diagram.png" width="100%" height="100%"/>
</center>
{{< /rawhtml >}}