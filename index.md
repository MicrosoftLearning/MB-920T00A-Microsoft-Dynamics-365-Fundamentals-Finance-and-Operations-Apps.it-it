---
title: Istruzioni ospitate online
permalink: index.html
layout: home
---

# Directory contenuto

I collegamenti ipertestuali a ognuno degli esercizi e delle demo del lab sono elencati di seguito.

## Esercitazioni

{% assign labs = site.pages | where_exp:"page", "page.url contains '/Instructions/Labs'" %}
| Modulo | Lab |
| --- | --- | 
{% per l'attività nei lab %}| {{ activity.lab.module }} | [{{ activity.lab.title }}{% if activity.lab.type %} - {{ activity.lab.type }}{% endif %}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}

## Demo

{% assign demos = site.pages | where_exp:"page", "page.url contains '/Instructions/Demos'" %}
| Modulo | Demo |
| --- | --- | 
{% per l'attività nelle demo %}| {{ activity.demo.module }} | [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
