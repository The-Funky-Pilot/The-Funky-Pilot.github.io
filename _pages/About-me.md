---
title: "About Me"
layout: default
permalink: /AboutMe/
skills:
  - name: "Unity"
    icon: "fab fa-fw fa-unity"
    badges: ["C#", "Game Dev"]
    text: "Built multiple prototypes and a published jam game."
    years: 2
  - name: "Game Design"
    icon: "fas fa-fw fa-gamepad"
    badges: ["Game Mechanics", "Levels", "UI"]
    text: "Designed mechanics, levels, and player feedback loops."
    level_label: "Beginner"
---
{% include figure image_path="/assets/images/stupidSprite.png" alt="Game Jam screenshot" caption="This is MY new caption" %}

This page uses the `default` layout. It is a minimal wrapper around your content.
You can use it for simple pages where you want full control over the markup.

{% include skills skills=page.skills %}

{% include download
  title="Download my Project Proposal"
  url="/assets/downloads/Project-proposal.pdf"
  button_label="Download Project Proposal"
  download="Project-proposal.pdf"
%}

{% include google-form
  title="Contact Me"
  src="https://forms.gle/XVE9i3LQ79UHr53s8"
  height="800"
%}
