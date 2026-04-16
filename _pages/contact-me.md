---
title: "Contact Me"
layout: splash
permalink: /contact-me/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/placeholder.png
skills:
    - name: "Discord"
      icon: "fab fa-fw fa-discord"
      text: "Placeholder-Account-Name"
    - name: "Twitter/X"
      icon: "fab fa-fw fa-twitter-square"
      text: "Placeholder-Account-Name"
    - name: "Gmail"
      icon: "fab fa-fw fa-gmail"
      text: "Placeholder-Account-Name"
---
If there is anything you would wish to contact me for, please fill in the attached Google form and I shall respond as soon as I can.

{% include google-form
  title="Contact Me"
  src="https://forms.gle/VGw65LWmLXH2rp7o6"
  height="800"
%}

Additionally, you can contact me through my accounts on social media and other platforms:

{% include skills skills=page.skills %}
