<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5(data-aos="fade")
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 5
      h1 Interpretación de los resultados de emisiones
    .row
      .col-lg-6
        p Uno de los pasos más importantes para hacer control de la calidad del aire que hay en Colombia es hacer mediciones de manera periódica de las emisiones lanzadas al aire y luego realizar la interpretación de los datos obtenidos en ellas, con el fin de identificar si están acordes con los estándares internacionales definidos para el control de la concentración de estas sustancias que las empresas lanzan al medio ambiente, esto con el fin de diseñar políticas y dar pautas para su adecuado manejo, y de esa forma cumplir con la agenda 2030 definida por la UNESCO.
        p Para profundizar en este tema, se invita a descargar el siguiente documento.
      .col-lg-6
        img(src="@/assets/curso/tema5/1.png")
    .row.mt-3
      .col-lg-7
        .cajon.color-acento-contenido.p-4.mb-4
          p En Colombia, las normas relacionadas con la emisión e inmisión de contaminantes al aire establecen una serie de correcciones a los resultados que se registran en campo después de obtenidas las muestras de los contaminantes. A tales adaptaciones de presión y temperatura se les denominan correcciones de referencia, las cuales establecen a una temperatura 298.15 ºK y una presión atmosférica de 760 mmHg o 1 atmósfera.
      .col-lg-5
        img(src="@/assets/curso/tema5/2.png")
    p.mt-3 A continuación, verá cómo se realizan estas correcciones tanto en inmisión como en emisión.
    separador
    #t_5_1.titulo-segundo.color-acento-contenido
      h2 5.1   Correcciones de resultados en inmisión o calidad del aire   
    p Las correcciones de resultados en emisión o calidad del aire son establecidas en el Protocolo para el Monitoreo y Seguimiento de la Calidad del Aire, Manual de Operación de Sistemas de Vigilancia de la Calidad del Aire, del año 2008. 
    .row.mt-3
      .col-lg-5
        img(src="@/assets/curso/tema5/3.png")

      .col-lg-7
        .cajon.color-acento-contenido.p-4.mb-4
          p A continuación, se presenta una metodología para el cálculo de las concentraciones a condiciones de referencia (Temperatura: 298.15 ºK y Presión: 760 mmHg ≈ 101325 Pa ≈ 101.325 kPa) a partir de los valores promedios horarios de concentración.
        p La Resolución 2254 de 2017 establece, en su Capítulo I, Artículo 2, los niveles máximos permisibles para contaminantes criterio y los tiempos de exposición para cada contaminante.
    .row.justify-content-center.mt-4
      .col-lg-10
        .tarjeta.color-primario.p-3.mb-5.mt-4
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema2/i1.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h5 Para reforzar su aprendizaje, se invita a revisar los documentos mencionados con anterioridad, los cuales se pueden encontrar en la sección de referencia. Esto con el fin de que profundice los conceptos.
    p Para comparar los datos de calidad de aire obtenidos de las mediciones con la norma, debe hacer un procedimiento básico. Se sugiere el procedimiento que a continuación se presenta:
    ul.lista-ul--color
      li
        i.fas.fa-check
        | Con los datos ya validados (e identificados con banderas) y organizados por orden cronológico, se calculará primeramente el valor promedio horario (promedio de todos los datos recolectados y válidos obtenidos en una hora).
      li
        i.fas.fa-check
        | Una vez se tienen estimados los valores promedio de concentración horaria del contaminante, se procede con el cálculo de la media móvil.
      li
        i.fas.fa-check
        | Debido a que las normas establecidas en la legislación colombiana se encuentran definidas a condiciones de referencia o condiciones estándar, es necesario expresar cada promedio de ocho (8) horas obtenido a estas mismas condiciones estándar. En ningún momento es correcto expresar la norma nacional (condiciones de referencia) a norma local (condiciones propias de cada ciudad), para realizar la comparación.
      li
        i.fas.fa-check
        | Para expresar la media móvil (obtenida a partir de los datos promedios horarios de la estación) a condiciones de referencia o condiciones estándar y poder establecer la comparación con la norma, se parte de la ecuación de gas ideal y se establecen las correspondientes relaciones, esto es:
    .row.justify-content-center
      .col-lg-6
        .row.justify-content-center.bgt.p-4
          .col-lg-5
            .row.coloaqz.p-1
              h4.text-center.mb-0 PV=nRT
          p Donde:
          p.mb-0 P: presión.
          p.mb-0 V: volumen.
          p.mb-0 n: número de moles.
          p.mb-0 R: constante de los gases ideales (8.314 m3Pa/Kmol.K ≈ 0.082 l.atm/mol.K)
          p.mb-0 T: temperatura (siempre expresada en grados Kelvin, ºK).
    .row.justify-content-center.mt-3
      .col-lg-10
        p A través de la ecuación del gas ideal, puede determinarse la concentración en función de la presión, la temperatura y el peso molecular de la sustancia de la que se desea cuantificar su presencia en el gas, de la siguiente forma:
    .row.mt-4.align-items-center
      .col-lg-2
      .col-lg-3
        img(src="@/assets/curso/tema5/4.svg")

      .col-lg-5
        p.mb-0 En esta serie de ecuaciones, se encuentran los siguientes términos:
        p.mb-0 <strong>m:</strong> masa de la sustancia que se quiere determinar en el gas (Kg)
        p.mb-0 <strong>PM:</strong> peso molecular de la sustancia a determinar (Kg/Kmol)
        p.mb-0 <strong>C:</strong> Concentración de la sustancia en el gas (Kg/m3 ó g/l)
    .row.justify-content-center.mt-4
      .col-lg-10
        p Ahora bien, del tratamiento matemático anterior realizado a la ecuación del gas ideal, se llega a la conclusión que, dependiendo del contaminante (de sus propiedades físicas, como masa y peso molecular) y de las condiciones atmosféricas (presión y temperatura), se obtendrán determinados valores de concentración.
        p Por lo tanto, es válido afirmar que la concentración del contaminante i, a condiciones estándar, es igual al producto del peso molecular de dicho contaminante por la relación existente entre las condiciones estándar de presión y temperatura (<strong>Pst, Tst</strong>):
    .row.justify-content-center.mt-4
      .col-lg-2
        img(src="@/assets/curso/tema5/5.svg")
    .row.justify-content-center.mt-4
      .col-lg-10
        p Como los datos promedio de concentración que se obtienen del monitoreo de calidad de aire corresponden a los valores de concentración de cada contaminante en particular obtenidos a las condiciones locales de presión y temperatura, y dichas condiciones son diferentes a las condiciones de referencia, entonces los datos que se obtienen, en realidad, de concentración corresponden a:
    .row.justify-content-center
      .col-lg-10
        .row.justify-content-center.bgt.p-4.align-items-center  
          .col-lg-3
            img(src="@/assets/curso/tema5/6.svg")
          .col-lg-1
          .col-lg-8
            p Donde
            h5.mb-0 (C  ) j : concentración del contaminante i en la región o ciudad j.
            h5.mb-0 (P) j : presión en la región o ciudad j, es decir, la condición local de presión.
            h5.mb-0 (T)  : temperatura en la región o ciudad j, es decir, la condición local de temperatura.
            h5.mb-0 PM  : peso molecular del contaminante medido.
            h5.mb-0 R: constante de los gases ideales (8.314 m3. Pa/kmol.K ≈ 0.082 l.atm/mol.K).
    p.mt-4 Concluyendo, los datos obtenidos de valores promedio (media móvil para el periodo de tiempo que se va a evaluar) se tienen referenciados a las condiciones locales de la región o ciudad para los cuales se realizó la medición; pero estos, a su vez, deben ser comparados con la norma nacional, la cual se encuentra expresada a condiciones de referencia o condiciones estándar (760 mmHg de presión o 101325 Pa o 101.325 KPa y a una temperatura de 298.15 ºK). 
    p Por ese motivo, es necesario expresar los datos promedios obtenidos de la medición a valores promedios de concentración expresados a condiciones estándar o de referencia. Esto se realiza de la siguiente forma: los datos promedios de ocho horas obtenidos a condiciones locales  (C  )j son expresados bajo condiciones de referencia.
    p Finalmente, tan pronto se hayan expresado los datos promedio de concentración a condiciones de referencia o condiciones estándar, se procede a compararlos con la norma nacional para el periodo de tiempo estipulado.
    .row.justify-content-center.mt-4
      .col-lg-10
        .tarjeta.color-primario.p-3.mb-5.mt-4
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema2/i1.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h5 Para continuar aprendiendo, se invita a revisar la página web del Ministerio de Ambiente, Vivienda y Desarrollo Territorial (2008), quienes realizaron el Protocolo para el Monitoreo y Seguimiento de la Calidad del Aire. Manual de Operación de Sistemas de Vigilancia de la Calidad del Aire (p. 121-124). Para acceder a la información, puede ir a la sección de referencias.
    separador
    #t_5_2.titulo-segundo.color-acento-contenido
      h2 5.2   Correcciones de resultados en emisión o fuentes fijas                
    p Según lo establecido en la Resolución 909 de 2008, en el Capítulo XXI disposiciones finales, Artículo 86, todos los resultados de las mediciones de los diferentes contaminantes deben ser corregidos a condiciones de referencia, por medio de la siguiente ecuación:
    .row.justify-content-center
      .col-lg-10
        .row.justify-content-center.bgt.p-4.align-items-center  
          .col-lg-3
            img(src="@/assets/curso/tema5/7.png")
          .col-lg-1
          .col-lg-8
            p Donde
            p.mb-0 C    : Concentración del contaminante a condiciones de referencia en mg/m3
            p.mb-0 C    : Concentración del contaminante a condiciones locales en mg/m3
            p.mb-0 T    : Temperatura de los gases a la salida del ducto en °K
            p.mb-0 P    : Presión a condiciones de referencia en mm Hg
            p.mb-0 P    :  Presión de los gases a la salida del ducto en mm Hg
            p.mb-0 T    : Temperatura a condiciones de referencia en °K.
    p.mt-4 La misma resolución, en su Artículo 88, define adicionalmente que los resultados en los que se vean implicados los contaminantes derivados de una relación de combustión deben realizar adicionalmente la corrección de oxígeno, de acuerdo con la siguiente ecuación:
    .row.justify-content-center
      .col-lg-10
        .row.justify-content-center.bgt.p-4.align-items-center  
          .col-lg-3
            img(src="@/assets/curso/tema5/8.png")
          .col-lg-1
          .col-lg-8
            p Donde
            p.mb-0 C              : Concentración del contaminante a condiciones de referencia con la corrección de oxígeno, basado en el oxígeno de referencia, de conformidad con lo establecido en la presente resolución.

            p.mb-0 C           : Concentración del contaminante a condiciones de referencia.

            p.mb-0 %0_(2ref): Oxígeno de referencia de la medición, de conformidad con lo establecido en la presente resolución, en porcentaje (%).

            p.mb-0 X%: Oxígeno medido a la salida de los gases, en porcentaje (%).

    p.mt-4 Dependiendo si la fuente de contaminación proviene de una actividad industrial más NO de una fuente de combustión externa, la resolución 909 de 2008, Artículo 87, establece que se debe calcular el flujo del contaminante. Para calcular el flujo de los contaminantes, se debe emplear la siguiente ecuación: 
    .row.justify-content-center
      .col-lg-10
        .row.justify-content-center.bgt.p-4.align-items-center  
          .col-lg-3
            img(src="@/assets/curso/tema5/9.png")
          .col-lg-1
          .col-lg-8
            p Donde
            p.mb-0 C              : Concentración del contaminante a condiciones de referencia con la corrección de oxígeno, basado en el oxígeno de referencia, de conformidad con lo establecido en la presente resolución.
            p.mb-0 C           : Concentración del contaminante a condiciones de referencia.
            p.mb-0 %0_(2ref): Oxígeno de referencia de la medición, de conformidad con lo establecido en la presente resolución, en porcentaje (%).
            p.mb-0 X%: Oxígeno medido a la salida de los gases, en porcentaje (%).

    p.mt-4 Dependiendo si la fuente de contaminación proviene de una actividad industrial más NO de una fuente de combustión externa, la resolución 909 de 2008, Artículo 87, establece que se debe calcular el flujo del contaminante. Para calcular el flujo de los contaminantes, se debe emplear la siguiente ecuación: 
    .row.justify-content-center.mt-4
      .col-lg-10
        .tarjeta.color-primario.p-3.mb-5.mt-4
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema2/i1.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h5 Para profundizar en el tema, se invita a ingresar a la página web del Ministerio de Ambiente, Vivienda y Desarrollo Territorial, donde aparece la Resolución 909 de 2008. Por la cual se establecen las normas y estándares de emisión admisibles de contaminantes a la atmósfera por fuentes fijas y se dictan otras disposiciones. (2008, p. 29). Esta información está ubicada en la sección de referencias.
    p Una vez obtenidos los resultados, se comparan directamente con la norma. Dependiendo si la fuente corresponde a procesos relacionados a actividades industriales, se toma como base el Artículo 4, como lo muestra la siguiente tabla. 
    .titulo-sexto.color-secundario
      h5 Tabla 8
      span Estándares de emisión admisible       
    img(src="@/assets/curso/tema5/10.svg")
    p Las dioxinas y furanos se expresan en las siguientes unidades (ng-         ), EQT: Equivalencia de toxicidad.
    p Si, por el contrario, corresponde a una fuente de combustión externa, se tomarán como referentes los estándares contenidos en el Capítulo III, Artículos 7 y 8, y hacer la comparación directa.
    .titulo-sexto.color-secundario
      h5 Tabla 9
      span Estándares de emisión admisibles en equipos de combustión externa     
    img(src="@/assets/curso/tema5/11.svg")
    .titulo-sexto.color-secundario
      h5 Tabla 10
      span Estándares de emisión admisibles en equipos de combustión externa nuevos
    img(src="@/assets/curso/tema5/12.svg")
    .row.p-3
      p Cuando se habla del concepto inmisión, se están relacionando los contaminantes presentes en el aire que el ser humano respira; a ello se le denomina calidad del aire y la normativa que en la actualidad la regula es la Resolución 2254 de 2017. Y cuando se refiere al concepto de emisión, se está hablando de los contaminantes que emiten las fuentes móviles y fuentes fijas desde sus ductos o chimeneas; las normas en Colombia que las regulan actualmente son las Resoluciones 910 y 909 de 2008.
      p Como conclusión, Colombia ha venido cumpliendo el pacto propuesto por la UNESCO con la Agenda 2030- Objetivos de Desarrollo Sostenible, puesto que tiene normatividad y resoluciones, se hace seguimiento al sector productivo y se definen pautas a seguir en el caso de que se encuentre que se está saliendo una empresa del límite de emisiones dañinas al medio ambiente.
      p Para profundizar en el tema, se invita a revisar la zona de referencias, con el fin de aclarar su conocimiento al leer directamente los contenidos que las entidades del Estado colombiano han diseñado para cuidar el medio ambiente y, de esa forma, poder cumplir con los Objetivos de Desarrollo Sostenible que la Agenda 2030 y la Unesco han desarrollado.
</template>

<script>
export default {
  name: 'Tema5',
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

<style lang="sass"></style>
