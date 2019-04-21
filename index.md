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
  - excerpt: 'I undertake research in *data-centric aeronautics*: applying existing, and developing novel, data-driven algorithms in **turbomachinery aerothermodynamics** and **machine learning** for better aerodynamic inference and decision-making. My research interests vary from statistical theory and numerical linear algebra to turbomachinery applications. Explore my current projects below.'
feature_row:
  - image_path: bayes.jpg
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "Aerobayes"
    title: "Bayesian spatial models from engine sensor measurements"
    excerpt: "Understanding aeroengine aerothermodynamics by generating spatial fields of temperature and pressure based on sensor measurements."
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: dr.jpg
    alt: "Subspace-based dimension reduction"
    title: "Dimension reduction in blade aerodynamic design"
    excerpt: "Finding lower-dimensional representations of high-dimensional design spaces for aerodynamic design."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: polynomials.jpg
    title: "Polynomial approximations for machine learning"
    excerpt: "Leveraging polynomial approximations via least squares, compressive sensing and numerical integration rules for statistical inference, design guidance and learning."
    btn_label: "Explore project"
    btn_class: "btn--primary"
    url: "www.effective-quadratures.org"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include paginator.html %}
