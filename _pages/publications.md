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
      </div> <br/>
      <div class="pub-authors"> {{ item.authors }} </div> <br/>
      <div class="pub-bibinfo"> {{ item.bibinfo }} </div> <br/> <br/>
    </div>
    {% endfor %}
</div>