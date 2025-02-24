---
title: "Welcome to My Website"
layout: splash
permalink: /
date: 2025-02-24T00:00:00-05:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/Puppy.png
  actions:
    - label: "Explore More"
      url: "/about/"
  caption: "Photo credit: [Unsplash](https://unsplash.com)"
excerpt: "Explore cutting-edge research, bioinformatics resources, and interactive data visualization tools."
intro:
  - excerpt: 'Welcome to my research hub, where you can find insights into bioinformatics, single-cell RNA sequencing, and more. *Explore the data, methods, and findings.*'
feature_row:
  - image_path: /assets/images/Puppy.png
    alt: "Feature 1"
    title: "Interactive Visualizations"
    excerpt: "Explore interactive plots and data-driven insights."
    url: "/visualizations/"
    btn_label: "View Now"
    btn_class: "btn--primary"
  - image_path: /assets/images/Puppy.png
    alt: "Feature 2"
    title: "Bioinformatics Methods"
    excerpt: "Learn about the tools and workflows used in high-throughput data analysis."
    url: "/methods/"
    btn_label: "Learn More"
    btn_class: "btn--primary"
  - image_path: /assets/images/Puppy.png
    alt: "Feature 3"
    title: "Publications & Insights"
    excerpt: "Read about key findings and ongoing research."
    url: "/publications/"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/Puppy.png
    alt: "Feature 4"
    title: "Data Repositories"
    excerpt: "Access datasets and analysis-ready files."
    url: "/data/"
    btn_label: "Browse Data"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/Puppy.png
    alt: "Feature 5"
    title: "Tools & Scripts"
    excerpt: "Find useful bioinformatics scripts and pipelines."
    url: "/tools/"
    btn_label: "Explore Tools"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/Puppy.png
    alt: "Feature 6"
    title: "Collaborate & Contact"
    excerpt: "Reach out for collaborations, questions, or discussions."
    url: "/contact/"
    btn_label: "Get in Touch"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}
