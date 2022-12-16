<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5(data-aos="fade")
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Combustión
    .row
      .col-lg-6
        p Las diferentes sustancias presentes en la naturaleza interactúan entre ellas continuamente. Por lo que sucesos tan comunes como la combustión de un fósforo, la oxidación de un metal en el ambiente o nuestra respiración obedecen a lo que se conocen como reacciones químicas. Se trata de un proceso por el cual una o más sustancias, llamadas reactivos, se transforman en otra u otras sustancias con propiedades diferentes, llamadas productos.
        p En una reacción química, los enlaces entre los átomos que forman los reactivos se rompen. Entonces, estos se reorganizan de otro modo, formando unos nuevos y dando lugar a una o más sustancias diferentes a las iniciales.
        .cajon.color-acento-contenido.p-4.mb-4
          p ¨La respiración celular puede ser considerada como una serie de reacciones químicas de óxido-reducción en las cuales las moléculas combustibles son paulatinamente oxidadas y degradadas liberando energía¨.
          p (Universidad Nacional de Lomas de Zamora, s. f.) 
      .col-lg-6
        img(src='@/assets/curso/tema3/1.png', alt='Texto que describa la imagen')
    separador
    #t_3_1.titulo-segundo.color-acento-contenido
      h2 3.1 Leyes de las reacciones químicas
    p A continuación, se presenta un objeto de aprendizaje donde podrá revisar los exponentes de las leyes de las reacciones químicas.
    TabsA.color-acento-contenido.mb-5.mt-4

      .tarjeta.color-acento-contenido--borde.p-4(titulo="Leyes de las reacciones químicas")
        .row
          .col-lg-6
            img(src="@/assets/curso/tema3/2.png")    
          .col-lg-6
            p La naturaleza está compuesta por elementos físicos y químicos. Aquí es importante ver cómo las Leyes de las reacciones químicas generan cambios o transformaciones debido a que al mezclarse pueden ganar o perder elementos, lo que lleva a que se formen otras sustancias completamente diferentes.
      .tarjeta.color-acento-contenido--borde.p-4(titulo="Leyes de las reacciones químicas")
        .row
          .col-lg-6
            img(src="@/assets/curso/tema3/3.png")    
          .col-lg-6
            p Esta Ley establece que, en toda reacción química, la masa de las sustancias que reaccionan es igual a la masa de las sustancias que se forman. 
            p Reacción química en la cual una molécula de metano y dos moléculas de oxígeno reaccionan por combustión y se producen dos moléculas de agua y una de dióxido de carbono. Antes y después de la reacción, el número de átomos de oxígeno (4), hidrógeno (4) y carbono (1) es el mismo.
            p Por lo tanto, la masa total de los reactivos es la suma de la masa de todos los átomos, lo que quiere decir que es igual a la masa total de los productos.
      .tarjeta.color-acento-contenido--borde.p-4(titulo="Leyes de las reacciones químicas")
        .row
          .col-lg-6
            img(src="@/assets/curso/tema3/4.png")    
          .col-lg-6
            p La Ley de las proporciones definidas dice que cuando dos o más elementos se combinan para formar un compuesto, la relación entre sus masas es constante.
      .tarjeta.color-acento-contenido--borde.p-4(titulo="Leyes de las reacciones químicas")
        .row
          .col-lg-6
            img(src="@/assets/curso/tema3/5.png")    
          .col-lg-6
            p La Ley de los volúmenes de combinación dice que cuando los gases se combinan para obtener compuestos también gaseosos, sus respectivos volúmenes guardan una proporción de números enteros sencillos, siempre que se midan en iguales condiciones de presión y temperatura.
      .tarjeta.color-acento-contenido--borde.p-4(titulo="Leyes de las reacciones químicas")
        .row
          .col-lg-6
            img(src="@/assets/curso/tema3/6.png")    
          .col-lg-6
            p En 1811, Amadeo Avogadro (1776-1856) explicó esta ley partiendo de dos ideas: • En volúmenes iguales de distintos gases, a la misma presión y temperatura, existe el mismo número de partículas. Las últimas partículas de los elementos gaseosos no son átomos sino agregados de átomos iguales, a los que llamó moléculas.
    separador
    #t_3_2.titulo-segundo.color-acento-contenido
      h2 3.2 Ecuaciones químicas   
    .row
      .col-lg-6
        p Las ecuaciones químicas constituyen una forma abreviada de expresar por escrito una reacción química, por medio de símbolos y fórmulas. En una ecuación química las sustancias que se combinan entre sí son los reactivos y se escriben a la izquierda. A la derecha se escriben los productos, que son las sustancias que se forman. Los reactivos se separan de los productos por medio de una flecha, su dirección es de reactivos → productos.
        p Los símbolos y fórmulas utilizados en la ecuación deben ir acompañados por un subíndice dentro de un paréntesis que indica los estados de agregación de cada sustancia (s) (l) (g). También se puede colocar el subíndice (ac) que significa que la sustancia está en disolución acuosa. Arriba o debajo de la flecha pueden aparecer las condiciones necesarias para que se efectúe la reacción, por ejemplo, indica que se requiere energía en forma de calor para que se lleve a cabo la reacción.
      .col-lg-6
        img(src="@/assets/curso/tema3/7.png")    
    p En toda reacción química no se crean ni se destruyen átomos, los que están presentes se reorganizan para formar nuevas sustancias, conservándose la materia. ¿Recuerda la Ley de conservación de la materia? Importante para comprender el equilibrio entre reactivos y productos en una reacción.
    .row.justify-content-center
      .col-lg-10
        .tarjeta.color-primario.p-3.mb-5.mt-4
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema1/pdf.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h5 Para profundizar en el tema, se invita a ver el documento ecuaciones químicas, que se encuentra en la sección de referencias. 
                .col-sm-auto
                  a.boton.color-acento-botones.texto-blanco(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download      
    .row.justify-content-center
      .col-lg-8
        p Para continuar, con el tema, se invita a revisar el siguiente ejemplo:
        .titulo-sexto.color-secundario
          h5 Figura 14
          span Ecuación química 
        img(src="@/assets/curso/tema3/8.png")
        p.mt-2 Nota. Tomada de Peña y Bautista (2018). https://explorerbiogen.wordpress.com/2018/02/01/naturaleza-de-las-reacciones-quimicas/
    .row.mt-4
      .col-lg-3
        .row.p-1.colorazul
          h4.text-white.mt-1 Tipos de reacciones químicas.
    p.mt-4 Hay diferentes tipos de reacciones químicas y varias formas de clasificarlas según el criterio elegido. Estos pueden ser: el energético, el cinético, la transformación que se produce y la partícula intercambiada. Revise el siguiente objeto de aprendizaje para acceder a mayor información.
    TabsB.color-acento-botones.mb-5
      .py-4.py-md-5(titulo="Criterio energético" :icono="require('@/assets/curso/tema3/f1.svg')")
        .row.justify-content-center
          h3 Criterio energético
          .col-md-5.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema3/9.png', alt='Texto que describa la imagen')
            p.mt-2 <strong>Endotérmica:</strong> es aquella en la cual se absorbe el calor.
          .col-md-5
            figure
              img(src='@/assets/curso/tema3/10.png', alt='Texto que describa la imagen')
            p.mt-2 <strong>Exotérmica:</strong> en esta reacción química, se libera energía en forma de calor.
      .py-4.py-md-5(titulo="Criterio cinético" :icono="require('@/assets/curso/tema3/f2.svg')")
        .row.justify-content-center
          h3 Criterio cinético
          .col-md-5.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema3/13.png', alt='Texto que describa la imagen')
            p.mt-2 <strong>Rápida:</strong>  es aquella en la cual no se puede medir su velocidad por la forma en que se produce.
          .col-md-5
            figure
              img(src='@/assets/curso/tema3/14.png', alt='Texto que describa la imagen')
            p.mt-2 <strong>Lenta:</strong>  en esta reacción química, se puede medir su velocidad de producción.
      .py-4.py-md-5(titulo="Según la transformación que se produce" :icono="require('@/assets/curso/tema3/f3.svg')")
        .row.justify-content-center
          h3 Según la transformación que se produce
          .col-md-5.mb-4.mb-md-0
            p Son aquellas en las que dos o más sustancias (reactivos) se combinan para formar un producto más complejo. Estas pueden ser:
            figure
              img(src='@/assets/curso/tema3/11.svg', alt='Texto que describa la imagen')
          .col-md-5
            h5 Ejemplo:
            figure
              img(src='@/assets/curso/tema3/12.png', alt='Texto que describa la imagen')
      .py-4.py-md-5(titulo="Según la partícula intercambiada" :icono="require('@/assets/curso/tema3/f4.svg')")
        .row.justify-content-center
          h3 Según la partícula intercambiada
          .col-md-5.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema3/16.svg', alt='Texto que describa la imagen')
          .col-md-5
            h5 Ejemplo:
            figure
              img(src='@/assets/curso/tema3/15.png', alt='Texto que describa la imagen')
    p A continuación, se explican las reacciones según la transformación que se produce:
    AcordionA(tipo="b" clase-tarjeta="tarjeta tarjeta--azul")
      .row.justify-content-center(titulo="Reacciones de síntesis")
        .col-md-11.mb-4.mb-md-0
          p Son reacciones químicas en las que dos o más sustancias (reactivos) se combinan para formar otra distinta (producto), más compleja. Si los reactivos son elementos, se llaman reacciones de formación.
          p.mb-2 La ecuación química general es:  A + B → AB 
          h5.mb-0 Ejemplos:
          p.mb-1 Fe + S → FeS
          p 4 Al + 3 O  → 2 Al  O
      .row.justify-content-center(titulo="Reacciones de descomposición")
        .col-md-11.mb-4.mb-md-0
          p.mb-0 Son reacciones químicas en las que un compuesto se descompone en dos o más sustancias más simples. Son las inversas de las reacciones de síntesis.
          p La ecuación química general es:
          p.mb-2 AB → A + B
          h5.mb-0 Ejemplos:
          p.mb-1 2 AlCl  → 2 Al + 3 Cl 
          p 2 KClO  → 2 KCl + 3 O 
      .row.justify-content-center(titulo="Reacciones de sustitución o desplazamiento")
        .col-md-11.mb-4.mb-md-0
          p.mb-0 Las reacciones de sustitución o desplazamiento pueden ser simples o dobles.

          p En una reacción de sustitución o desplazamiento simple, un elemento es reemplazado por otro elemento más reactivo en un compuesto para producir un nuevo compuesto y el elemento desplazado.

          p.mb-2 AB → A + B
          h5.mb-0 Ejemplos:
          p.mb-1 2 AlCl  → 2 Al + 3 Cl 
          p 2 KClO  → 2 KCl + 3 O 
      .row.justify-content-center(titulo="Reacciones de sustitución o desplazamiento")
        .col-md-11.mb-4.mb-md-0
          p.mb-0 Las reacciones de sustitución o desplazamiento pueden ser simples o dobles. En una reacción de sustitución o desplazamiento simple, un elemento es reemplazado por otro elemento más reactivo en un compuesto para producir un nuevo compuesto y el elemento desplazado.
          p.mb-0 La ecuación química general es:
          p.mb-0 A + BC → AC + B
          h5.mb-0 Ejemplos:
          p.mb-1 Fe  O  + 2 Al → Al  O  + 2 Fe

          p 2 Na + 2 H  O → 2 NaOH + H
          p.mb-0 En una reacción de doble sustitución o desplazamiento, hay dos compuestos químicos que intercambian dos elementos para formar dos nuevos compuestos.
          p La ecuación química general es:
          p AB + CD → AD + CB 
          h5.mb-0 Ejemplos:
          p.mb-0 LiH + H  O → LiOH + H  ↑ (H  , gas)
          p HCl + NaOH → NaCl + H  O (H  O, agua)
    p.mt-3 Por otro lado, es indispensable revisar los conceptos relacionados con las reacciones según la partícula transferida, los cuales se desarrollan a continuación:
    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
      .row.justify-content-center(titulo="Reacciones de precipitación")
        .col-md-11.mb-4.mb-md-0
          p En una reacción de precipitación, la partícula intercambiada es un ión. Se produce, en general, en disolución acuosa y entre sustancias iónicas. En la reacción, un anión y un catión se ponen en contacto y dan lugar a un compuesto iónico insoluble que precipita.
          h5 Ejemplos:
          p AgNO  (aq) + NaCl (aq) → NaNO  (aq) + ↓AgCl (s)
          p Para saber si se produce una reacción de este tipo, es necesario saber qué sustancia es insoluble y por esto se ponen en la ecuación química los estados físicos de las sustancias que intervienen.
      .row.justify-content-center(titulo="Reacciones de oxidación-reducción")
        .col-md-11.mb-4.mb-md-0
          p Las reacciones de oxidación-reducción (redox) implican la transferencia de electrones entre especies químicas. Se llaman también reacciones de transferencia de electrones, ya que la partícula que se intercambia es el electrón.
          p En una reacción de oxidación-reducción, tienen lugar dos procesos simultáneos: la oxidación y la reducción.
          p El aluminio reacciona con el oxígeno para formar óxido de aluminio, 4 Al + 3 O  → 2 Al  O 
          p En el transcurso de esta reacción, cada átomo de aluminio pierde tres electrones, para formar un ion Al 3+  
          p Al → Al 3+ + 3 e -
          p Y cada molécula de O 2 gana cuatro electrones, para formar dos iones O 2 -
          p O 2 + 4 e - → 2 O 2-
          p Como los electrones ni se crean ni se destruyen en las reacciones químicas, la oxidación y la reducción son inseparables.
          p El aluminio cede electrones y el oxígeno los gana. El aluminio actúa como agente reductor, se oxida (su número de oxidación pasa de 0 a +3) cediendo tres electrones, mientras que el oxígeno actúa como agente oxidante, se reduce (su número de oxidación pasa de 0 a -2) ganando dos electrones.
    .row.justify-content-center.mt-4
      .col-lg-10
        .tarjeta.color-primario.p-3.mb-5.mt-4
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema2/i1.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h5 Para profundizar en el tema, se invita a revisar la página web de la Junta de Andalucía (s. f.), donde se mencionan los tipos de reacciones químicas, la cual está ubicada en la sección de referencias. 
    .row
      .col-lg-5
        .row
          .col-lg-9
            .row.p-1.colorazul
              h4.text-white.mb-0 Reacciones químicas de interés ambiental.
        p.mt-2  Uno de los problemas fundamentales en el presente siglo, que debe ser estudiado por el ciudadano global y que menciona Naciones Unidas, es el ¨cambio climático y sus consecuencias para la sostenibilidad del planeta y la existencia de la raza humana¨ (Naciones Unidas, s. f.). Por lo anterior, se invita a seguir revisando el contenido del documento con el fin de conocer cuáles son las reacciones químicas que afectan directamente el medio ambiente.
      .col-lg-7
        img(src="@/assets/curso/tema3/17.png")
    AcordionA.mt-4(tipo="b" clase-tarjeta="tarjeta tarjeta--azul")
      .row.justify-content-center(titulo="Reacciones con el oxígeno ")
        .col-md-11.mb-4.mb-md-0
          p El oxígeno es el elemento químico más abundante en la corteza terrestre. Muchos elementos reaccionan con el oxígeno dando lugar a una reacción de oxidación. Un caso particular de la reacción de oxidación es la denominada reacción de combustión.
      .row.justify-content-center(titulo="Reacciones de oxidación ")
        .col-md-11.mb-4.mb-md-0
          p En las reacciones de oxidación, el oxígeno se une al elemento de forma lenta y sin gran desprendimiento de energía, y se forma un compuesto llamado óxido:
          p elemento + oxígeno (O2) → óxido
          p La reacción contraria, en la que el óxido se descompone, produce el metal y libera oxígeno, también existe y se llama reacción de reducción: 
          p calor óxido → metal + oxígeno
          p La formación de óxidos no siempre es ventajosa, ya que a veces la oxidación de algunos no metales, como el carbono y el azufre, puede crear problemas medioambientales. El CO  desprendido contribuye a aumentar el efecto invernadero, y el SO  formado por la oxidación del azufre favorece la denominada lluvia ácida. 
          p Asimismo, la oxidación de metales, como el hierro, produce grandes perjuicios económicos. El hierro es uno de los metales que más se utiliza en la industria y en la construcción, pero en presencia de oxígeno y humedad se oxida rápidamente y se corroe. Para evitarlo, se recubre de una capa de pintura y de una capa de otro metal que no se oxide, por ejemplo, de cromo, lo que se denomina cromado.
      .row.justify-content-center(titulo="Reacciones de combustión")
        .col-md-11.mb-4.mb-md-0
          p Las reacciones de combustión son reacciones de oxidación en las que una sustancia arde uniéndose al oxígeno y produce otras sustancias diferentes. La sustancia que arde se denomina combustible y la sustancia que mantiene la combustión se llama comburente. 
          p Uno de los usos más frecuentes de las reacciones de combustión es la producción de energía. En la actualidad, los combustibles más utilizados son los hidrocarburos (compuestos derivados del petróleo formados por carbono e hidrógeno) que, en presencia de oxígeno, producen dióxido de carbono, agua y energía. Así, por ejemplo, la reacción de combustión del metano (CH4) es:
          p CH4 (g) + 2 O2 (g) → CO2 (g) + 2H2O (g) + energía 
          p El CO2 desprendido crea problemas medioambientales y contribuye a aumentar el efecto invernadero. Por este motivo, las investigaciones se encaminan a la fabricación de vehículos no contaminantes, como los coches eléctricos.
      .row.justify-content-center(titulo="Reacciones de combustión en el reino animal")
        .col-md-11.mb-4.mb-md-0
          p Metabolismo. El metabolismo es el conjunto de cambios físicos y químicos que se originan en los seres vivos y que sirven, por un lado, para mantener sus funciones vitales (anabolismo) y, por otro, para generar la energía que necesitan (catabolismo). Así, los alimentos ingeridos, ricos en hidratos de carbono, se descomponen, entre otros compuestos, en glucosa (C6H12O6) que pasa desde el intestino a la sangre y de esta a las células donde se producen las reacciones de combustión: 
          p C6H12O6 + 6 O2 → 6 CO2 + 6 H2O + energía
      .row.justify-content-center(titulo="Combustión incompleta")
        .col-md-11.mb-4.mb-md-0
          p.mb-0 El combustible no se oxida completamente. Se forman sustancias que todavía pueden seguir oxidándose; por ejemplo, CO. Estas sustancias se denominan inquemados. La presencia de inquemados indica que la combustión se está realizando en forma incompleta. Otros inquemados pueden ser H2, CnHm,
          p H2S y C. Estas sustancias son los contaminantes más comunes que escapan a la atmósfera en los gases de combustión.
    separador
    #t_3_3.titulo-segundo.color-acento-contenido
      h2 3.3 Procesos de combustión 
    .row
      .col-lg-6
        p La combustión no es más que una reacción química de oxidación, en la que normalmente se va a liberar una gran cantidad de calor (energía). La reacción de un elemento químico con el oxígeno se llama oxidación. Para entender este tema, se hace necesario adquirir los siguientes conceptos:
        ul.lista-ul--color
          li.mb-0
            i.fas.fa-check
            | Cuando el calor de reacción es negativo, dicho calor es liberado o entregado por el sistema, y el proceso se llama exotérmico. 
          li.mb-0
            i.fas.fa-check
            | Si, en cambio, el calor es positivo, el calor debe ser absorbido por el sistema durante la reacción química y el proceso se denomina endotérmico. 
          li.mb-0
            i.fas.fa-check
            | Combustible: toda sustancia (hidrocarburo) capaz de arder. 
          li.mb-0
            i.fas.fa-check
            | Comburente: sustancia (aire) que aporta el oxígeno para que el combustible sufra oxidación.
        p.mt-2 En una reacción de oxidación, se tiene la siguiente ecuación: 
        .cajon.color-acento-contenido.p-4.mb-4
          h5.text-center Combustible + Comburente = Gases de combustión + Energía
      .col-lg-6
        img(src="@/assets/curso/tema3/18.png")
    p.mt-3 Entonces, la ecuación también podría tomar la siguiente forma, donde las letras mayúsculas indican las sustancias químicas y las minúsculas indican la cantidad de moles de dichas sustancias. Y se denominan genéricamente reactantes a las sustancias escritas antes del signo igual (A y B) y productos a las escritas después del signo igual (C y D).
    p Se puede dar el caso de que el combustible esté formado por una mezcla de sustancias entre las cuales hay una o más que no reaccionan con el O2, por ejemplo, SO2. En este caso, estas sustancias también pasarán en forma completa a los humos (productos). 
    separador
    #t_3_4.titulo-segundo.color-acento-contenido
      h2 3.4 Combustibles    
    p Los combustibles normalmente son una combinación de carbono, hidrógeno y azufre, tal como se puede ver en la siguiente tabla:
    .row.justify-content-center.mt-4
      .col-lg-10
        .titulo-sexto.color-secundario
          h5 Tabla 6
          span Tipos de combustibles  
        img(src="@/assets/curso/tema3/19.svg")
    .row.mt-4
      .col-lg-2
        .row.p-1.colorazul
          h4.text-white.mt-1 Comburente (aire)
    .row.mt-3
      .col-lg-6
        p Sustancia gaseosa, transparente, inodora e insípida que envuelve la tierra y forma la atmósfera; está constituida principalmente por oxígeno y nitrógeno, y por cantidades variables de argón, vapor de agua y anhídrido carbónico. Para casi todos los cálculos de combustión, es posible tratar al argón y al dióxido de carbono como nitrógeno adicional, ya que son inertes y aparecen en pequeñas cantidades. Puede revisar la composición en la siguiente tabla: 

      .col-lg-6
        img(src="@/assets/curso/tema3/20.png")
    .row.justify-content-center.mt-4
      .col-lg-8
        .titulo-sexto.color-secundario
          h5 Tabla 7
          span Composición del comburente (aire)
        img(src="@/assets/curso/tema3/21.svg")    
        p Utilizando esta suposición, un mol de aire se compone de 0.79 moles de N2 y 0.21 moles de O2. 
        p 0.21mol O2 + 0.79mol N2 = 1mol aire
        p Por lo tanto, el N2 pasará íntegramente a los humos.
    .row.mt-4
      .col-lg-2
        .row.p-1.colorazul
          h4.text-white.mb-0 Tipos de combustión  
    p.mt-3 Los procesos de combustión se pueden clasificar en: 
    AcordionA.mt-4(tipo="b" clase-tarjeta="tarjeta tarjeta--azul")
      .row.justify-content-center(titulo="Combustión completa")
        .col-md-11.mb-4.mb-md-0
          p Las sustancias del combustible se queman hasta el máximo grado posible de oxidación. En consecuencia, no habrá sustancias combustibles en los humos (productos). 
          p En los productos de la combustión completa, se pueden encontrar los siguientes reactantes y sus correspondientes productos:
        .col-lg-7
          .titulo-sexto.color-secundario
            h5 Tabla 8
            span Productos de la combustión
          img(src="@/assets/curso/tema3/22.png")
        .col-md-11.mb-4.mb-md-0
          p.mt-2 El balance de materia de las reacciones químicas se denomina estequiometría. Siempre se plantea en moles, y la sumatoria de masas de ambos miembros siempre deberá ser igual, tal como se muestra en el siguiente ejemplo:
    .row.justify-content-center.mt-4
      .col-lg-10
        .tarjeta.color-primario.p-3.mb-5.mt-4
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema2/i1.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h5 Para desarrollar su aprendizaje autónomo, se invita a revisar la página web Naturaleza de las reacciones químicas (Peña y Bautista, 2018), con el fin de profundizar en el tema tratado anteriormente. La información la puede encontrar en la sección de referencias.
    separador
    #t_3_5.titulo-segundo.color-acento-contenido
      h2 3.5 Balanceo de ecuaciones químicas                  
    p Balancear una ecuación es realmente un procedimiento de ensayo y error, que se fundamenta en la búsqueda de diferentes coeficientes numéricos que hagan que el número de cada tipo de átomos presentes en la reacción química sea el mismo tanto en reactivos como en productos.
    .row
      .col-lg-3
        .row.p-1.colorazul
          h4.text-white.mb-0 Método del tanteo o inspección
    .row.mt-4
      .col-lg-6
        p Este método es utilizado para ecuaciones sencillas y consiste en colocar coeficientes a la izquierda de cada sustancia, hasta tener igual número de átomos tanto en reactantes como en productos. Observe el siguiente ejemplo:
        h4 N      +     H 	→    NH
        p Para balancearlos hay que colocar un coeficiente 3 al H   y un coeficiente 2 al producto NH  :
        h4 N      +    3H 	→    NH
        p La ecuación ha quedado equilibrada, el número de átomos de cada elemento es el mismo en reactivos y productos.
      .col-lg-6
        img(src="@/assets/curso/tema3/23.png")
    .row.mt-3
      .col-lg-3
        .row.p-1.colorazul
          h4.text-white.mb-0 Método de óxido reducción
    p.mt-3 Las reacciones de oxidación-reducción (redox) implican la transferencia de electrones entre especies químicas. Se llaman también reacciones de transferencia de electrones, ya que la partícula que se intercambia es el electrón.
    p En una reacción de oxidación-reducción, tienen lugar dos procesos simultáneos: la oxidación y la reducción. Para balancear una ecuación por oxidación-reducción, hay que tener presente lo registrado a continuación:
    .row.mt-4
      .col-lg-6
        .row.p-3.colort3
          h5.text-center OXIDACIÓN
          p.text-center La oxidación es el proceso en el cual una especie química pierde electrones y su número de oxidación aumenta.
      
      .col-lg-6    
        .row.p-3.colort32
          h5.text-center REDUCCIÓN
          p.text-center La reducción es el proceso en el cual una especie química gana electrones y su número de oxidación disminuye.
    p.mt-4 Como los procesos de óxido-reducción son de intercambio de electrones, las ecuaciones químicas estarán igualadas cuando el número de electrones cedidos por el agente oxidante sea igual al recibido por el agente reductor. El número de electrones intercambiados se calcula fácilmente, teniendo en cuenta la variación de los números de oxidación de los elementos. Revise los siguientes pasos:
    .row.justify-content-center
      .col-lg-10
        .tarjeta.color-primario.p-3.mb-5.mt-4
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema1/pdf.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h5 Para profundizar en su aprendizaje, se invita a revisar el contenido El Mundo de la Ciencia (s. f.), el cual se encuentra ubicado en la sección de referencias.
                .col-sm-auto
                  a.boton.color-acento-botones.texto-blanco(:href="('https://sites.google.com/site/elmundodelacienciaensm/reacciones-redox')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download        
    separador
    #t_3_6.titulo-segundo.color-acento-contenido
      h2 3.6 Estequiometría   
    p La estequiometría es la parte de la química que estudia las relaciones cuantitativas entre las sustancias que intervienen en una reacción química (reactivos y productos).
    .row.justify-content-center.mt-3
      .col-lg-10
        .row.justify-content-center.align-items-center
          .col-lg-5
            .titulo-sexto.color-secundario
              h5 Figura 15
              span Reacciones químicas
            img(src="@/assets/curso/tema3/24.png")
          .col-lg-7
            p <strong>Las relaciones pueden ser: entre reactivos y productos</strong>, solo entre reactivos, o solo entre productos. Cualquier cálculo estequiométrico que se lleve a cabo debe hacerse con base en una ecuación química balanceada, para asegurar que el resultado sea correcto.
    .row.mt-3
      .col-lg-3
        .row.p-1.colorazul
          h4.text-white.mb-0 Cálculos estequiométricos
    p.mt-3 La estequiometría se emplea para determinar las cantidades de reactivos y productos involucrados en una reacción química. Existe una gran cantidad de problemas relacionados con esta, como se evidencia en el siguiente ejemplo:
    .row.p-3.bgt34.justify-content-center
      p "En los vehículos espaciales se utiliza hidróxido de litio sólido para eliminar el dióxido de carbono exhalado. El hidróxido de litio reacciona con el dióxido de carbono gaseoso, formando carbonato de sodio sólido y agua líquida. ¿Cuántos gramos de dióxido de carbono puede absorber 1 g de hidróxido de litio?
      .col-lg-10
        h5 SOLUCIÓN
        p <strong>Análisis:</strong> se da una descripción verbal de una reacción y se pide calcular el número de gramos de dióxido de carbono que reaccionan con 1.00 g de hidróxido de litio.
        p <strong>Estrategia:</strong> se puede usar la descripción verbal de la reacción para escribir una ecuación balanceada:
        p 2LiOH(s) + CO2 (g)          Li2CO3(s) + H2O(l)
        p Se dan los gramos de LiOH y se pide calcular los gramos de CO2. Esto puede lograrse mediante la siguiente serie de conversiones: gramos de LiOH moles de LiOH moles de CO2 gramos de CO2. La conversión de gramos de LiOH a moles de LiOH requiere el peso formular de esta sustancia (6.94 +16.00 + 1.01 =23.95). 
        p La conversión de moles de LiOH a moles de CO2 se basa en la ecuación química balanceada: 2 mol LiOH 1 mol CO2. 
        p Para convertir el número de moles de CO2 a gramos, se deberá usar el peso formular del CO2:  12.01 +2(16.00) = 44.01.
        h5 RESOLUCIÓN:
        p Comprobación: vemos que 23.95 ≈ 24; 24 _ 2 _ 48 y 44/48 es un poco menor que 1. Por tanto, la magnitud de la respuesta es razonable con base en la cantidad inicial de LiOH; las cifras significativas y las unidades también son apropiadas."
    .row.justify-content-center.mt-4
      .col-lg-10
        .tarjeta.color-primario.p-3.mb-5.mt-4
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema2/i1.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h5 Como parte de su aprendizaje autónomo, se invita a revisar la siguiente página web Profe Cerebrito (2013a), en la cual puede encontrar más información sobre la información cuantitativa en una ecuación. Se recomienda ir a la sección de referencias para ubicar allí el enlace. 
    .row.mt-3
      .col-lg-6
        .row.p-1.colorazul
          h4.text-white.mb-0 Cálculos de reactivo limitante y porcentaje de rendimiento.      
    .row.mt-4
      .col-lg-6
        p En una reacción química, no necesariamente se consume la totalidad de los reactivos. Generalmente, alguno de ellos se encuentra en exceso. El otro reactivo, que es el que se consume totalmente, se conoce como reactivo limitante. Para que una reacción se lleve a cabo, debe haber sustancias (reactivos) capaces de reaccionar para formar los productos, pero basta que uno solo de los reactivos se agote para que la reacción termine. En los procesos industriales, generalmente, se usa un exceso del reactivo más barato y fácil de conseguir, y se selecciona como limitante el más caro o difícil de conseguir. Ejemplo
      .col-lg-6 
        img(src="@/assets/curso/tema3/25.png")
    .row.p-3.bgt34.justify-content-center
      p Considere la reacción siguiente:
      .col-lg-10
        p Suponga que una disolución que contiene 3.50 g de Na3PO4, se mezcla con una disolución que contiene 6.40 g de Ba (NO3)2. ¿Cuántos gramos de Ba2(PO4)2 podrán formarse?
        h5 SOLUCIÓN
        p Análisis: se da una reacción química y las cantidades de dos reactivos [3.50 g de Na3PO4 y 6.40 g de Ba (NO3)2]. Se pide calcular el número de gramos de Ba3(PO4)2 (uno de los productos).
        p Estrategia: Se pide calcular la cantidad de producto dadas las cantidades de dos reactivos, así que se trata de un problema de reactivo limitante. Por tanto, primero se debe identificar el reactivo limitante. Para hacerlo, es preciso calcular el número de moles de cada reactivo y comparar su proporción con la que requiere la ecuación balanceada. Luego, se usa la cantidad del reactivo limitante para calcular la masa de Ba3(PO4)2 que se forma.
        h5 RESOLUCIÓN:
        p Se pide calcular la cantidad de producto dadas las cantidades de dos reactivos, así que se trata de un problema de reactivo limitante. Por tanto, primero se debe identificar el reactivo limitante. Para hacerlo, es preciso calcular el número de moles de cada reactivo y comparar su proporción con la que requiere la ecuación balanceada. Luego, se usa la cantidad del reactivo limitante para calcular la masa de Ba3(PO4)2 que se forma.
        p 2 mol Na3PO4 = 3 mol Ba (NO3)2 =1 mol Ba3(PO4)2
        p Utilizando la masa molar de cada sustancia, se puede calcular el número de moles de cada reactivo:
        p Estos cálculos muestran que el número de moles de Ba(NO3)2 es un poco mayor que el de Na3PO4. Sin embargo, los coeficientes de la ecuación balanceada indican que la reacción requiere 3 mol Ba(NO3)2 por cada 2 mol Na3PO4. [Es decir, se requieren 1.5 veces más moles de Ba (NO3)2 que de Na3PO4.]. Es decir, no hay suficiente Ba(NO3)2 para consumir totalmente el Na3PO4. Esto implica que el Ba(NO3)2 es el reactivo limitante. Por tanto, se usa la cantidad de Ba(NO3)2 para calcular la cantidad de producto que se forma. Se podría iniciar el cálculo con los gramos de Ba(NO3)2, pero es posible ahorrarse un paso si se parte de los moles de Ba(NO3)2 que se calcularon previamente en él.
        h5 Ejercicio: 
        h5 COMPROBACIÓN
        p La magnitud de la respuesta parece razonable: partiendo de los números en los dos factores de la derecha, se tiene: 
        p 600/3 = 200; 200 X 0.025 =5. 
        p Las unidades son correctas y el número de cifras significativas (3) corresponde a las que tiene la cantidad de Ba(NO3)2.
        h5 Comentario: 
        p.mb-0 También es posible usar la cantidad del reactivo limitante, Ba(NO3)2, para determinar la cantidad de NaNO3 que se forma (4.16 g) y la cantidad de Na3PO4 consumida (2.67 g).
        p El número de gramos del reactivo en exceso, Na3PO4, que quedan al término de la reacción es igual a la cantidad inicial menos la cantidad consumida en la reacción:
        p 3.50 g - 2.67 g = 0.82 g NaNO3
    .row.justify-content-center.mt-4
      .col-lg-10
        .tarjeta.color-primario.p-3.mb-5.mt-4
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema2/i1.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h5 Para desarrollar su aprendizaje autónomo, se invita a revisar la siguiente página web Profe Cerebrito (2013b), donde encontrará información sobre los reactivos, limitantes y teoría. Para acceder a la información, puede ir a la sección de referencias.
    .row.mt-3
      .col-lg-3
        .row.p-1.colorazul
          h4.text-white.mb-0 Rendimientos teóricos.
    .row.mt-4
      .col-lg-6
        .cajon.color-acento-contenido.p-4.mb-4
          p La cantidad de producto que, según los cálculos, se forma cuando reacciona todo el reactivo limitante se llama rendimiento teórico. La cantidad de producto que realmente se obtiene en una reacción se denomina rendimiento real. El rendimiento real casi siempre es menor (y nunca puede ser mayor) que el rendimiento teórico.
        p Esta diferencia tiene muy diversas causas. Por ejemplo, es posible que una parte de los reactivos no reaccione, o que reaccione de una forma diferente de la deseada (reacciones secundarias). Además, no siempre es posible recuperar todo el producto de reacción de la mezcla de reacción. El porcentaje de rendimiento de una reacción relaciona el rendimiento real con el teórico (calculado):
      .col-lg-6
        img(src="@/assets/curso/tema3/26.png")
    .row.mt-4.justify-content-center
      .col-lg-4
        .row.p-3.asc
          h5.text-center % Rendimiento= Rendimiento       Real     x 100% Rendimiento teórico
    .row.mt-4
      .col-lg-6
        img(src="@/assets/curso/tema3/27.png")

      .col-lg-6
        p El ácido adípico, H2C6H8O4, es un material empleado en la producción de nailon; se fabrica comercialmente por una reacción controlada entre ciclohexano (C   H   ) y O   :
        p Suponga que efectúa esta reacción partiendo de 25.0 g de ciclohexano, y que este es el reactivo limitante. Calcule el rendimiento teórico de ácido adípico.
        p Si obtiene 33.5 g de ácido adípico en la reacción, calcule el porcentaje de rendimiento de ácido adípico.
    .row.justify-content-center.mt-4
      .col-lg-10
        .tarjeta.color-primario.p-3.mb-5.mt-4
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema2/i1.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h5.mb-0 Para reforzar su aprendizaje, se invita a revisar los siguientes documentos, los cuales puede encontrar en la sección de referencias.
                  p.mb-0 Reactivos, limitantes, teoría y ejercicios resueltos, el cual puede encontrar en la página web Profe Cerebrito (2013b). 
                  p Química. La ciencia central, de los autores Brown, LeMay, Bursten y Burdge (2004, p 95-102).
    p.mt-4 Para redondear con dos decimales, se usa como base el tercer decimal. Si este es mayor o igual a 5, se aumenta una unidad al segundo decimal; si es menor o igual a 4 se conservará la cifra del segundo decimal.
    p A continuación, se ampliarán temas normativos que son importantes para comprender los conceptos vistos y su importancia.




  
</template>

<script>
export default {
  name: 'Tema3',
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
