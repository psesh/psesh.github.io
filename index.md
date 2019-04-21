---
title: "turbomachinery + machine learning"
layout: splash
author_profile: false
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: unsplash-image-1.jpg
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "I'm a postdoctoral fellow at the Department of Engineering, University of Cambridge and also a Group Leader in the Data-Centric Engineering Programme at the Alan Turing Institute. My team's research is funded by Rolls-Royce plc, the Lloyd's Register Foundation UK Research and Innovation."
intro: 
  - excerpt: 'I undertake research in *data-centric aeronautics*: applying existing, and developing novel, data-driven algorithms in **turbomachinery aerothermodynamics** and **machine learning** for better aerodynamic inference and decision-making. My research interests vary from statistical theory and numerical linear algebra to turbomachinery applications. Explore my current projects below'
feature_row:
  - image_path: unsplash-gallery-image-1-th.jpg
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 1"
    title: "Bayesian models in engines"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Dimension reduction in design"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Research overview"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
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
