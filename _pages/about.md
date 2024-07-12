---
title: "blog"
layout: splash
permalink: /about/
date: 2024-07-11T14:33:33-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/splash-1.jpg
  actions:
    - label: "Download"
      url: "https://github.com/mmistakes/minimal-mistakes/"
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "blog excerpt goes here"
intro: 
  - excerpt: 'There but for the grace of God go I.'
feature_row:
  - image_path: assets/images/splash-3.jpg
    alt: "placeholder image 1"
    title: "post 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/splash-4.jpg
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "post 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/splash-4.jpg
    title: "Placeholder 3"
    excerpt: "blog post teaser here"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}
