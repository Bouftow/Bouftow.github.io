---
layout: default
title: Inicio
---

# ¡Bienvenido a mi sitio!

Este sitio está construido con **Jekyll** y **GitHub Pages**.

## Últimos posts

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%d/%m/%Y" }}
{% endfor %}

## Sobre mí

Soy Boutflow y estoy aprendiendo a usar GitHub Pages.
