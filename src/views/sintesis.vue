<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
  
    p.mb-5 El siguiente mapa integra los criterios y especificidades de los conocimientos expuestos en el presente componente formativo:

    .row.justify-content-center
      .col-lg-10.mb-5
        figure
          img(src="@/assets/curso/temas/sintesis.svg", alt="En la elaboración de la panela se tienen en cuenta: 1. La normatividad permite: reglamentar vigencia sanitaria, conocer la legislación, presentar requisitos generales, definir sustancia permitidas y definir sustancias prohibidas. 2. Los procesamientos técnicos de producción de panela son: etapas del cultivo de caña de azúcar, germinación, acogollamiento o ahijamiento, maduración, rápido crecimiento y crecimiento. 3. En la elaboración de la panela se tienen en cuenta: a. Prelimpieza: vertimientos líquidos, residuos sólidos y tierra. b. Molienda: bagazo c. Prelimpieza del jugo: bagacillo y hojas. d. Calentamiento controlado: cenizas y gases de combustión. e. Adición de floculantes. f. Clarificación: cachaza")
      .col-auto
        a.anexo.mb-4(:href="obtenerLink('/downloads/sintesis.pdf')" target="_blank")
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
