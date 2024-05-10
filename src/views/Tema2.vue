<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 2
      h1 Clasificación de eventos
    
    .bloque-texto-g.bloque-texto-g--inverso.color-acento-botones.p-3.p-sm-4.p-md-5(data-aos="flip-up")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema2/1.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Los eventos, como se ha mencionado anteriormente, pueden estar orientados a distintos propósitos y grupos poblacionales. Así mismo, una organización podrá realizar un evento dirigido a su personal interno (evento de capacitación, convivencia, evento recreativo – deportivo, entre muchos que requiere dirigir la organización a su personal interno) o externo (eventos de divulgación dirigidos a clientes, proveedores, entre otros).
        br
        br
        | El tipo de evento lo va a definir el objetivo y propósito que este tenga, cuál es el fin que se pretende, y qué se desea comunicar. 
    
    p.mt-5.fw-bold(data-aos="zoom-in-up") A continuación, se presenta la clasificación de eventos propuestos por Campos y Fuente 2013:

    SlyderF.mt-5(columnas="col-lg-6 col-xl-4")
      .tarjeta.color-acento-botones.p-4(style="background-color:#FFCA00;")
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/tema2/2.png' alt="Imagen decorativa")
        h5.text-center Eventos de celebración
        p Aniversario, conmemoración, fiesta, y eventos con formatos que respondan a objetivos de celebración.
      .tarjeta.color-acento-botones.p-4(style="background-color:#FFCA00;")
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/tema2/3.png' alt="Imagen decorativa")
        h5.text-center Eventos de formación
        p Conferencia, convenciones, reuniones y congresos, y aquellos otros cuyo objetivo principal es la formación, en el que pueden combinarse distintas actividades o formatos formativos o educacionales.
      .tarjeta.color-acento-botones.p-4(style="background-color:#FFCA00;")
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/tema2/4.png' alt="Imagen decorativa")
        h5.text-center Eventos de motivación 
        p Convención y/o reuniones, donde se combinan a su vez otros objetivos como motivación e incentivos.
      .tarjeta.color-acento-botones.p-4(style="background-color:#FFCA00;")
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/tema2/5.png' alt="Imagen decorativa")
        h5.text-center Eventos de reconocimiento 
        p Entrega de premios y/o reconocimientos.
      .tarjeta.color-acento-botones.p-4(style="background-color:#FFCA00;")
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/tema2/6.png' alt="Imagen decorativa")
        h5.text-center Eventos institucionales
        p Inauguraciones, jornada puertas abierta, visitas a instalaciones, eventos públicos.
      .tarjeta.color-acento-botones.p-4(style="background-color:#FFCA00;")
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/tema2/7.png' alt="Imagen decorativa")
        h5.text-center Eventos societarios 
        p Junta de accionistas, el consejo administración, otros.
      .tarjeta.color-acento-botones.p-4(style="background-color:#FFCA00;")
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/tema2/8.png' alt="Imagen decorativa")
        h5.text-center Eventos comerciales
        p Dentro de esta categoría, pueden encuadrarse también las ferias, ya sean organizadas por la empresa, o bien la asistencia a las mismas.
      .tarjeta.color-acento-botones.p-4(style="background-color:#FFCA00;")
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/tema2/9.png' alt="Imagen decorativa")
        h5.text-center Eventos promocionales 
        p Persiguen la notoriedad de la marca y la fidelización.
      .tarjeta.color-acento-botones.p-4(style="background-color:#FFCA00;")
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/tema2/10.png' alt="Imagen decorativa")
        h5.text-center Eventos protocolarios 
        p Marcados por la asistencia de personalidades del ámbito político, tanto de las instituciones del Estado, como del ámbito internacional.
      .tarjeta.color-acento-botones.p-4(style="background-color:#FFCA00;")
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/tema2/11.png' alt="Imagen decorativa")
        h5.text-center Eventos de incentivos
        p Viaje de incentivo o eventos basados en un formato que incentive a los participantes en el mismo.
      .tarjeta.color-acento-botones.p-4(style="background-color:#FFCA00;")
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/tema2/12.png' alt="Imagen decorativa")
        h5.text-center Eventos responsables
        p La política de responsabilidad corporativa cobra gran importancia en el diseño de este. Son eventos pensados para una mayor notoriedad de la empresa, marca y para trasladar el compromiso de esta con la sociedad.
      .tarjeta.color-acento-botones.p-4(style="background-color:#FFCA00;")
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/tema2/13.png' alt="Imagen decorativa")
        h5.text-center Eventos sostenibles
        p Tienen como objetivo el respeto y cuidado al medio ambiente. Pueden tomar diversas formas, como conferencias, ferias o festivales. Se destacan por prácticas ecoamigables como gestión eficiente de residuos y uso de energías renovables, además de promover la conciencia ambiental entre los participantes.
      .tarjeta.color-acento-botones.p-4(style="background-color:#FFCA00;")
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/tema2/14.png' alt="Imagen decorativa")
        h5.text-center Eventos culturales
        p Eventos de la industria del ocio y de la cultura. 
      .tarjeta.color-acento-botones.p-4(style="background-color:#FFCA00;")
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/tema2/15.png' alt="Imagen decorativa")
        h5.text-center Eventos deportivos 
        p Aquellos que se organizan para realizar una o varias actividades deportivas, o los que se relacionan con la competición o actividad deportiva, como puede ser la ceremonia de inauguración o clausura de unos juegos olímpicos.
      .tarjeta.color-acento-botones.p-4(style="background-color:#FFCA00;")
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/tema2/16.png' alt="Imagen decorativa")
        h5.text-center Eventos de patrocinio 
        p Son aquellos que financian, en su totalidad o en parte, las empresas o las marcas concretas, aunque pueden adoptar distintos formatos, por ejemplo, un festival de música patrocinado por una marca de cervezas.
    
    p.mt-5.text-center(data-aos="fade-left") Luego de tener claridad sobre el concepto de eventos y su clasificación, se incursionará en el concepto de eventos deportivos.




</template>

<script>
export default {
  name: 'Tema2',
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

<style lang="sass"></style>
