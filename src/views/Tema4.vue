<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5(data-aos="fade")
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Normativa de emisiones
    p Para poder cumplir con los Objetivos de Desarrollo Sostenible, agenda 2030, Colombia debe diseñar una serie de normas y resoluciones, con el fin de disminuir la emisión de gases o partículas al aire. Por lo anterior, se invita a revisar este tema en el siguiente documento descargable.
    img(src='@/assets/curso/tema4/1.png', alt='Texto que describa la imagen')
    .row.justify-content-center
      .col-lg-10
        .tarjeta.color-primario.p-3.mb-5.mt-4
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema1/pdf.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h5 CF9_PDF2_ 4_ Normas de emisión
                .col-sm-auto
                  a.boton.color-acento-botones.texto-blanco(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download  
        p.mt-2 Como parte de su aprendizaje, le invito a revisar el siguiente tema, con el fin de comprender cómo se interpretan los resultados de las emisiones.
    p Conocer el marco normativo que regula la contaminación del aire en nuestro país es muy importante para establecer las acciones de prevención y control de los contaminantes que nos afectan en la actualidad. En esta sección, conocerá: las leyes, los decretos, las resoluciones, los protocolos y demás documentación vigente.
    separador
    #t_4_1.titulo-segundo.color-acento-contenido
      h2 4.1   Calidad del aire
    .row
      .col-lg-7
        .cajon.color-acento-contenido.p-4.mb-4
          p Las normas de calidad del aire en Colombia se convierten en la base para el seguimiento, así lo afirma El Instituto de Hidrología Meteorología y Estudios Ambientales –IDEAM, donde “... el monitoreo y control de la contaminación atmosférica ha tomado día a día mayor relevancia, debido a que, según cifras de la Organización Mundial para la Salud, una de cada ocho muertes ocurridas a nivel mundial es ocasionada por la contaminación del aire. A nivel nacional, el Departamento Nacional de Planeación estimó que, durante el año 2015, los efectos de este fenómeno estuvieron asociados a 10.527 muertes y 67,8 millones de síntomas y enfermedades. 
        p  Adicionalmente, los costos ambientales asociados a la contaminación atmosférica en Colombia, durante los últimos años, se incrementaron, pasando de 1,1% del PIB de 2009 ($5,7 billones de pesos) a 1,59% del PIB de 2014 ($12 billones de pesos) y del 1,93% del PIB en 2015 ($15.4 billones de pesos), lo cual pone en evidencia la necesidad de seguir implementando estrategias para controlar, evaluar y monitorear estas sustancias”.
      .col-lg-5
        img(src='@/assets/curso/tema4/2.png', alt='Texto que describa la imagen')
    .row.justify-content-center.mt-4
      .col-lg-10
        .tarjeta.color-primario.p-3.mb-5.mt-4
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema2/i1.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h5 Como parte de su aprendizaje, se invita a revisar la página web del IDEAM (2014), donde encontrará información sobre la contaminación y calidad ambiental. Esta es una entidad del Estado colombiano que se encarga de hacer investigación sobre el medio ambiente. Para acceder al enlace, se recomienda ir a la sección de referencias.
    .row.mt-3
      .col-lg-2
        .row.p-1.colorazul
          h3.text-white.mt-1 Normas asociadas      
    p.mt-2 A continuación, encontrará un listado de normas colombianas que dan las pautas a nivel nacional en el tema del manejo de la contaminación del aire. Para profundizar en el tema, puede ir a la sección de materiales de apoyo.
    .row
      .col-lg-6
        .row.mb-5
          LineaTiempoD.color-secundario
            p.text-small(numero="1" titulo="Resolución 2254 de 2017") Por la cual se adopta la norma de calidad del aire ambiente y se dictan otras disposiciones.
            
            p.text-small(numero="2" titulo="Resolución 650 de 2010") Por la cual se adopta el Protocolo para el Monitoreo y Seguimiento de la Calidad del Aire.
            p.text-small(numero="3" titulo="Resolución 2154 de 2010") Por la cual se ajusta el Protocolo para el Monitoreo y Seguimiento de la Calidad del Aire adoptado a través de la Resolución 650 de 2010 y se adoptan otras disposiciones.
  
              
      .col-lg-6
        img(src='@/assets/curso/tema4/3.png', alt='Texto que describa la imagen')
    .row.justify-content-center.mt-4
      .col-lg-10
        .tarjeta.color-primario.p-3.mb-5.mt-4
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema2/i1.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h5 Como parte de su aprendizaje autónomo, se invita a revisar las anteriores resoluciones con el fin de reforzar su aprendizaje sobre la normatividad en Colombia. Estas las puede encontrar en la sección de referencias.
    .row.mt-4
      .col-lg-2
        .row.p-1.colorazul
          h4.text-white.mt-1 Protocolo asociado    
    p.mt-3 Un protocolo es una serie de datos detallados sobre un proceso de actuación científica o técnica, por lo que a continuación se mencionan dos que son claves para la conceptualización y aplicación de sus conocimientos en su vida laboral.
    TabsA.color-acento-contenido.mb-5

      .tarjeta.color-acento-contenido--borde.p-4(titulo="Protocolo para el monitoreo y seguimiento de la calidad del aire")
        p <strong>Protocolo para el monitoreo y seguimiento de la calidad del aire.</strong> Nota: Ministerio de Medio Ambiente, Vivienda y Desarrollo Territorial. ¨Protocolo para el monitoreo y seguimiento de la calidad del aire¨ (2008).
      .tarjeta.color-acento-contenido--borde.p-4(titulo="Manual de diseño de Sistemas de Vigilancia de Calidad del Aire.")
        p <strong>Manual de diseño de Sistemas de Vigilancia de Calidad del Aire.</strong> Nota: Ministerio de Medio Ambiente, Vivienda y Desarrollo Territorial. ¨Protocolo para el monitoreo y seguimiento de la calidad del aire. Manual de diseño de sistemas de vigilancia de la calidad del aire¨ (2010). 
    .row.justify-content-center.mt-4
      .col-lg-10
        .tarjeta.color-primario.p-3.mb-5.mt-4
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema2/i1.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h5 Para reforzar su aprendizaje, se invita a revisar los anteriores documentos en la sección de referencias, con el fin de leer los documentos completos.
    separador
    #t_4_2.titulo-segundo.color-acento-contenido
      h2 4.2 Fuentes fijas                
    .row
      .col-lg-7
        .cajon.color-acento-contenido.p-4.mb-4
          p Las fuentes fijas puntuales, mejor conocidas como “chimeneas” o ductos, por donde se expulsan gases contaminantes ( Mp,Sox,Nox, Co,.Cov´s, entre otros) de las industrias que hacen parte del sector productivo que mueve la economía de nuestro país, aportan de manera importante al continuo deterioro de la calidad del aire que se respira, especialmente en la principales ciudades del país. Por esta razón, la normativa asociada a las fuentes fijas es fundamental para el seguimiento y control de las emisiones en Colombia. 
        p A continuación, se menciona la norma asociada relacionada con este tema.
      .col-lg-5
        img(src="@/assets/curso/tema4/4.png")
    .row.mt-4
      .col-lg-2
        .row.p-1.colorazul
          h4.text-white.mt-1 Normas asociadas
    p.mt-3 Resolución 909 de 2008.  Por la cual se establecen las normas y estándares de emisión admisibles de contaminantes a la atmósfera por fuentes fijas y se dictan otras disposiciones.
    .row.justify-content-center.mt-4
      .col-lg-10
        .tarjeta.color-primario.p-3.mb-5.mt-4
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema2/i1.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h5 Para complementar su aprendizaje, se invita a revisar la página web del Ministerio de Medio Ambiente, Vivienda y Desarrollo Territorial (2008), donde se toca el tema de la resolución 909 de 2008. Para esto debe ir a la sección de referencias
    .row.mt-4
      .col-lg-4
        .row.p-1.colorazul
          h4.text-white.mt-1 Métodos de medición y protocolos asociados
    .row.mt-3
      .col-lg-6
        .row.bgw.p-3
          p Resolución 0935 de 2011. Por la cual se establecen los métodos para la evaluación de emisiones contaminantes por fuentes fijas y se determina el número de pruebas o corridas para la medición de contaminantes en fuentes fijas. Nota: Instituto de Hidrología, Meteorología y Estudios Ambientales de Colombia (2011). 

      .col-lg-6
        .row.bgw.p-3
          p Protocolo para el control y vigilancia de la contaminación atmosférica generada por fuentes fijas. Nota: Ministerio de Medio Ambiente, Vivienda y Desarrollo Territorial. ¨Protocolo para el monitoreo y seguimiento de la calidad del aire¨ (2008). 
    .row.justify-content-center.mt-4
      .col-lg-10
        .tarjeta.color-primario.p-3.mb-5.mt-4
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema2/i1.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h5 Se invita a profundizar en el tema accediendo a la sección de referencias, donde encontrará la normatividad y regulaciones del IDEAM.
    .titulo-sexto.color-secundario
      h5 Figura 4
      span Métodos de medición             
    img(src="@/assets/curso/tema4/5.svg")

</template>

<script>
export default {
  name: 'Tema4',
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
.tarjeta--gris
  background-color: #D2E1F1
.linea-tiempo-d.color-secundario .linea-tiempo-d__item--selected .linea-tiempo-d__item__number
  background-color: #C9D9B6
.linea-tiempo-d__item__content.tarjeta.tarjeta--gris
  background-color: #F8F8F8
</style>
