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

##Redes sociales


 - [Instagram](http://instagram.com/HotelJulieta)
 - [Youtube](http://youtube.com/HotelJulieta)
 - [Facebook](http://fb.com/HotelJulieta)
 - [Twitter](http://twitter.com/HotelJulietaCL)
 - [Spotify](https://open.spotify.com/artist/4R6ApsFDCgq0nH0K5U9uj8)

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
[![Teatro Coca Cola](/{{pic.thumbnail}})](/{{pic.source}})
{% endfor %}


##Prensa

####Las 3 canciones más populares de Spotify en Talca
![Spotify Talca](https://lh5.googleusercontent.com/0Vo1ibek5kOKE4L2G1xEYX5mBZWDZh-G2VxSuaOKSkvJ6oNkEANgEQVq6BAMJgL03Tm0FKjyYD-UhsM=w1256-h538)

####Las 50 más virales de Chile en Spotify
![Spotify Chile](https://fbcdn-sphotos-b-a.akamaihd.net/hphotos-ak-xtp1/v/t1.0-9/11822442_491864784321375_6760165495853420254_n.jpg?oh=f8d88be6393acb15fb5b2fe97d126a34&oe=567893EB&__gda__=1453809629_12ca1647e584b5423c7f02501bd7dc27)

##Contacto

 |**Juan José Sanz**|
 |jjsanz@uc.cl|
 |+56 9 8124 9515|

