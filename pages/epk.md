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

Hotel Julieta es una banda chilena de rock-pop fundada por 2 músicos de Talca, con residencia en Santiago. Su propuesta musical tiene un fuerte énfasis en la presentación en vivo, cargada de una energía potente suscitando a la euforia.

El proyecto comienza el año 2013, cuando Matías (Voz) y Eduardo (Bajo), se juntan a componer y desarrollar el proyecto, a lo que más tarde se suma Tomas Ledoux como guitarrista.

El primer EP de la banda, “Imágenes” fue publicado en Junio del 2015, volviéndose muy popular en Spotify, alcanzando las dos canciones más escuchadas en Talca y entrando con la canción “Imágenes” a las 50 canciones más virales de Chile.

Después del primer EP, siguen publicando material sonoro y audiovisual, acompañado de viajes a diferentes localidades dentro de Chile, como Valparaíso, Talca, Santiago, entre otros.

Su fama también se vio impulsada por la aparición de su vocalista en el programa de televisión “The Voice Chile”, bajo el alero de Álvaro Lopez (ex Los Bunkers).

Actualmente se encuentran en la grabación de su álbum debut. El disco ha sido trabajado mayoritariamente en Estudios Triana, de la mano del productor Cristian Mendeville.

## Presentaciones

Festival Alameda (Talca), Casino de Talca, Ele bar, Bar central, Cine plaza. Teatro Coca-Cola City, Teatro Cariola, Centro Arte Alameda, salas SCD, Club Chocolate.

## Redes sociales

 - [#hoteljulieta](https://instagram.com/explore/tags/hoteljulieta/)
 - [Instagram](http://instagram.com/HotelJulieta)
 - [Youtube](http://youtube.com/HotelJulieta)
 - [Facebook](http://fb.com/HotelJulieta)
 - [Twitter](http://twitter.com/HotelJulietaCL)
 - [Spotify](https://open.spotify.com/artist/4R6ApsFDCgq0nH0K5U9uj8)

## Integrantes


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

## Canciones

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

## Fotos

{% for pic in site.data.epkpics %}
[![Teatro Coca Cola](/{{pic.thumbnail}})](/{{pic.source}})
{% endfor %}

## Prensa

- [Bienvenidos al Hotel Julieta - Rata.cl](http://rata.cl/bienvenidos-al-hotel-julieta/)
- [Hotel Julieta en teatro Coca-Cola City - Rata.cl](http://rata.cl/hotel-julieta-en-vivo-en-teatro-coca-cola-city/)
- [Las canciones más escuchadas en 9 ciudades de Chile según Spotify - Revista XY](http://www.revistaxy.com/entretencion/musica-entretencion/las-canciones-mas-escuchadas-en-9-ciudades-de-chile-segun-spotify/)
- [5 cosas que no sabías de 5 nuevos clasificados de The Voice - 13.cl](http://www.13.cl/programas/the-voice/noticias/5-cosas-que-no-sabias-de-5-nuevos-clasificados)
- [Hotel Julieta + Juan Pablo Mira en Ele Bar - DIARIOdeANAFUNK](http://diariodeanafunk.cl/hotel-julieta-juan-pablo-mira-en-ele-bar-01-de-agosto)
- [Maulinos se robaron la película en programa de talentos "The Voice" Chile - Diario El Centro](http://www.diarioelcentro.cl/?q=articulo-espectaculos&id=1207)
- [#TheVoiceChile: Los proyectos musicales de algunos clasificados - Sólo Artistas Chilenos](http://soloartistaschilenos.blogspot.cl/2015/06/thevoicechile-los-proyectos-musicales_9.html)
- [Las 3 canciones más populares de Spotify en Talca](/images/epk/press/spotifytalca.png)
- [Las 50 más virales de Chile en Spotify](/images/epk/press/50masvirales.jpg)

## Contacto

<center>
  <b>Juan José Sanz</b>
</center>
<center>
  <a href="mailto:hoteljulieta@gmail.com">hoteljulieta@gmail.com</a>
</center>
<center>
  <a href="tel:+56981249515">+56 9 8124 9515</a>
</center>


### Ficha técnica

[Descargar](/downloads/ficha_tecnica_hotel_julieta.pdf)

