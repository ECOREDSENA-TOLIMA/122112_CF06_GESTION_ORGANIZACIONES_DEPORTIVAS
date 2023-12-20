<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p.mb-5(data-aos="fade-right") En resumen, el tema abordado se centró en la planificación y organización de eventos deportivos, incluyendo el análisis de conceptos generales, la clasificación, la influencia de factores internos y externos, así como la importancia de la planeación. Se subrayó la definición de eventos deportivos como acontecimientos especiales con objetivos específicos y atractivos para diversas partes interesadas. Se hizo hincapié en la estructura del contenido mediante puntos clave, destacando la relevancia de considerar diversos factores para lograr el éxito en la planificación y ejecución de los eventos deportivos. A continuación, se presenta un mapa conceptual que visualiza estos aspectos de manera resumida:

    .row.justify-content-center
      .col-lg-10.mb-5
        figure
          img(src="@/assets/curso/sintesis.svg", alt="la sintesis resume los temas abordados a lo largo del componente formativo, como es la planeación de los eventos deportivos y lo que se debe contemplar en su organización, otro tema importante los factores internos y externos que sedeben tener en cuenta, el concepto, caracterísicas y calsificación de los eventos, lo que esto genera y promueve, entre otros temas importartes y necesarios para alcanzar el resultado de aprendizaje propuesto para este componente formativo.")
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
