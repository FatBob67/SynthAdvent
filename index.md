# Synth Advent Calendar

Hello and Welcome to this blog which will track my trials and tribulations when building a synthesizer using the Electronic sound Advent Calendar.

![image](/_assets/2023-11-30/Elec_Snd_Advent_Calendar.png)

<ul>
  {% for post in site.posts %}
  <li><a href="{{ post.url }}" class="post-preview">{{ post.title }}</a></li>
  {% endfor %}
</ul>