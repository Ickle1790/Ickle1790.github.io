---
title: "Home Page"
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/index-background.jpg
  actions:
    - label: "Download CV"
      url: "https://drive.google.com/file/d/1I7Hvu_ZIAXsTJ6i5KnKicptkYnmrgoqX/preview"
      target: "_blank"


excerpt: "The gateway to all other pages"
intro: 
  - excerpt: 'Welcome to my portfolio! In this site, you may read about:'
feature_row:
  - image_path: /assets/images/derry-stock.jpg
    alt: "About Me"
    title: "About Me"
    excerpt: "Read about my education, location, hobbies and more."
    url: "https://ickle1790.github.io/about-me/"
    btn_label: "Go to About Me"
    btn_class: "btn--primary"
  - image_path: /assets/images/Homepage-Projects-Image-Bigger.jpg
    alt: "My Projects"
    title: "My Projects"
    excerpt: "View previous games I have created."
    url: "https://ickle1790.github.io/projects/"
    btn_label: "Go to Projects"
    btn_class: "btn--primary"
  - image_path: /assets/images/gmail-stock.png
    alt: "My Contact Information"
    title: "My Contact Information"
    excerpt: "Learn the best ways to reach out to me."
    url: "https://ickle1790.github.io/contact-me/"
    btn_label: "Go to Contact Me"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

