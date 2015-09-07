---
layout: pageepk
title: "Hotel Julieta"
subheadline: "EPK"
show_meta: false
teaser: "Hotel Julieta es una banda chilena de rock-pop."
permalink: "/epk/"
logo: "logo_sin_sombra.png"
header:
    image_fullwidth: "teatro.jpg"
---

La banda se formó a inicios de ...

<iframe width="320" height="315" src="https://www.youtube.com/embed/Ko-6N7VrhLg" frameborder="0" allowfullscreen></iframe>

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
  <div class="medium-8 columns t20">
    <audio controls>
      <source src="{{site.url}}/{{song.download-url}}" type="audio/mpeg">
      Your browser does not support the audio tag.
    </audio>
  </div>
</div>
{% endfor %}

##Fotos

{% for pic in site.data.epkpics %}
[![Teatro Coca Cola](/{{pic.thumbnail}})](/{{pic.source}})
{% endfor %}


##Prensa

- [Bienvenidos al Hotel Julieta - Rata.cl](http://rata.cl/bienvenidos-al-hotel-julieta/)
- [Hotel Julieta en teatro Coca-Cola City - Rata.cl](http://rata.cl/hotel-julieta-en-vivo-en-teatro-coca-cola-city/)
- [Las canciones más escuchadas en 9 ciudades de Chile según Spotify - Revista XY](http://www.revistaxy.com/entretencion/musica-entretencion/las-canciones-mas-escuchadas-en-9-ciudades-de-chile-segun-spotify/)
- [5 cosas que no sabías de 5 nuevos clasificados de The Voice - 13.cl](http://www.13.cl/programas/the-voice/noticias/5-cosas-que-no-sabias-de-5-nuevos-clasificados)
- [Hotel Julieta + Juan Pablo Mira en Ele Bar - DIARIOdeANAFUNK](http://diariodeanafunk.cl/hotel-julieta-juan-pablo-mira-en-ele-bar-01-de-agosto)
- [Maulinos se robaron la película en programa de talentos "The Voice" Chile - Diario El Centro](http://www.diarioelcentro.cl/?q=articulo-espectaculos&id=1207)
- [#TheVoiceChile: Los proyectos musicales de algunos clasificados - Sólo Artistas Chilenos](http://soloartistaschilenos.blogspot.cl/2015/06/thevoicechile-los-proyectos-musicales_9.html)
- [Las 3 canciones más populares de Spotify en Talca](/images/epk/press/spotifytalca.png)
- [Las 50 más virales de Chile en Spotify](/images/epk/press/50masvirales.jpg)

##Contacto

 |**Juan José Sanz**|
 |jjsanz@uc.cl|
 |+56 9 8124 9515|

