---
title: "brendan's blog"
layout: splash
permalink: /
date: 2024-07-11T14:33:33-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/splash-1.jpg
  caption: ""
excerpt: "blog excerpt goes here"
intro: 
  - excerpt: 'glob'
feature_row:
  - image_path: assets/images/splash-3.jpg
    alt: "placeholder image 1"
    title: "Urgent: Help Required"
    excerpt: "No good email address goes unpunished."
    url: "https://github.com/bji219/blog/blog/WMP/"
    btn_label: "Read On"
    btn_class: "btn--primary"
  - image_path: /assets/images/splash-4.jpg
    image_caption: ""
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
