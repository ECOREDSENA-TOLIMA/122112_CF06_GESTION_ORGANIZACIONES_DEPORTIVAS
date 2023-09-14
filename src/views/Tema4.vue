<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 4
      h1 Factores internos y externos de los eventos deportivos
    
    figure
      img(src="@/assets/curso/tema4/1.png" data-aos="zoom-in-up")
    
    p.mt-5.text-center(data-aos="zoom-in") Los eventos deportivos presentan factores internos y externos que inciden en ellos y deberán ser contemplados al momento de planear el evento.
    p.mt-4.fw-bold.text-center(data-aos="zoom-in") Observe a continuación, estos factores:

    TabsB.color-acento-contenido.mt-4
      .py-4.py-md-5(titulo="Factores internos" :icono="require('@/assets/curso/tema4/2.svg')")
        .row.col-xl-10.m-auto
          .col-md-6.col-lg-6.mb-4.mb-md-0(style="place-self:center;")
            ul.lista-ul
              li 
                i.fas.fa-check(style="color:#FE502D;")
                | Factor organizacional.
              li 
                i.fas.fa-check(style="color:#FE502D;")
                | Capacidad organizativa.
              li 
                i.fas.fa-check(style="color:#FE502D;")
                | Factor experiencia.
              li 
                i.fas.fa-check(style="color:#FE502D;")
                | Factor tiempo.
              li 
                i.fas.fa-check(style="color:#FE502D;")
                | Factor recursos propios.
              li 
                i.fas.fa-check(style="color:#FE502D;")
                | Factor costo de oportunidad.
              li 
                i.fas.fa-check(style="color:#FE502D;")
                | Factor de incertidumbre.
          .col-md-6.col-lg-6(style="place-self:center;")
            figure
              img(src='@/assets/curso/tema4/4.svg')
      .py-4.py-md-5(titulo="Factores internos" :icono="require('@/assets/curso/tema4/3.svg')")
        .row.col-xl-10.m-auto
          .col-md-6.col-lg-6.mb-4.mb-md-0(style="place-self:center;")
            ul.lista-ul
              li 
                i.fas.fa-check(style="color:#FE502D;")
                | Factor político.
              li 
                i.fas.fa-check(style="color:#FE502D;")
                | Factor interés comunidad.
              li 
                i.fas.fa-check(style="color:#FE502D;")
                | Apoyo institucional.
              li 
                i.fas.fa-check(style="color:#FE502D;")
                | Factor demográfico.
              li 
                i.fas.fa-check(style="color:#FE502D;")
                | Entusiasmo y apoyo de los ciudadanos.
              li 
                i.fas.fa-check(style="color:#FE502D;")
                | Factor mediático.
              li 
                i.fas.fa-check(style="color:#FE502D;")
                | Factor económico.
              li 
                i.fas.fa-check(style="color:#FE502D;")
                | Factor infraestructura y equipamientos.
              li 
                i.fas.fa-check(style="color:#FE502D;")
                | Factor impacto.
              li 
                i.fas.fa-check(style="color:#FE502D;")
                | Factor técnico.
              li 
                i.fas.fa-check(style="color:#FE502D;")
                | Tipo y deseo del cliente.
              li.d-flex
                i.fas.fa-check(style="color:#FE502D;")
                div #[em "Stakeholders"] (partes interesadas).
          .col-md-6.col-lg-6(style="place-self:center;")
            figure
              img(src='@/assets/curso/tema4/5.svg')




</template>

<script>
export default {
  name: 'Tema4',
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
.tabs-b.color-acento-contenido .tabs-b__tab--active
  background-color: #FFFAE5
  border: none !important
.tabs-b__content-item
  background-color: #FFFAE5
.tabs-b__tab
  border: none !important
</style>
