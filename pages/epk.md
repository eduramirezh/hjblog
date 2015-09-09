---
layout: pageepk
show_meta: false
permalink: "/epk/"
logo: "logo_sin_sombras.png"
header:
    image_fullwidth: "header_unsplash_12.jpg"
---

<style>
.embed-container {
  position: relative;
  padding-bottom: 56.25%;
  height: 0;
  overflow: hidden;
  max-width: 100%;
}
.embed-container iframe, .embed-container object, .embed-container embed {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}
</style>
<div class='embed-container'>
  <iframe src='http://www.youtube.com/embed/7D7pMN97PZQ' frameborder='0' allowfullscreen></iframe>
</div>

Hotel Julieta es una banda chilena de rock-pop formada a finales de 2014.

Su propuesta musical consiste en crear canciones directas y potentes, utilizando el escenario y su espectáculo como un instrumento más para transmitir emociones con su música.

Su enfoque artístico los ha llevado rápidamente a posicionarse dentro de las bandas más populares de Chile en Spotify. Su fama también se vió impulsada por la aparición de su vocalista en el programa de televisión "The Voice Chile".

El proyecto comienza cuando Matías Schulze (estudiante de música) y Eduardo Ramírez (ingeniero civil), compañeros de colegio en Talca su ciudad natal, se juntan a componer y desarrollar un proyecto musical con una propuesta fuerte.

A fines de 2014 conocen a Tomás Ledoux (guitarrista clásico), con quien surge una química instantánea para potenciar esta propuesta.

Sus distintas disciplinas y visiones artísticas se complementan para dar origen a "Hotel Julieta". Este nombre representa el lugar imaginario donde sus ideas y visiones se comparten y se convierten en su música y su show.

Durante 2015 se integra Matías Jiménez quien, con su maestría en la batería, se convierte en la pieza final del Hotel.

Actualmente se encuentran trabajando en su primer disco LP con el productor Cristián Mendeville, y en Octubre llevarán a cabo una gira por distintas ciudades de Chile con fines promocionales.


##Redes sociales

 - [#hoteljulieta](https://instagram.com/explore/tags/hoteljulieta/)
 - [Instagram](http://instagram.com/HotelJulieta)
 - [Youtube](http://youtube.com/HotelJulieta)
 - [Facebook](http://fb.com/HotelJulieta)
 - [Twitter](http://twitter.com/HotelJulietaCL)
 - [Spotify](https://open.spotify.com/artist/4R6ApsFDCgq0nH0K5U9uj8)

##Integrantes


<figure class="image"><img src="/images/epk/tomas_epk.png" alt="{{ include.description }}">
  <figcaption>
    Tomás Ledoux <a href="http://instagram.com/i_ledoux">(@i_ledoux)</a>
  </figcaption>
</figure>

<figure class="image"><img src="/images/epk/edu_epk.jpg" alt="{{ include.description }}">
  <figcaption>
    Eduardo Ramírez <a href="http://instagram.com/eduramirezh">(@eduramirezh)</a>
  </figcaption>
</figure>

<figure class="image"><img src="/images/epk/matias_epk.jpg" alt="{{ include.description }}">
  <figcaption>
    Matías Schulze <a href="http://instagram.com/matschulze">(@matschulze)</a>
  </figcaption>
</figure>

<figure class="image"><img src="/images/epk/matiasj_epk.jpg" alt="{{ include.description }}">
  <figcaption>
    Matías Jiménez <a href="http://instagram.com/matiasjimmenez">(@matiasjimmenez)</a>
  </figcaption>
</figure>

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

<center>
  <b>Juan José Sanz</b>
</center>
<center>
  <a href="mailto:hoteljulieta@gmail.com">hoteljulieta@gmail.com</a>
</center>
<center>
  <a href="tel:+56981249515">+56 9 8124 9515</a>
</center>


###Ficha técnica

[Descargar](/downloads/ficha_tecnica_hotel_julieta.pdf)

