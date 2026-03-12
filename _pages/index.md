---
title: "Home Page"
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/placeholder.png
  actions:
    - label: "Download CV"
      url: "https://drive.google.com/file/d/1ePqrAcar-abcMBgLCd7uo0HUbZDd929t/preview"
      target: "_blank"


excerpt: "The gateway to all other pages"
intro: 
  - excerpt: 'In this site, you may read about:'
feature_row:
  - image_path: /assets/images/placeholderfavicon.png
    alt: "placeholder image 1"
    title: "About Me"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/placeholderfavicon.png
    alt: "placeholder image 2"
    title: "My Projects"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/placeholderfavicon.png
    alt: "placeholder image 4"
    title: "My Contact Information"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

