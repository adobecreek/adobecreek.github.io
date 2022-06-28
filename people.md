---
layout: page
title: People at Adobe Creek
permalink: /people/
---

<div class="categories">

{% for person in site.people %}

<div class="partner">
     <div class="personhead">{% if person.head_image %}<img src="{{ person.head_image }}" alt="headshot of {{ person.name }}"/>{% endif %}</div>
     <div>{{ person.name }}, {{ person.role }}</div>
     <div>{{ person.content }}</div>
</div>

{% endfor %}

</div>
