---
layout: page
title: Publications
permalink: /publications/
---


<div id="pubs-container">
  {% for item in site.data.publications %}
    <div class="pub-record">
      <div class="pub-title">
        <a href="{{ item.link }}">
          {{ item.title }}
        </a>
      </div>
      <div class="pub-authors"> {{ item.authors }} </div>
      <div class="pub-bibinfo"> {{ item.bibinfo }} </div> <br/>
    </div>
    {% endfor %}
</div>