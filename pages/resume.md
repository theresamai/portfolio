---
layout: page
title: Resume
permalink: /resume/
weight: 3
---

# **About Me**

Hello. My name is **{{ site.author.name }}**! :wave: <br>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.

<div class="row">
{% include resume/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include resume/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
