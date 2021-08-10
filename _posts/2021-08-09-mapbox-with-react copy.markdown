---
title:  "Mapbox with react"
# date:   2021-08-09 21:32:49 +0300
categories: reactjs
tags: "mapbox reactjs"
---
Simplest example how to set up mapbox with react

Europe cities map using mapbox:
<img src="{{ site.baseurl }}/assets/images/mapbox-cities.png">


1. Install [mapbox-gl][mapbox-gl] by running ```npm i mapbox-gl```

2. Visit [account page][account] of the mapbox and get access token 

3. The code for component will look like this: 

{% gist cb9361e56aeada95c357690be2466df9 %}

<!-- See more by tags
{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %} -->


[mapbox-gl]: https://www.npmjs.com/package/mapbox-gl
[account]: https://account.mapbox.com/