<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 3
      h1 Concepto y características de los eventos deportivos
    
    .row
      .col-lg-4.mb-4.mb-lg-0.col-md-6(data-aos="fade-right")
        figure
          img(src="@/assets/curso/tema3/1.png" alt="Imagen decorativa")
      .col-lg-8(data-aos="fade-left")
        p Los eventos del sector deportivo son particulares, reconocidos a nivel mundial y de gran relevancia para toda la humanidad. Es quizás el sector de mayor impacto en la sociedad por su capacidad de movilizar, transformar e integrar personas masivamente. Este interés por el deporte se debe a la gran capacidad de generar emociones en sus practicantes y espectadores, como difícilmente lo puede lograr otro sector; a tal punto que los eventos de esta índole no se limitan a las organizaciones deportivas, sino que también son empleados por marcas y organizaciones de otros sectores con el fin de promocionar sus productos y alcanzar sus objetivos.
        .cajon.mt-4.p-4.color-primario(style="background-color:#E0F4FE;")
          p.mb-0 Los eventos deportivos son tan amplios como el deporte mismo y abarca todos los componentes de su clasificación: deportes individuales, deportes colectivos; deporte recreativo, deporte competitivo, deporte formativo, entre otros.
    
    .bloque-texto-g.bloque-texto-g--inverso.color-acento-contenido.p-3.p-sm-4.p-md-5.mt-5(data-aos="flip-up")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema3/2.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Cuando hablamos de eventos masivos rápidamente, pensamos en eventos deportivos. Los eventos deportivos como se mencionaba anteriormente son particulares, atractivos para sus participantes, espectadores, patrocinadores y demás partes interesadas. Pero así mismo, son complejos y exigentes en su organización. 
    
    p.mt-5(data-aos="fade-right") El impacto de las marcas deportivas es el más conocido en el mundo, este recauda millones de dólares al año, y difícilmente se puede comparar con eventos de otros sectores. A continuación, se evidencia el impacto económico que generan los eventos deportivos en el mundo para el año 2017.

    .cont_3_1.mt-4
      .col-xl-8.m-auto.col-lg-10
        .titulo-sexto.color-acento-contenido(data-aos="fade-right")
          h5 Figura 1.
          i Marcas de eventos deportivos más valiosas del mundo en 2017
        figure(data-aos="zoom-in")
          img(src="@/assets/curso/tema3/4.svg" data-aos="zoom-in-up" alt="En la figura 1 se muestran las marcas de eventos deportivos más valiosos del mundo en 2017.")
    
    .row.mt-5
      .col-lg-4.mb-4.mb-md-0.col-md-6(data-aos="fade-right")
        figure
          img(src="@/assets/curso/tema3/5.png" alt="Imagen que muestra en millones de dólares lo pagado por diferentes marcas para los eventos deportivos más importantes en el año 2017.")
      .col-lg-8.col-md-6(data-aos="fade-left")
        p Eventos como el Súper #[em Bowl], que corresponde a la final del fútbol americano, es el evento que más transacciones e impacto económico genera en el mundo del deporte. Las franjas comerciales que pautan en el partido son las más costosas, pero a su vez, genera más exhibición para las marcas patrocinadoras. 
        .cajon.mt-4.p-4.color-primario(style="background-color:#E9EDFF;")
          p.mb-0 Acercándose al concepto de evento deportivo, como todo acontecimiento único, especial e irrepetible relacionado al sector deporte, con diferentes fines desde la promoción deportiva, fomento de la práctica deportiva u otras organizaciones patrocinadoras que emplean el deporte simplemente como un instrumento para promocionar sus marcas. 
    
    .row.mt-5
      .col-lg-6.mb-4.mb-lg-0(data-aos="fade-right")
        p Gresser y Bessy (1999), definen:
        .p-4.cont_3_2.d-flex(style="border-top:1px #FFCA00 solid;")
          i.fas.fa-quote-left.me-3(style="color:#FFCA00;font-size:28px;")
          div.mt-3
            p.mb-0 El evento deportivo como la organización de una actividad deportiva de mayor complejidad en el seno de una institución deportiva, sea pública o privada (s.p.). #[i.fas.fa-quote-right.ms-1(style="color:#FFCA00;font-size:28px;top: 15px")]
            .text-end.mt-3
              p.fw-bold.mb-0 Gresser y Bessy (1999).
      .col-lg-6.mb-4.mb-lg-0(data-aos="fade-left")
        p Martin (1996), define los eventos deportivos como:
        .p-4.cont_3_2.d-flex(style="border-top:1px #FFCA00 solid;")
          i.fas.fa-quote-left.me-3(style="color:#FFCA00;font-size:28px;")
          div.mt-3
            p.mb-0 programas deportivos, es decir, como actividad física deportiva organizada que satisface a quien la consume, busca la eficiencia y que requiere las mismas fases en su construcción (diseño, desarrollo y actuación final) y las mismas áreas funcionales que cualquier programa deportivo (s.p).#[i.fas.fa-quote-right.ms-1(style="color:#FFCA00;font-size:28px;top: 15px")]
            .text-end.mt-3
              p.fw-bold.mb-0 Martin (1996).
    
    p.mt-5(data-aos="zoom-in-up") Los eventos deportivos son particulares y a su vez complejos, por lo que la organización encargada de planear el evento deberá contemplar las siguientes características:

    .col-xl-10.m-auto.mt-5
      .row.justify-content-center
        .col-lg.col-md-6.mb-4.mb-lg-0(data-aos="zoom-in-up")
          figure.text-center
            img.m-auto(src="@/assets/curso/tema3/6.png" style="max-width:200px;" alt="Imagen decorativa")
          p.fw-bold.text-center.text-small Masivos
        .col-lg.col-md-6.mb-4.mb-lg-0(data-aos="zoom-in-up")
          figure.text-center
            img.m-auto(src="@/assets/curso/tema3/7.png" style="max-width:200px;" alt="Imagen decorativa")
          p.fw-bold.text-center.text-small Competencia
        .col-lg.col-md-6.mb-4.mb-lg-0(data-aos="zoom-in-up")
          figure.text-center
            img.m-auto(src="@/assets/curso/tema3/8.png" style="max-width:200px;" alt="Imagen decorativa")
          p.fw-bold.text-center.text-small Requerimiento del deportista
        .col-lg.col-md-6.mb-4.mb-lg-0(data-aos="zoom-in-up")
          figure.text-center
            img.m-auto(src="@/assets/curso/tema3/9.png" style="max-width:200px;" alt="Imagen decorativa")
          p.fw-bold.text-center.text-small Condiciones mínimas para la práctica deportiva
        .col-lg.col-md-6.mb-4.mb-lg-0(data-aos="zoom-in-up")
          figure.text-center
            img.m-auto(src="@/assets/curso/tema3/10.png" style="max-width:200px;" alt="Imagen decorativa")
          p.fw-bold.text-center.text-small Expectativas, deseos y requerimientos del espectador
    
    p.mt-5(data-aos="zoom-in-up") Así mismo, se deberán contemplar aspectos como: 

    .row.mt-5
      .col-lg.mb-4.mb-lg-0
        .tarjeta-numerada.color-acento-contenido.p-5.h-100(data-aos="zoom-in" style="box-shadow: 0px 0px 7px rgba(0,0,0,.25);")
          .tarjeta-numerada__numero
            .h2 1
          p.fw-bold Previo al evento
          p Permisos para el desarrollo del evento, cumplimiento de requerimientos legales, estudios previos de viabilidad del evento, inscripción, gestión de recursos y gestión de espacios.
      .col-lg.mb-4.mb-lg-0
        .tarjeta-numerada.color-acento-botones.p-5.h-100(data-aos="zoom-in" style="box-shadow: 0px 0px 7px rgba(0,0,0,.25);")
          .tarjeta-numerada__numero
            .h2.text-white 2
          p.fw-bold Durante el evento
          p Cubrimiento de cada detalle establecido en el plan, que garantice el desarrollo deportivo bajo parámetros de seguridad, sin contratiempos y/o con un control frente a posibles imprevistos, como lo pueden ser: hidratación, premiación, jueces, entre otros.
      .col-lg.mb-4.mb-lg-0
        .tarjeta-numerada.color-primario.p-5.h-100(data-aos="zoom-in" style="box-shadow: 0px 0px 7px rgba(0,0,0,.25);")
          .tarjeta-numerada__numero
            .h2.text-white 3
          p.fw-bold Final del evento
          p Evaluación del evento, entrega de premios, pagos a proveedores y recursos del evento, entre otros aspectos que pueden surgir en su cierre. 







</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    // variables de vue
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
.cont_3_1, .cont_3_1 *
  position: relative
.cont_3_1:before
  content: ''
  position: absolute
  width: 125%
  left: -15%
  height: 100%
  top: 30px
  background: url(../assets/curso/tema3/3.png)
  background-size: cover
  background-position: center
.cont_3_2, .cont_3_2 *
  position: relative
.cont_3_2:before
  content: ''
  position: absolute
  width: 55%
  height: 55%
  bottom: 10px
  right: 0
  background-color: #FFFAE5
</style>
