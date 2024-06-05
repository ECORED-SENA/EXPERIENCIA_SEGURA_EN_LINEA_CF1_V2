<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    .tarjeta-escudo.bg__4.p-3.mb-5
      .row.justify-content-center.align-items-center
        .col-lg-3.mb-5.mb-lg-0(data-aos="fade-right")
          h3.mb-0.text-center ¿Qué es la ciberseguridad? 
        .col-lg-3.position-relative.mb-5.mb-lg-0(data-aos="fade-up")
          .escudo
            img(src='@/assets/curso/0.svg', alt='Texto que describa la imagen' style='width: 187px').m-auto
        .col-lg-3(data-aos="fade-left")
          h3.mb-0.text-center ¿Qué es la seguridad de la información?
    br
    p.mb-5(data-aos="fade-right") Estas preguntas y muchas más serán respondidas a lo largo del componente formativo, pero para comenzar, lo invitamos a ver el siguiente video.
    figure.mb-5(data-aos="fade-up")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/oHGhb7QoRik" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Ciberseguridad y Seguridad de la Información: introducción

    
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>
<style lang="sass">
.tarjeta-escudo
  background-color: #ffd947
.escudo
  @media (min-width: $bp-min-xl)
    position: absolute
    bottom: 0
    transform: translateY(30%)
</style>
