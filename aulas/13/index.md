---
title: Aula 13 - Fundamentos de VueJs
nav_order: 13
has_children: true
has_toc: false
youtubeId: 9MiQa8mUl8U
next: 01-introducao
---
{% assign title = page.title | split: "-" %}
{% assign slide =  title[1] | replace: " ", "-" %}

## {{ title | slice: 1 }}

### Recurso

<span class="fs-3">
<a href="{{site.baseurl}}/assets/downloads/{{ page.nav_order }}{{ slide }}.pdf" class="btn" target="_blank">Notas de aula</a>
<a href="https://www.icloud.com/keynote/08831v0gK4p2H-8_GJSRf-VdA#11-Fundamentos-de-VueJs" class="btn" target="_blank">Slides com animação</a>
</span>

{% include youtubePlayer.html id=page.youtubeId %}


<span class="fs-3 float-right">
[Próxima aulas]({{page.next}}){: .btn }
</span>

