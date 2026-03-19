---
title: "About Me"
layout: splash
permalink: /about-me/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/placeholder.png
  actions:
    - label: "Download CV"
      url: "https://drive.google.com/file/d/1ePqrAcar-abcMBgLCd7uo0HUbZDd929t/preview"
      target: "_blank"
skills:
    - name: "Unity"
      icon: "fab fa-fw fa-unity"
      badges: ["C#", "Game Dev"]
      text: "Built multiple prototypes, and currently working on another."
      level_label: "Beginner"
      overlay_color: "FF8FF1"
    - name: "Game Design"
      icon: "fas fa-fw fa-gamepad"
      badges: ["Game Mechanics", "Levels", "UI"]
      text: "Designed mechanics, levels, and player feedback loops."
      level_label: "Beginner"
---

About me about me about me

{% include figure image_path="/assets/images/placeholderfavicon.png" alt="Game Jam screenshot" caption="This is a caption" %}

{% include skills skills=page.skills %}
