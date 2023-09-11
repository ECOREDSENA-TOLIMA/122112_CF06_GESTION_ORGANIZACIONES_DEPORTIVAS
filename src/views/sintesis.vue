<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p.mb-5(data-aos="fade-right") En resumen, el tema abordado se centró en la planificación y organización de eventos deportivos, incluyendo el análisis de conceptos generales, la clasificación, la influencia de factores internos y externos, así como la importancia de la planeación. Se subrayó la definición de eventos deportivos como acontecimientos especiales con objetivos específicos y atractivos para diversas partes interesadas. Se hizo hincapié en la estructura del contenido mediante puntos clave, destacando la relevancia de considerar diversos factores para lograr el éxito en la planificación y ejecución de los eventos deportivos. A continuación, se presenta un mapa conceptual que visualiza estos aspectos de manera resumida:

    .row.justify-content-center
      .col-lg-10.mb-5
        figure
          img(src="@/assets/curso/sintesis.svg", alt="alt")
      .col-auto
        a.anexo.mb-5(:href="obtenerLink('/downloads/sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
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
