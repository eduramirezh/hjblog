---
layout: pageepk
title: "Hotel Julieta"
subheadline: "EPK"
show_meta: false
teaser: "Hotel Julieta es una banda chilena de rock-pop emergente."
permalink: "/epk/"
header:
    image_fullwidth: "teatro.jpg"
---

La banda se formó a inicios de ...

##Canciones


{% for song in site.data.songs %}
<div class="row">
  <div class="medium-8 columns t20">
    <a target="_blank" href="{{site.url}}/{{song.download-url}}" download>{{ song.title }}</a>

  </div>
    <audio controls>
      <source src="{{site.url}}/{{song.download-url}}" type="audio/mpeg">
      Your browser does not support the audio tag.
    </audio>
</div>
{% endfor %}

##Fotos

{% for pic in site.data.epkpics %}
![Teatro Coca Cola]({{site.url}}/{{pic.source}})
{% endfor %}

##Otros videos

##Prensa

