---
layout: page
title: Publications
permalink: /publications/
---


<div id="publications-container">
              {% for item in site.data.publications %}
                <a href="{{ item.link }}">
                  {{ item.title }}
                </a> \\
                {{ item.authors }} \\
                {{ item.bibinfo }} \\
              {% endfor %}
</div>