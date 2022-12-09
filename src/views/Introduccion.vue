<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5(data-aos="fade")
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .row 
      .col-lg-7(data-aos="fade-left")
        p Como bien sabe, la contaminación atmosférica es la consecuencia producida por el consumo irracional de los combustibles fósiles como el carbón y el petróleo, los cuales son vitales en los diferentes procesos productivos que apalancan el consumo y que permiten mover la economía del mundo.
        .cajon.color-acento-contenido.p-5.mb-4
          p Por lo anterior, la importancia de los combustibles en la sociedad se refleja directamente en su desarrollo y en los impactos que se producen por la generación de las emisiones, especialmente de compuestos de azufre y nitrogenados, los cuales quedan inmersos en el aire que se respira, por lo que producen directamente en el hombre enfermedades respiratorias.
      .col-lg-5(data-aos="fade-down")
        img(src='@/assets/curso/1.png', alt='Texto que describa la imagen')
    p.mt-3 Como puede ver, el cambio climático está impactando fuertemente el medio ambiente y el contexto en el cual vive el ser humano. Aquí se hace necesario profundizar en algunos temas, con el fin de que entienda cómo desde su contexto directo o indirecto puede aportar para alcanzar los Objetivos de Desarrollo Sostenible definidos por los países que conforman la UNESCO en las Naciones Unidas (s. f.) 

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
