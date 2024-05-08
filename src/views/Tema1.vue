<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5(style="padding-bottom:0px !important;")
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 1
      h1 Concepto y características del evento
    
    .row
      .col-lg-7.mb-4.mb-lg-0(data-aos="fade-right")
        p Según Campos y Fuente (2013), un evento tiene:
        .p-4.cont_1_1.d-flex(style="border-top:1px #FFCA00 solid;")
          i.fas.fa-quote-left.me-3(style="color:#FFCA00;font-size:28px;")
          div.mt-3
            p.mb-0 La capacidad para captar la atención de los invitados o públicos a los que va destinado (para comunicar experiencias mediante el acto en vivo, para hacer visible la marca y su aspecto relacional), hace que los eventos sean considerados una extraordinaria herramienta de comunicación y un canal perfecto para transmitir experiencias y fortalecer los mensajes que la empresa desea trasladar (p.86). #[i.fas.fa-quote-right.ms-1(style="color:#FFCA00;font-size:28px;top: 15px")] 
            .text-end.mt-4
              p.fw-bold.mb-0 Campos y Fuente (2013).
      .col-lg-5(data-aos="fade-left")
        figure
          img(src="@/assets/curso/tema1/1.png" alt="Imagen decorativa")
    
    p.mt-5(data-aos="fade-right") Es decir, un evento al ser masivo y contar con la participación de un gran número de personas y medios de comunicación, es una perfecta oportunidad para que una organización o marca, difunda, promueva y en general comunique lo que desee transmitir o dar a conocer.
    p.mt-4(data-aos="fade-left") Antes de incursionar en el tema de planeación de eventos deportivos, se comenzará definiendo el término evento. Los eventos independientemente de su tamaño, propósito y contexto, tienen características comunes como lo son:

    TabsA.color-acento-contenido.mt-5
      .tarjeta.color-acento-botones.p-4(titulo="Masivos" style="background-color:#FFFAE5;")
        .row
          .col-lg-4.mb-4.mb-lg-0.col-md-6(style="place-self:center;")
            figure
              img(src="@/assets/curso/tema1/2.png" alt="Imagen decorativa")
          .col-lg-8.col-md-6(style="place-self:center;")
            p.mb-0 Intervienen grandes cantidades de personas, incluyendo principalmente los usuarios o clientes principales del evento, espectadores, patrocinadores, proveedores y entre otras posibles partes interesadas en el evento. 
      .tarjeta.color-acento-botones.p-4(titulo="Temporales" style="background-color:#FFFAE5;")
        .row
          .col-lg-4.mb-4.mb-lg-0.col-md-6(style="place-self:center;")
            figure
              img(src="@/assets/curso/tema1/3.png" alt="Imagen decorativa")
          .col-lg-8.col-md-6(style="place-self:center;")
            p.mb-0 Todo evento tiene un principio y un final. Pueden ser tan cortos con una duración de horas y tan largos con una duración de meses. 
      .tarjeta.color-acento-botones.p-4(titulo="Acontecimiento especial" style="background-color:#FFFAE5;")
        .row
          .col-lg-4.mb-4.mb-lg-0.col-md-6(style="place-self:center;")
            figure
              img(src="@/assets/curso/tema1/4.png" alt="Imagen decorativa")
          .col-lg-8.col-md-6(style="place-self:center;")
            p.mb-0 Un evento requiere ser especial y diferente a lo que generalmente se hace desde sus medios, contenidos, presentación, para captar el interés de las partes interesadas.
      .tarjeta.color-acento-botones.p-4(titulo="De índole social" style="background-color:#FFFAE5;")
        .row
          .col-lg-4.mb-4.mb-lg-0.col-md-6(style="place-self:center;")
            figure
              img(src="@/assets/curso/tema1/5.png" alt="Imagen decorativa")
          .col-lg-8.col-md-6(style="place-self:center;")
            p.mb-0 El enfoque principal del evento, ya sea en personas o no (como en exposiciones caninas, jornadas de vacunación felina, exposiciones ecuestres, donde no son el foco), atraerá a un sector de la sociedad.
    
    .cont_1_2.mt-4.pt-5.pb-5
      .col-xl-10.m-auto
        .tabla-a.color-acento-botones(data-aos="flip-up")
          table
            thead(style="border:0;")
              tr
                td.p-4.text-white(colspan="2" style="background-color:#2D54FE;") Teniendo en cuenta estas características, se abordará el concepto del evento que aportan diferentes autores:
            tbody
              tr.bg-white
                td.p-4 Los eventos son acontecimientos especiales, “iniciativas, sucesos y/o hechos de distinta índole y naturaleza, de presencia pública, promovidos y/o realizados por organizaciones fuera de su dinámica habitual para conseguir distintos objetivos” (Arnaldi,1968, p.84).
                td.p-4 “Acontecimiento programado, que puede ser de índole cultural, de ocio o naturaleza profesional, sin discriminar necesariamente cuál es el grado de importancia” y suelen contar con nombres únicos que le distingan, que le confieran un carácter de singularidad o autenticidad y, por consiguiente, el ciudadano lo identifique claramente entre el resto de los eventos (Ortega, 2010, p.85).
        
        p.mt-4(data-aos="fade-right") Conforme a la tabla anterior, los autores coinciden al definir el evento en incorporar el término de acontecimiento especial, por lo que un evento se considera único e irrepetible, sin importar si este se realiza periódicamente. 



      
      
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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
.cont_1_1, .cont_1_1 *
  position: relative
.cont_1_1:before
  content: ''
  position: absolute
  width: 50%
  height: 60%
  bottom: 10px
  right: 0
  background-color: #E9EDFF
.tabs-a__tab
  background-color: #F6F6F6
  height: 100%
.cont_1_2, .cont_1_2 *
  position: relative
.cont_1_2:before
  content: ''
  position: absolute
  width: 125%
  left: -15%
  height: 100%
  top: 0
  background: url(../assets/curso/tema1/6.png)
  background-size: cover
  background-position: center
</style>
