<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(icono="fas fa-tasks" titulo="Actividad didáctica")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
      .titulo-segundo.color-acento-contenido.mb-5
        h2 Procedimientos técnicos de producción panelera
  
      .row
        .col-6.col-md-4.col-lg-3.mb-4.mb-md-0
          .tarjeta.h-100.d-flex.align-items-center.p-4
            figure
              img(src='@/assets/curso/temas/Actividad.svg')
        .col-6.col-md-8.col-lg-9
          p Esta actividad le permitirá determinar el grado de apropiación de los contenidos del componente formativo.
          p De acuerdo con la definición planteada en la columna izquierda, arrastre cada término al lugar que considere correcto de la columna derecha.
  
          .tarjeta.actividad.p-3
            .row.justify-content-around.align-items-center
              .col-sm.mb-3.mb-sm-0
                p.fw-bold.mb-0 Arrastrar y soltar
              .col-auto
                a.boton.boton--b(:href="obtenerLink('/actividades/actividad.html')" target="_blank")
                  span Realizar
                  i.fas.fa-puzzle-piece
  
</template>

<script>
export default {
  name: 'Actividad',
}
</script>

<style lang="sass"></style>
