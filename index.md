---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#

layout: frontpage
title: "Hotel Julieta"
redirect_to:
  - /epk
header:
   image_fullwidth: "header_unsplash_12.jpg"
widget-1:
    title: "Canciones"
    url: 'songs'
    text: 'Escucha y comparte la música de Hotel Julieta'
    image: unsplash_9-302x182.jpg
widget-2:
    title: "Videos"
    url: 'videos'
    text: 'Material audiovisual'
    video: '<a href="#" data-reveal-id="videoModal"><img src="/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""></a>'
widget-3:
    title: "Noticias"
    url: 'blog'
    text: 'Entérate de las últimas novedades de la banda'
    image: github-303x182.jpg
---


<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/lCV_CDJssvc" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
