---
layout: default
---

# Synth Advent Calendar

Hello and Welcome to this blog which will track my trials and tribulations when building a synthesizer using the Electronic sound Advent Calendar.

![Electronic Sound Advent Calendar Box](./assets/2023-11-30/Elec_Snd_Advent_Calendar.png)

## Blog Posts

<ul>
  {% for post in site.posts %}
  <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>