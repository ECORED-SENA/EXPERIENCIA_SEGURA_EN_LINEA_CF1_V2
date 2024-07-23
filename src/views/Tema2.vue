<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 2
      h1 Las redes sociales
    
    .row.mb-5.align-items-center
      .col-lg-6(data-aos="fade-right")
        p Sabía que las redes sociales son mega estructuras creadas en Internet por grupos de personas que contactan entre sí, para compartir intereses en común, para crear relaciones por gustos, pasiones, intereses o necesidades. Esta es la forma más rápida de relacionarse con una persona o empresa.
          br
          br
          |Las primeras redes sociales como tal, no surgieron hasta la popularización de Internet a principios del siglo XXI, en la web 2.0, cuya principal característica era dar la posibilidad a los usuarios de elaborar y publicar sus propios contenidos #[em online].
      .col-lg-6(data-aos="fade-left"): img(src="@/assets/curso/65.jpg")
    p.mb-0 Pero, gracias a la popularización y cada vez más fácil el acceso a Internet y a elementos de comunicación móviles como los teléfonos inteligentes y las tabletas, las redes sociales han tomado una gran importancia y han incrementado el uso y acceso a este tipo de plataformas, donde el usuario busca la manera de conocerse y relacionarse e incluso busca la posibilidad de ofrecer y adquirir productos, hasta utilizarlas como estrategia para la búsqueda y consecución de empleo. 
    Separador
    #t_2_1.titulo-segundo(data-aos="fade-right")
      h2 2.1 Tipos de redes sociales
    .row.mb-5.align-items-center
      .col-lg-6.mb-4.mb-lg-0(data-aos="fade-right"): img(src="@/assets/curso/66.jpg")
      .col-lg-6(data-aos="fade-left")
        p Se puede pensar equivocadamente que las redes sociales son todas iguales, pero no es así. De hecho, por lo general se dividen en diferentes tipos, de acuerdo con el objetivo de los usuarios al crear un perfil, de esa forma una misma red social puede ser útil de más de una manera. 
          br
          br
          |Normalmente las redes sociales que más se usan tienen el mismo propósito, pero en realidad existen muchas otras alternativas dispuestas dependiendo del objetivo al momento del registro y crear una cuenta en ellas. La clasificación más común es:

    TabsD.color-acento-contenido.mb-5
      .py-4.py-md-5(titulo="Red social de relaciones" :icono="require('@/assets/curso/53.svg')" :icono2="require('@/assets/curso/54.svg')")
        .row
          .col-lg-3.mb-4.mb-lg-0
            img(src="@/assets/curso/61.jpg")
          .col-lg-9
            h4 Red social de relaciones
            p El principal objetivo de esta red social es el de conectar personas, el caso más conocido es Facebook. Pero podemos citar innumerables otras redes, que también encajan en los otros tipos, como Instagram, LinkedIn, Twitter, etc.
      .py-4.py-md-5(titulo="Red social de entretenimiento" :icono="require('@/assets/curso/55.svg')" :icono2="require('@/assets/curso/56.svg')")
        .row
          .col-lg-3.mb-4.mb-lg-0
            img(src="@/assets/curso/62.jpg")
          .col-lg-9
            h4 Red social de entretenimiento
            p Las redes sociales de entretenimiento son aquellas en las que el objetivo principal no es relacionarse con las personas, sino consumir contenido. El ejemplo más icónico es YouTube, la mayor plataforma de distribución de videos del mundo, en la que el objetivo es publicar y ver videos. Otro caso es el de Pinterest, en el que las personas publican y consumen imágenes.
      .py-4.py-md-5(titulo="Red social profesional " :icono="require('@/assets/curso/57.svg')" :icono2="require('@/assets/curso/58.svg')")
        .row
          .col-lg-3.mb-4.mb-lg-0
            img(src="@/assets/curso/63.jpg")
          .col-lg-9
            h4 Red social profesional 
            p Son redes donde el usuario tiene como objetivo crear relaciones profesionales con otros usuarios, divulgar proyectos y conquistas profesionales, presentar su currículum y habilidades, además de conseguir indicaciones, empleos, etc.
              br
              br
              |LinkedIn es la red social profesional más conocida y utilizada, pero hay otras que también vienen ganando un espacio y posicionándose, como Behance, Bebee, Bayt, Xing y Viadeo.
      .py-4.py-md-5(titulo="Red social de nicho" :icono="require('@/assets/curso/59.svg')" :icono2="require('@/assets/curso/60.svg')")
        .row
          .col-lg-3.mb-4.mb-lg-0
            img(src="@/assets/curso/64.jpg")
          .col-lg-9
            h4 Red social de nicho
            p Las redes sociales de nicho son aquellas dirigidas a un público específico, ya sea una categoría profesional o personas que tienen un interés específico en común.
              br
              br
              |Uno de los casos más emblemáticos es el de TripAdvisor, donde los usuarios atribuyen notas y comentarios a atracciones relacionadas con el sector gastronómico y turístico.
    p.mb-0 Si bien existen estas categorías de redes sociales, es importante mencionar que todas ellas fueron creadas con una visión o propósito inicial, pero que en la medida de su popularización y uso se han convertido en redes sociales que encajan perfectamente en varias de esta clasificación. 
      br
      br
      |Es el caso de Facebook la cual originalmente fue creada como una red que conectara personas, en la actualidad viene siendo utilizada para ofertar productos y servicios, ofrecer entretenimiento y hasta ser un medio que facilita la publicación y contratación de oferta laboral.
    Separador
    #t_2_2.titulo-segundo(data-aos="fade-right")
      h2 2.2 Usos de las redes sociales
    p.mb-5 Este uso está determinado por el tipo de red elegida para crear una cuenta entre muchas opciones. Los usos más comunes son:
    .row.justify-content-center
      .col-lg-10
        SlyderC.p-1(:datos="datosSlyder")
    Separador
    #t_2_3.titulo-segundo(data-aos="fade-right")
      h2 2.3 Características de seguridad en las redes sociales
    p.mb-5 Dada la proliferación o aumento de uso de las redes sociales, a continuación se mencionan algunas características de seguridad a tener en cuenta al momento de utilizarlas.
    .tarjeta.color-acento-contenido.p-4.p-md-5.mb-5
      .row.justify-content-around.align-items-center
        .col-8.col-sm-6.col-md-4.mb-4.mb-md-0
          img(src="@/assets/curso/78.svg")

        .col-md.col-lg-6
          h3 Características de seguridad en las redes sociales
          p.mb-4 Para iniciar debe tener en cuenta las redes sociales que usa y  la cantidad de información que comparte al día junto con la veracidad de la misma, posterior a eso se deben tener en cuenta las siguientes condiciones de seguridad para el buen uso de las redes sociales.
          
          a.boton.color-acento-botones(:href="obtenerLink('/downloads/Infografia_Seguridad_Redes.pdf')" target="_blank" type="application/pdf")
            span Descargar
            i.fas.fa-file-download

</template>

<script>
import TabsD from '../components/TabsD.vue'
export default {
  name: 'Tema2',
  components: {
    TabsD,
  },
  data: () => ({
    datosSlyder: [
      {
        titulo: '',
        texto: '',
        imagen: require('@/assets/curso/67.jpg'),
        leyendaImagen: 'Mantener contacto con amigos y familiares.',
      },
      {
        titulo: '',
        texto: '',
        imagen: require('@/assets/curso/68.jpg'),
        leyendaImagen:
          'Mantenerse al día con las noticias y eventos de actualidad.',
      },
      {
        titulo: '',
        texto: '',
        imagen: require('@/assets/curso/69.jpg'),
        leyendaImagen: 'Llenar el tiempo libre.',
      },
      {
        titulo: '',
        texto: '',
        imagen: require('@/assets/curso/70.jpg'),
        leyendaImagen: 'Encontrar contenido entretenido o divertido.',
      },
      {
        titulo: '',
        texto: '',
        imagen: require('@/assets/curso/71.jpg'),
        leyendaImagen: 'Compartir su opinión sobre un determinado tema.',
      },
      {
        titulo: '',
        texto: '',
        imagen: require('@/assets/curso/72.jpg'),
        leyendaImagen: 'Compartir fotos y videos con las demás personas.',
      },
      {
        titulo: '',
        texto: '',
        imagen: require('@/assets/curso/73.jpg'),
        leyendaImagen: 'Generación de una red de contactos.',
      },
      {
        titulo: '',
        texto: '',
        imagen: require('@/assets/curso/74.jpg'),
        leyendaImagen: 'Conocer personas.',
      },
      {
        titulo: '',
        texto: '',
        imagen: require('@/assets/curso/75.jpg'),
        leyendaImagen:
          'Compartir los detalles de lo que se está haciendo en la vida diaria.',
      },
      {
        titulo: '',
        texto: '',
        imagen: require('@/assets/curso/76.jpg'),
        leyendaImagen:
          'Compartir perfil profesional y ofrecer y buscar empleo.',
      },
      {
        titulo: '',
        texto: '',
        imagen: require('@/assets/curso/77.jpg'),
        leyendaImagen: 'Promocionar productos y servicios.',
      },
    ],
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass">
@media screen and (max-width: 600px)
  .slyder-a__bullets__item
    margin: 0 1px
  .slyder-a__tipo-a .slyder-a__bullets
    bottom: 2px
</style>
