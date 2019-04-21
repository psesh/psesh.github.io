---
title: "aeroengines + machine learning"
layout: splash
author_profile: false
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: engine.jpg
excerpt: "I'm a postdoctoral fellow at the Department of Engineering, University of Cambridge and also a Group Leader in the Data-Centric Engineering Programme at the Alan Turing Institute. My team's research is funded by Rolls-Royce plc, the Lloyd's Register Foundation and UK Research and Innovation."
intro: 
  - excerpt: 'I undertake research in *data-centric aeronautics*: applying existing, and developing novel, data-driven algorithms in **turbomachinery aerothermodynamics** and **machine learning** for better aerodynamic inference and decision-making. My research interests vary from statistical theory and numerical linear algebra to turbomachinery applications. Explore my current projects below'
feature_row:
  - image_path: bayes.jpg
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 1"
    title: "Bayesian spatial models from engine sensor measurements"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: dr.jpg
    alt: "placeholder image 2"
    title: "Dimension reduction in blade aerodynamic design"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: polynomials.jpg
    title: "Polynomial approximations for machine learning"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: <"https://www.youtube.com/embed/ZTzyWkdQMjg" width="560" height="315" frameborder="0">
    alt: "placeholder image 2"
    title: "Research overview"
    excerpt: 'Sound interesting? Then check out the video to the left. This is a talk I gave at the Alan Turing Institute on **Data-centric engineering in aeroengines**.'
    url: "#test-link"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Effective Quadratures"
    excerpt: 'I am the founder and lead developer of the [Effective Quadratures](https://www.effective-quadratures.org) open-source project. Our goal is to  solve a range of problems in machine learning, uncertainty quantification and optimization using polynomials! The Effective Quadratures 2019 Workshop is on July 1st 2019! 
    [Click here for more details.](https://www.effective-quadratures.org/workshop2019)'
    url: "www.effective-quadratures.org"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}

{% include paginator.html %}
