---
layout: default
title: Documentation 
---

<div>
   Documentation
</div>
<div>
    Vous trouverez ci-dessous l'ensemble de la documentation permettant de démarrer un nouveau projet selon les règles de l'ANS
</div>

<div class="row">
    <div class="border rounded col p-2 m-1">
        <h3>Documentation</h3>
        <hr aria-hidden="true">
        <div>
            {% for item in site.data.menu.header[0].subfolderitems[0].subfolderitems %}
                <div><a href="{{ item.url | relative_url }}">{{ item.title }}</a></div>
            {% endfor %}
        </div>
    </div>
    <div class="border rounded col p-2 m-1">
        <h3>Ressources FHIR</h3>
        <hr aria-hidden="true">
        <div>
            {% for item in site.data.menu.header[0].subfolderitems[1].subfolderitems %}
                <div><a href="{{ item.url | relative_url }}">{{ item.title }}</a></div>
            {% endfor %}
        </div>
    </div>
    <div class="border rounded col p-2 m-1">
        <h3>Techniques avancées</h3>
        <hr aria-hidden="true">
        <div>
            {% for item in site.data.menu.header[0].subfolderitems[2].subfolderitems %}
                <div><a href="{{ item.url | relative_url }}">{{ item.title }}</a></div>
            {% endfor %}
        </div>
    </div>
</div>
