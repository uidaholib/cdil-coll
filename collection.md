---
title: Collection
layout: default
---

Preview our collection:

<hr>
<br>

{% for item in site.data.stockbridge-cdil %}
    
<div>
    <a href="{{ item.imagelink }}">
    <img src="{{ item.imagelink }}" alt="{{ item.Title }}"></a>
    <h3>{{ item.Title }}</h3>
    <p>{{ item.Date }}</p>
    <p>{{ item.Description }}</p>
</div>

<hr>
<br>
    
{% endfor %}
