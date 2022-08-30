---
layout: default
title: Documentation 
---

<div>
    Vous trouverez ci-dessous l'ensemble de la documentation permettant de démarrer un nouveau projet selon les règles de l'ANS
</div>

<div class="row">
    <div class="border rounded col p-2 m-1">
        <h3>Documentation</h3>
        <hr aria-hidden="true">
        <div>
            {% for item in site.data.menu.header[2].subfolderitems %}
                <div><a href="{{ item.url | relative_url }}">{{ item.title }}</a></div>
            {% endfor %}
        </div>
    </div>
    <div class="border rounded col p-2 m-1">
        <h3>Projets</h3>
        <hr aria-hidden="true">
        <div>
            {% for item in site.data.menu.header[3].subfolderitems %}
                <div><a href="{{ item.url | relative_url }}">{{ item.title }}</a></div>
            {% endfor %}
        </div>
    </div>
</div>
