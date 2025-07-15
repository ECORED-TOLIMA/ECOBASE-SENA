<template lang="pug">
  div.mb-5 
        
    .titulo-segundo.color-acento-botones(data-aos="fade-right")
      h2 Encabezados
    
    h3.mb-5 #[i.fas.fa-angle-double-right.txt--green] Estilo de título para el índice de contenidos:

    .row.justify-content-center.mb-4
      .col-11
        .titulo-principal.color-acento-botones(data-aos="fade-right")
          .titulo-principal__numero
            span 1
          h1 Título principal, 30pt        

        .titulo-segundo.color-primario(data-aos="fade-right")
          h2 1.1  Título de segundo nivel, 24pt

        h3.titulo-tercero Título de tercer nivel, 20pt 

    Separador
    .titulo-segundo.color-acento-botones(data-aos="fade-right")
      h2 Párrafos

    p.mb-0 Los párrafos mantienen un tamaño regular de 16 pt con interlineado base de 24 pt, sin embargo, existe excepciones para resaltar contenido donde se puede hacer uso de pesos 
      | #[span.text-thin THIN], 
      | #[strong BOLD], y #[span.text-black BLACK] 
      | o #[mark etiquetas] de color (según paleta del programa). Así mismo, el ancho de los cajones textos permite variación en las doce (12) columnas.

    Separador
    .titulo-segundo.color-acento-botones(data-aos="fade-right")
      h2 Operaciones matematicas

    .row.justify-content-center.mb-4
      .col-lg-4.mb-lg-0.mb-4(data-aos="fade-right")
        .h5 Fracionarios
        .fraccionario
          span.num Numerador
          span.div /
          span.den Denominador
      .col-lg-4.mb-lg-0.mb-4(data-aos="flip-up")
        .h5 Radicales
        .radical
          span.potencia 3 
          span &radic;
          span.radicand 8
      .col-lg-4.mb-lg-0.mb-4(data-aos="fade-left")
        .h5 Potencias
        p x #[sup 3]

    Separador
    .titulo-segundo.color-acento-botones(data-aos="fade-right")
      h2 Listados
    
    p.mb-5 Se debe tener en cuenta que las personas realizan un escaneo del mismo para encontrar elementos de su interés. Las listas deben estar compuestas por elementos relacionados entre sí, con un orden específico o un conteo importante.

    .row.mb-5
      .col-lg.mb-lg-0.mb-4
        h4 Listado ordenado básico
        ol.lista-ol
          li(data-aos="fade-right") 
            span.text-bold 1. 
            | Item lista ordenada 1
          li(data-aos="fade-right") 
            span.text-bold 2. 
            | Item lista ordenada 2
          li(data-aos="fade-right") 
            span.text-bold a. 
            | Item lista ordenada a
          li(data-aos="fade-right") 
            span.text-bold b. 
            | Item lista ordenada b 
      .col-lg.mb-lg-0.mb-4
        h4 Listado ordenado cuadro color
        ol.lista-ol--cuadro
          li(data-aos="flip-up") 
            .lista-ol--cuadro__vineta
              span 1
            | Item lista ordenada 1
          li(data-aos="flip-right") 
            .lista-ol--cuadro__vineta
              span 2
            | Item lista ordenada 2
          li(data-aos="flip-right") 
            .lista-ol--cuadro__vineta
              span a
            | Item lista ordenada a
          li(data-aos="flip-right") 
            .lista-ol--cuadro__vineta
              span b
            | Item lista ordenada b
      .col-lg.mb-lg-0.mb-4
        h4 Listado ordenado cuadro color + separadores
        ol.lista-ol--cuadro.lista-ol--separador
          li(data-aos="fade-left") 
            .lista-ol--cuadro__vineta
              span 1
            | Item lista ordenada 1
          li(data-aos="fade-left") 
            .lista-ol--cuadro__vineta
              span 2
            | Item lista ordenada 3
          li(data-aos="fade-left") 
            .lista-ol--cuadro__vineta
              span a
            | Item lista ordenada a
          li(data-aos="fade-left") 
            .lista-ol--cuadro__vineta
              span b
            | Item lista ordenada b

    .row
      .col-lg.mb-lg-0.mb-4
        h4 Listado no ordenado básico
        ul.lista-ul
          li(data-aos="fade-right") 
            i.lista-ul__vineta
            | Item lista no ordenada
          li(data-aos="fade-right")
            ul
              li(data-aos="fade-right") 
                i.lista-ul__vineta
                | Item lista no ordenada
              li(data-aos="fade-right") 
                i.lista-ul__vineta
                | Item lista no ordenada
          li(data-aos="fade-right") 
            i.lista-ul__vineta
            | Item lista no ordenada
          li(data-aos="fade-right") 
            i.lista-ul__vineta
            | Item lista no ordenada 
      .col-lg.mb-lg-0.mb-4
        h4 Listado no ordenado color
        ul.lista-ul--color
          li(data-aos="flip-up") 
            i.fas.fa-brain.txt--green
            | Item lista no ordenada
          li(data-aos="flip-up")
            ul
              li(data-aos="flip-up") 
                i.fas.fa-bug.txt--green
                | Item lista no ordenada
              li(data-aos="flip-up") 
                i.fas.fa-car-side.txt--green
                | Item lista no ordenada
          li(data-aos="flip-up") 
            i.fas.fa-compass.txt--green
            | Item lista no ordenada
          li(data-aos="flip-up") 
            i.fas.fa-eye.txt--green
            | Item lista no ordenada 
      .col-lg.mb-lg-0.mb-4
        h4 Listado no ordenado color + separadores
        ul.lista-ul--color.lista-ul--separador
          li(data-aos="fade-left") 
            i.fas.fa-feather.txt--green
            | Item lista no ordenada
          li(data-aos="fade-left").pb-0
            ul
              li(data-aos="fade-left") 
                i.fas.fa-cookie.txt--green
                | Item lista no ordenada
              li(data-aos="fade-left") 
                i.fas.fa-hat-wizard.txt--green
                | Item lista no ordenada
          li(data-aos="fade-left") 
            i.fas.fa-hippo.txt--green
            | Item lista no ordenada
          li(data-aos="fade-left") 
            i.fas.fa-kiwi-bird.txt--green
            | Item lista no ordenada

    Separador
    .titulo-segundo.color-acento-botones(data-aos="fade-right")
      h2 Tablas

    .titulo-sexto.color-secundario(data-aos="fade-right")
      h5 Tabla_A.
      i Titulo_tabla
    .tabla-a.color-acento-botones.mb-5 
      table(data-aos="zoom-in" alt="Texto_alternativo_tabla")
        caption Nota. <span style="font-weight: 400">Tomado_referencia.</span>
        thead
          tr(data-aos="fade-right")
            th Encabezado_1
            th Encabezado_2
            th Encabezado_3
            th Encabezado_4
            th Encabezado_5
        tbody
          tr(data-aos="fade-right")
            td Celda_1
            td Celda_2
            td Celda_3
            td Celda_4
            td Celda_5
          tr(data-aos="fade-right")
            td Celda_1
            td Celda_2
            td Celda_3
            td Celda_4
            td Celda_5
          tr(data-aos="fade-right")
            td Celda_1
            td Celda_2
            td Celda_3
            td Celda_4
            td Celda_5

    .titulo-sexto.color-secundario(data-aos="fade-right")
      h5 Tabla_B.
      i Titulo_tabla
    .tabla-b.color-acento-contenido.mb-5
      .tabla-b__header
        h4.mb-0 Titulo_header
      table(data-aos="zoom-in" alt="Texto_alternativo_tabla")
        caption Nota. <span style="font-weight: 400">Tomado_referencia.</span>
        tr(data-aos="fade-right")
          th Celda_titulo_1
          td Celda_Contexto_2
        tr(data-aos="fade-right")
          th Celda_titulo_1
          td Celda_Contexto_2
        tr(data-aos="fade-right")
          th Celda_titulo_1
          td Celda_Contexto_2
        tr(data-aos="fade-right")
          th Celda_titulo_1
          td Celda_Contexto_2
        tr(data-aos="fade-right")
          th Celda_titulo_1
          td Celda_Contexto_2

    .titulo-sexto.color-secundario(data-aos="fade-right")
      h5 Tabla_C.
      i Titulo_tabla
    .tabla-c.mb-5
      table(data-aos="zoom-in" alt="Texto_alternativo_tabla")
        caption Nota. <span style="font-weight: 400">Tomado_referencia.</span>
        thead
          tr(data-aos="fade-right")
            th Encabezado_1
            th Encabezado_2
            th Encabezado_3
            th Encabezado_4
            th Encabezado_5
        tbody 
          tr(data-aos="fade-right")
            th Celda_1
            td 
              p.text-small Textos_pequeños_Celda_2
            td
              .h6.mb-0 $12.500.200
            td
              .h6.mb-0 $12.500.200
              span.text-small Textos_pequeños
            td
              .h6 FDSD33
          tr(data-aos="fade-right")
            th Celda_1
            td(data-aos="fade-right") 
              p.text-small Textos_pequeños_Celda_2
            td(data-aos="fade-right")
              .h6.mb-0 $12.500.200
            td(data-aos="fade-right")
              .h6.mb-0 $12.500.200
              span.text-small Textos_pequeños
            td(data-aos="fade-right")
              .h6 FDSD33
          tr(data-aos="fade-right")
            th Celda_1
            td(data-aos="fade-right") 
              p.text-small Textos_pequeños_Celda_2
            td(data-aos="fade-right")
              .h6.mb-0 $12.500.200
            td(data-aos="fade-right")
              .h6.mb-0 $12.500.200
              span.text-small Textos_pequeños
            td(data-aos="fade-right")
              .h6 FDSD33
          tr(data-aos="fade-right")
            th Celda_1
            td(data-aos="fade-right") 
              p.text-small Textos_pequeños_Celda_2
            td(data-aos="fade-right")
              .h6.mb-0 $12.500.200
            td(data-aos="fade-right")
              .h6.mb-0 $12.500.200
              span.text-small Textos_pequeños
            td(data-aos="fade-right")
              .h6 FDSD33
          tr(data-aos="fade-right")
            th Celda_1
            td(data-aos="fade-right") 
              p.text-small Textos_pequeños_Celda_2
            td(data-aos="fade-right")
              .h6.mb-0 $12.500.200
            td(data-aos="fade-right")
              .h6.mb-0 $12.500.200
              span.text-small Textos_pequeños
            td(data-aos="fade-right")
              .h6 FDSD33

    Separador
    .titulo-segundo.color-acento-botones(data-aos="fade-right")
      h2 Imagenes

    .row.justify-content-center.mb-5
      .col-lg-10
        .titulo-sexto.color-acento-contenido(data-aos="fade-right")
          h5 Figura 1.
          i Nombre_figura
        figure(data-aos="zoom-in")
          img(src='@/assets/template/img-placeholder.svg' alt="Imagen decorativa")
          figcaption Nota. <span style="font-weight: 400">Tomado referencia.</span>

    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h3 Imagen Infográfica A
    //- Advertencia, tener encuenta que si la imagen tiene titulo, en la tarjeta no iria titulación
    ImagenInfografica.color-secundario.mb-5(data-aos="zoom-in")
      template(v-slot:imagen)
        figure
          img(src='@/assets/template/img-placeholder.svg', alt="Imagen decorativa")
          figcaption Leyenda_de_la_imagen
      .tarjeta.color-acento-botones.p-3(x="20%" y="20%" numero="1")
        .h5.mb-2 titulo
        p.mb-0 Texto_infografia_a
      .tarjeta.color-acento-botones.p-3(x="50%" y="50%" numero="A")
        .h5.mb-2 titulo
        p.mb-0 Texto_infografia_a
      .tarjeta.color-acento-botones.p-3(x="70%" y="70%" numero="B")
        .h5.mb-2 titulo
        p.mb-0 Texto_infografia_a

    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h3 Imagen Infográfica B
    //- Advertencia, tener encuenta que si la imagen tiene titulo, en la tarjeta no iria titulación
    ImagenInfograficaB.color-primario.mb-5
      template(v-slot:imagen)
        figure
          img(src='@/assets/template/img-placeholder.svg', alt="Imagen decorativa")
          figcaption Leyenda_de_la_imagen
      div(x="20%" y="20%" tooltip="tooltip_de_max_35_caracteres" numero="1")
        h5 titulo
        p Texto_infografia_b
        p Texto_infografia_b
        p.mb-0 Texto_infografia_b
      div(x="50%" y="50%" tooltip="tooltip_de_max_35_caracteres")
        .h5.mb-2 titulo
        p.mb-0 Texto_infografia_b
      div(x="70%" y="70%" tooltip="tooltip_de_max_35_caracteres")
        .h5.mb-2 titulo
        p.mb-0 Texto_infografia_b

    Separador
    .titulo-segundo.color-acento-botones(data-aos="fade-right")
      h2 Video

    figure.mb-5(data-aos="zoom-in")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
        figcaption Video: Leyenda del video
    
    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 Bloques de texto destacado
    
    p.mb-5 Cuando se tiene una información sencilla que se puede explicar en un solo párrafo y acompañada por una imagen es pertinente usar esta herramienta ya que se puede combinar perfectamente con cualquiera de las herramientas anteriormente descritas. Se puede utilizar cuando tenemos un solo bloque de texto, sin subtópicos, listas, ramificaciones y demás divisiones, complementándolo con las demás herramientas. 

    .row.mb-4
      .col-lg-4(data-aos="fade-right")
        .cajon.color-acento-contenido.p-4
          .h5 Cajón texto color
          p Se puede usar dos o más columnas para diagramar el texto, estos elementos pueden presentar contenedores que permitan diferenciar ideas o conceptos.
      .col-lg-8(data-aos="fade-left")
        .cajon.color-acento-botones.p-4
          .h5 Cajón texto color
          p Se puede usar dos o más columnas para diagramar el texto, estos elementos pueden presentar contenedores que permitan diferenciar ideas o conceptos.

    .cajon-b.color-primario.p-3.mb-5(data-aos="fade-right")
      p Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla vel porta justo. Praesent congue nibh a justo ornare, eget vulputate nisl eleifend. Cras interdum finibus lacinia. Fusce dignissim sapien sit amet orci imperdiet, pharetra maximus nisi ullamcorper. Aliquam interdum elit ac nisi viverra, ultrices finibus est ultricies. Fusce tincidunt velit nulla. Aliquam eleifend libero eu neque rhoncus, sed placerat mi ornare.
      p.mb-0 Proin dignissim nisl ac iaculis molestie. Fusce et orci arcu. Cras ac ultricies nisl. Praesent posuere tempor felis in pharetra. Curabitur vestibulum, mi sed placerat accumsan, est nulla sagittis mi, non faucibus tortor ex ac lacus. Nunc condimentum dolor sem, et pulvinar sapien cursus ut. Aenean consequat pharetra rutrum. Nunc vel nunc laoreet, ornare augue a, efficitur quam.

    h3.titulo-tercero Cajón texto color A
    .bloque-texto-a.color-secundario.p-4.p-md-5.mb-5 
      .row.justify-content-between.align-items-center.m-0
        .col-lg-4.mb-lg-0.mb-4(data-aos="fade-right")
          h2.mb-0 Whatever can be captured in words can be conquered with understanding. 
        .col-lg-8(data-aos="fade-left")
          .bloque-texto-a__texto.p-4
            p Think about all the possibilities. A good composition is the result of a hierarchy consisting of clearly contrasting elements set with distinct alignments containing irregular intervals of negative space. Nothing of without working at it. Be impossible to ignore.
            p.mb-0 Stand so tall that they can’t look past you. Saul Bass on failure: Failure is built into creativity… the creative act involves this element of ‘newness’ and ‘experimentalism,’ then one must expect accept possibility of failure. 

    .row.justify-content-center.mb-5
      .col-lg-6.mb-lg-0.mb-4(data-aos="fade-right")
        h3.titulo-tercero Cajón texto color B
        .bloque-texto-b.color-secundario.p-4
          .bloque-texto-b__texto
            i.fas.fa-quote-left
            h2.mb-0 Can we all just agree as the greater design community to stop talking about Comic Sans altogether?
            i.fas.fa-quote-right
      .col-lg-6(data-aos="fade-left")
        h3.titulo-tercero Cajón texto color C
        .bloque-texto-c.color-secundario.p-4
          .bloque-texto-c__contenido
            i.fas.fa-quote-left
            h2.mb-2 Then you’ll prove to yourself that you can survive anything.
            span.autor - The graphic designer
          i.fas.fa-quote-right.cierre-comilla

    .row.justify-content-center.mb-5
      .col-lg-6.mb-lg-0.mb-4(data-aos="fade-right")
        h3.titulo-tercero Cajón texto color D
        .bloque-texto-d.color-secundario.p-4
          .bloque-texto-d__texto.mb-2
            i.fas.fa-quote-left
            h3.text-regular Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent tincidunt augue in augue tempus, in dapibus justo interdum. Sed viverra sed odio quis rhoncus. In elementum purus massa, id venenatis purus ullamcorper ut. Vestibulum vel dictum dolor, nec fringilla orci. Nulla vestibulum, metus nec porttitor bibendum, lectus ligula viverra eros, eget tempor risus nulla pretium justo. Nullam turpis dolor, pharetra vel fermentum at, rutrum in elit. Maecenas vitae hendrerit libero, et ornare augue. Vestibulum iaculis, metus et accumsan malesuada, ligula sapien convallis risus, a iaculis velit ante at turpis. Vivamus bibendum tellus sed tincidunt rhoncus. Nam velit massa, porttitor eget quam et, porttitor viverra eros. Donec eget pharetra metus. Cras porta arcu eu mauris iaculis euismod. Sed fringilla vel nisl quis aliquam.
            i.fas.fa-quote-right
          .bloque-texto-d__autor 
            .h5.mb-0 The graphic designer
            .h6.mb-0 Lorem ipsum dolor sit amet
      .col-lg-6(data-aos="fade-left")
        h3.titulo-tercero Cajón texto color E
        .bloque-texto-e.color-secundario.p-4
          .bloque-texto-e__texto
            i.fas.fa-quote-left
            h2.text-regular Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent tincidunt augue in augue tempus, in dapibus justo interdum. Sed viverra sed odio quis rhoncus. In elementum purus massa, id venenatis purus ullamcorper ut. Vestibulum vel dictum dolor, nec fringilla orci. Nulla vestibulum, metus nec porttitor bibendum, lectus ligula viverra eros, eget tempor risus nulla pretium justo. Nullam turpis dolor, pharetra vel fermentum at, rutrum in elit. Maecenas vitae hendrerit libero, et ornare augue. Vestibulum iaculis, metus et accumsan malesuada.
            i.fas.fa-quote-right
          .row.align-items-end
            .col
              .bloque-texto-e__autor 
                .h5.mb-0 The graphic designer
                .h6.mb-0 Lorem ipsum dolor sit amet
            .col-4
              img(src='@/assets/template/img-placeholder-1-1.svg', alt="Imagen decorativa")

    h3.titulo-tercero Cajón texto color F
    .bloque-texto-f.color-secundario.pt-4.px-5.mb-5(data-aos="fade-right")
      .bloque-texto-f__comillas
        i.fas.fa-quote-left
        i.fas.fa-quote-right
      h4.text-regular.bloque-texto-f__texto Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent tincidunt augue in augue tempus, in dapibus justo interdum. Sed viverra sed odio quis rhoncus. In elementum purus massa, id venenatis purus ullamcorper ut. Vestibulum vel dictum dolor, nec fringilla orci. Nulla vestibulum, metus nec porttitor bibendum, lectus ligula viverra eros, eget tempor risus nulla pretium justo. Nullam turpis dolor, pharetra vel fermentum at, rutrum in elit. Maecenas vitae hendrerit libero, et ornare augue. Vestibulum iaculis, metus et accumsan malesuada, ligula sapien convallis risus, a iaculis velit ante at turpis. Vivamus bibendum tellus sed tincidunt rhoncus. Nam velit massa, porttitor eget quam et, porttitor viverra eros. Donec eget pharetra metus. Cras porta arcu eu mauris iaculis euismod. Sed fringilla vel nisl quis aliquam.
      .bloque-texto-f__autor.mb-3
        h3.mb-0 The graphic designer
      .bloque-texto-f__avatar
        .bloque-texto-f__avatar__img
          img(src='@/assets/template/img-placeholder-1-1.svg', alt="Imagen decorativa")

    h3.titulo-tercero Cajón texto color G
    .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/img.jpg')})`}" data-aos="fade-right"
      )
      .bloque-texto-g__texto.p-4(data-aos="fade-left")
        p.mb-0 Think about all the possibilities. A good composition is the result of a hierarchy consisting of clearly contrasting elements set with distinct alignments containing irregular intervals of negative space. Nothing of without working at it. Be impossible to ignore.
          br
          br
          | Stand so tall that they can’t look past you. Saul Bass on failure: Failure is built into creativity… the creative act involves this element of ‘newness’ and ‘experimentalism,’ then one must expect accept possibility of failure. 

    .bloque-texto-g.bloque-texto-g--inverso.color-secundario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/img.jpg')})`}" data-aos="fade-left"
      )
      .bloque-texto-g__texto.p-4(data-aos="fade-right")
        p.mb-0 Think about all the possibilities. A good composition is the result of a hierarchy consisting of clearly contrasting elements set with distinct alignments containing irregular intervals of negative space. Nothing of without working at it. Be impossible to ignore.
          br
          br
          | Stand so tall that they can’t look past you. Saul Bass on failure: Failure is built into creativity… the creative act involves this element of ‘newness’ and ‘experimentalism,’ then one must expect accept possibility of failure. 

    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h3 Slide navegación simple

    p.mb-4 Provee mayor espacio para la explicación textual así que es óptima para la definición de conceptos completos y extensos. No se asocia a pasos específicos o tipificaciones sino que puede abarcar una temática completa dividida en secciones.

    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h3 Slider A
    .tarjeta.tarjeta--azul.p-4.mb-5
      h4.titulo-cuarto Tipo A
      SlyderA(data-aos="zoom-in")
        .row.justify-content-center
          .col-lg-6.order-lg-1.order-2
            p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
          .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
            img(src='@/assets/template/img-placeholder.svg' alt="Imagen decorativa")
        .row.justify-content-center
          .col-lg-6.col-10.mb-lg-0.mb-4(data-aos="fade-right")
            img(src='@/assets/template/img-placeholder.svg' alt="Imagen decorativa")
          .col-lg-6(data-aos="fade-left")
            p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
        div
          figure
            img.w-75(src='@/assets/template/img-placeholder.svg', alt="Imagen decorativa")
            figcaption Leyenda_de_la_imagen

    .tarjeta.tarjeta--azul.p-4.mb-5
      h4.titulo-cuarto Tipo B
      SlyderA(tipo="b" data-aos="zoom-in")
        .row.justify-content-center
          .col-lg-6.order-lg-1.order-2
            p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
          .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
            img(src='@/assets/template/img-placeholder.svg' alt="Imagen decorativa")
        .row.justify-content-center
          .col-lg-6.col-10.mb-lg-0.mb-4(data-aos="fade-right")
            img(src='@/assets/template/img-placeholder.svg' alt="Imagen decorativa")
          .col-lg-6(data-aos="fade-left")
            p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
        div
          figure
            img.w-75(src='@/assets/template/img-placeholder.svg', alt="Imagen decorativa")
            figcaption Leyenda_de_la_imagen

    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h3 Slider B
    SlyderB.mb-5(:datos="datosSlyder")

    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h3 Slider C
    SlyderC.mb-5(:datos="datosSlyder")

    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h3 Slider D
    SlyderD.mb-5(:datos="datosSlyder")

    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h3 Slyder F
    SlyderF.color-primario.mb-5(columnas="col-lg-6 col-xl-4" data-aos="zoom-in")
      .tarjeta.color-acento-botones.p-4
        .row.justify-content-center.mb-4
          .col-8
            img(src='@/assets/componentes/ej-05.svg' alt="Imagen decorativa")
        h2.text-center FIRST
        p.text-center.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
      .tarjeta.color-acento-botones.p-4
        .row.justify-content-center.mb-4
          .col-8
            img(src='@/assets/componentes/ej-05.svg' alt="Imagen decorativa")
        h2.text-center 2
        p.text-center.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
      .tarjeta.color-acento-botones.p-4
        .row.justify-content-center.mb-4
          .col-8
            img(src='@/assets/componentes/ej-05.svg' alt="Imagen decorativa")
        h2.text-center 3
        p.text-center.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
      .tarjeta.color-acento-botones.p-4
        .row.justify-content-center.mb-4
          .col-8
            img(src='@/assets/componentes/ej-05.svg' alt="Imagen decorativa")
        h2.text-center 4
        p.text-center.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
      .tarjeta.color-acento-botones.p-4
        .row.justify-content-center.mb-4
          .col-8
            img(src='@/assets/componentes/ej-05.svg' alt="Imagen decorativa")
        h2.text-center LAST
        p.text-center.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.

    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h3 Slider Bootstrap
    #carouselExampleIndicators.carousel.slide.mb-5(data-bs-ride='carousel' data-aos="zoom-in")
      .carousel-indicators
        button.active(type='button' data-bs-target='#carouselExampleIndicators' data-bs-slide-to='0' aria-current='true' aria-label='Slide 1')
        button(type='button' data-bs-target='#carouselExampleIndicators' data-bs-slide-to='1' aria-label='Slide 2')
        button(type='button' data-bs-target='#carouselExampleIndicators' data-bs-slide-to='2' aria-label='Slide 3')
      .carousel-inner
        .carousel-item.active
          figure
            img(src='@/assets/template/img-placeholder.svg', alt="Imagen decorativa")
            figcaption Leyenda_de_la_imagen
        .carousel-item
          figure
            img(src='@/assets/template/img-placeholder.svg', alt="Imagen decorativa")
            figcaption Leyenda_de_la_imagen
        .carousel-item
          figure
            img(src='@/assets/template/img-placeholder.svg', alt="Imagen decorativa")
            figcaption Leyenda_de_la_imagen
      button.carousel-control-prev(type='button' data-bs-target='#carouselExampleIndicators' data-bs-slide='prev')
        span.carousel-control-prev-icon(aria-hidden='true')
        span.visually-hidden Previous
      button.carousel-control-next(type='button' data-bs-target='#carouselExampleIndicators' data-bs-slide='next')
        span.carousel-control-next-icon(aria-hidden='true')
        span.visually-hidden Next

    .titulo-segundo.color-acento-botones(data-aos="fade-right")
      h2 Acordiones

    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h3 Acordion A

    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul" data-aos="zoom-in")
      .row.justify-content-center(titulo="Titulo item 1")
        .col-lg-6.order-lg-1.order-2
          p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
        .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
          figure
            img(src='@/assets/template/img-placeholder.svg', alt="Imagen decorativa")
            figcaption Leyenda_de_la_imagen
      div(titulo="Titulo item 2")
        figure
          img(src='@/assets/template/img-placeholder.svg', alt="Imagen decorativa")
          figcaption Leyenda_de_la_imagen

    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h3 Acordion A tipo B

    AcordionA(tipo="b" clase-tarjeta="tarjeta tarjeta--azul" data-aos="zoom-in")
      .row.justify-content-center(titulo="Titulo item 1")
        .col-lg-6.order-lg-1.order-2
          p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
        .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
          figure
            img(src='@/assets/template/img-placeholder.svg', alt="Imagen decorativa")
            figcaption Leyenda_de_la_imagen
      div(titulo="Titulo item 2")
        figure
          img(src='@/assets/template/img-placeholder.svg', alt="Imagen decorativa")
          figcaption Leyenda_de_la_imagen

    Separador
    .titulo-segundo.color-acento-botones(data-aos="fade-right")
      h2 Pestañas o Tabs

    p.mb-3 Es un elemento web que permite cambiar rápidamente el contenido que el usuario está consumiendo sin cambiar de ventana o desplazarse verticalmente por el sitio web. 

    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h3 Pestañas A
    TabsA.color-acento-botones.mb-5(data-aos="fade-right")
      .tarjeta.color-acento-botones--borde.p-4(titulo="Requerimientos de información")
        ul.lista-ul.mb-4
          li
            i.fas.fa-angle-right.txt--green
            | Titulo corto e ilustrativo (cuando aplica).
          li
            i.fas.fa-angle-right.txt--green
            | Cada diapositiva debe ir acompañada de un texto corto de máximo 40 palabras que acompañe a una  foto o ilustración.
      .tarjeta.color-acento-botones--borde.p-4(titulo="PASO 2")
        h4 PASO 2: The splendor
        .row.justify-content-center
          .col-lg-6.col-10.mb-lg-0.mb-4
            img(src='@/assets/template/img-placeholder.svg', alt="Imagen decorativa")
            figcaption Leyenda_de_la_imagen
          .col-lg-6
            p This is a normal paragraph (<code>p</code> element). To add some length to it, let us mention that this page was primarily written for testing the effect of 
              strong user style sheets
              |. You can use it for various other purposes as well, like just checking how your browser displays various HTML elements by default. It can also be useful when testing conversions from HTML format to other formats, since some elements can go wrong then.
            p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
          
    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h3 Pestañas B
    TabsB.color-acento-contenido.mb-5(data-aos="zoom-out")
      .py-4.py-lg-5(titulo="Titulo_1" :icono="require('@/assets/componentes/ej-04.svg')")
        .row.justify-content-center
          .col-lg-7.order-lg-1.order-2
            h4 Celebrate_your_failures_1
            p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
          .col-lg-5.col-10.order-lg-2.order-1.mb-lg-0.mb-4
            img(src='@/assets/template/img-placeholder.svg', alt="Imagen decorativa")
            figcaption Leyenda_de_la_imagen
      .py-4.py-lg-5(titulo="Titulo_2" :icono="require('@/assets/componentes/ej-04.svg')")
        .row.justify-content-center
          .col-lg-6.mb-lg-0.mb-4
            img(src='@/assets/template/img-placeholder.svg', alt="Imagen decorativa")
            figcaption Leyenda_de_la_imagen
          .col-lg-6
            h4 Celebrate_your_failures_2
            p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
      
    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h3 Pestañas C
    TabsC.color-primario.mb-5(data-aos="zoom-out")
      .py-3.py-md-4(titulo="Titulo_1")
        .row.justify-content-center
          .col-lg-6.order-lg-1.order-2
            h4 Celebrate your failures 1
            p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
          .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
            img(src='@/assets/template/img-placeholder.svg', alt="Imagen decorativa")
            figcaption Leyenda_de_la_imagen
      .py-3.py-md-4(titulo="Titulo_2")
        .row.justify-content-center
          .col-lg-6.col-10.mb-lg-0.mb-4
            img(src='@/assets/template/img-placeholder.svg', alt="Imagen decorativa")
            figcaption Leyenda_de_la_imagen
          .col-lg-6
            h4 Celebrate your failures 2
            p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
    
    Separador
    .titulo-segundo.color-acento-botones(data-aos="fade-right")
      h2 Líneas de tiempo
    
    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h3 Linea Tiempo A
    LineaTiempoA.color-acento-contenido.mb-5(:datos="datosLineaTiempoA")

    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h3 Linea Tiempo B
    LineaTiempoB.color-secundario.mb-5(:datos="datosLineaTiempoB")

    .titulo-sexto.color-acento-contenido(data-aos="fade-right")|
      h3 Linea Tiempo C
    .tarjeta.tarjeta--gris.p-4.mb-5
      LineaTiempoC.color-acento-contenido(text-small)
        .row.justify-content-center(titulo="Titulo_1")
          .col-lg-6.order-lg-1.order-2
            p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
          .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
            img(src='@/assets/template/img-placeholder.svg', alt="Imagen decorativa")
            figcaption Leyenda_de_la_imagen
        .row.justify-content-center(titulo="Titulo_2")
          .col-lg-6.order-lg-1.order-2
            p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion. 
          .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
            img(src='@/assets/template/img-placeholder.svg', alt="Imagen decorativa")
            figcaption Leyenda_de_la_imagen

    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h3 Linea Tiempo D
    .row.justify-content-center.mb-5
      .col-lg-6.mb-lg-0.mb-4(data-aos="fade-right")
        LineaTiempoD.color-secundario
          p.text-small(numero="1" titulo="Praesent luctus") This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
          p.text-small(numero="2" titulo="Praesent luctus") This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
          p.text-small(numero="3" titulo="Praesent luctus") This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
      .col-lg-6(data-aos="fade-left")
        LineaTiempoD.color-primario
          .row.justify-content-center(numero="1" titulo="Praesent luctus")
            .col-lg-6.order-lg-1.order-2
              p.text-small.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
            .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
              img(src='@/assets/template/img-placeholder.svg', alt="Imagen decorativa")
              figcaption Leyenda_de_la_imagen
          .row.justify-content-center(numero="2" titulo="Praesent luctus")
            .col-lg-6.col-10.mb-4
              img(src='@/assets/template/img-placeholder.svg', alt="Imagen decorativa")
              figcaption Leyenda_de_la_imagen
            .col-lg-6
              p.text-small.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
          .row.justify-content-center(numero="3" titulo="Praesent luctus")
            .col-lg-6.order-lg-1.order-2
              p.text-small.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
            .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
              img(src='@/assets/template/img-placeholder.svg', alt="Imagen decorativa")
              figcaption Leyenda_de_la_imagen

    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h3 Linea Tiempo E

    LineaTiempoE.color-acento-contenido.mb-5(data-aos="zoom-out")
      .row.justify-content-center(titulo="2014 - <em>Present</em>" subtitulo="Title, Company")
        .col-lg-6.order-lg-1.order-2
          p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
        .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
          img(src='@/assets/template/img-placeholder.svg', alt="Imagen decorativa")
          figcaption Leyenda_de_la_imagen
      div(titulo="1014 - Past" subtitulo="Title, Company")
        figure
          img(src='@/assets/template/img-placeholder.svg', alt="Imagen decorativa")
          figcaption Leyenda_de_la_imagen
      .row.justify-content-center(titulo="2034 - Future" subtitulo="Title, Company")
        .col-lg-6.order-lg-1.order-2
          p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
        .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
          img(src='@/assets/template/img-placeholder.svg', alt="Imagen decorativa")
          figcaption Leyenda_de_la_imagen
    
    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h3 Linea de tiempo Cronologica
    .cronologia.mb-5
      .contenedor
        .tarjeta-evento.tarjeta-evento--paso1(data-aos="fade-left")
          .tarjeta-titulo
            .cajon-numero
              span 01
            h2.p-2.text-white Subtitle
          .tarjeta-cuerpo.p-4
            p This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
            figure
              img(src='@/assets/template/img-placeholder.svg', alt="Imagen decorativa")
              figcaption Leyenda_de_la_imagen 
        .tarjeta-evento.tarjeta-evento--paso2(data-aos="fade-right")
          .tarjeta-titulo
            .cajon-numero
              span 02
            h2 Subtitle
          .tarjeta-cuerpo
            p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
        .tarjeta-evento.tarjeta-evento--paso3(data-aos="fade-left")
          .tarjeta-titulo
            .cajon-numero
              span 03
            h2 Subtitle
          .tarjeta-cuerpo
            p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
        .tarjeta-evento.tarjeta-evento--paso4(data-aos="fade-right")
          .tarjeta-titulo
            .cajon-numero
              span 04
            h2 Subtitle
          .tarjeta-cuerpo
            p.mb-0 This is another paragraph.

    Separador
    .titulo-segundo.color-acento-botones(data-aos="fade-right")
      h2 Pasos

    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h3 Pasos A tipo n
    PasosA.color-primario.mb-5(tipo="n")
      .row.justify-content-center
        .col-lg-6.order-lg-1.order-2(data-aos="fade-right")
          h3 titulo_1
          p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
        .col-lg-4.col-8.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
          img(src='@/assets/template/img-placeholder.svg', alt="Imagen decorativa")
          figcaption Leyenda_de_la_imagen
      .row.justify-content-center
        .col-lg-4.col-8.mb-lg-0.mb-4(data-aos="fade-right")
          img(src='@/assets/template/img-placeholder.svg', alt="Imagen decorativa")
          figcaption Leyenda_de_la_Imagen
        .col-lg-8(data-aos="fade-left")
          h3 titulo_2
          p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
      .row.justify-content-center
        .col-lg-6.order-lg-1.order-2(data-aos="fade-right")
          h3 titulo_1
          p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
        .col-lg-4.col-8.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
          img(src='@/assets/template/img-placeholder.svg', alt="Imagen decorativa")
          figcaption Leyenda_de_la_imagen
      .row.justify-content-center
        .col-lg-4.col-8.mb-lg-0.mb-4(data-aos="fade-right")
          img(src='@/assets/template/img-placeholder.svg', alt="Imagen decorativa")
          figcaption Leyenda_de_la_Imagen
        .col-lg-8(data-aos="fade-left")
          h3 titulo_2
          p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.

    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h3 Pasos A tipo l
    PasosA.color-acento-botones.mb-5(tipo="l")
      div(data-aos="fade-left")
        h3 Titulo_Pasos_A
        p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
      div(data-aos="fade-right")
        h3 Titulo_Pasos_A
        p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
      div(data-aos="fade-left")
        h3 Titulo_Pasos_A
        p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
      div(data-aos="fade-right")
        h3 Titulo_Pasos_A
        p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.

    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h3 Pasos B
    .tarjeta.tarjeta--gris.p-4
      PasosB.color-acento-contenido(data-aos="zoom-in")
        .row.justify-content-center(titulo="titulo_pasos_b")
          .col-lg-6.order-lg-1.order-2
            p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
          .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
            img(src='@/assets/template/img-placeholder.svg', alt="Imagen decorativa")
            figcaption Leyenda_de_la_imagen
        .row.justify-content-center(titulo="titulo_pasos_b")
          .col-lg-6.order-lg-1.order-2
            p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
          .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4
            img(src='@/assets/template/img-placeholder.svg', alt="Imagen decorativa")
            figcaption Leyenda_de_la_imagen
        
    Separador
    .titulo-segundo.color-acento-botones(data-aos="fade-right")
      h2 Llamados a la acción

    p Es un bloque de texto que destaca por su composición y diseño. Su principal función es incentivar al usuario a realizar una acción a través de un botón o hipervínculo, en este caso, con el fin de poder acceder a recursos como infografías, videos, documentos y sitios web externos e independientes del componente formativo.
    
    h3 #[i.fas.fa-angle-double-right.txt--green] Ejemplo: Llamado a la acción 1 Acción de infografías
    .tarjeta.color-acento-botones.p-4.p-md-5.mb-5(data-aos="fade-right")
      .row.justify-content-around.align-items-center
        .col-8.col-sm-6.col-md-4.mb-4.mb-md-0
          img(src="@/assets/componentes/ej-01.png")
        .col-md.col-lg-6
          h3 Título del recurso
          p.mb-4 There is no right answer. The splendor of the mystery is that you don’t understand. Your rapidograph pens are dried up, the x-acto blades in your bag are rusty, and your mind is dull. Stop clicking your mouse, get messy, go back to the basics and make something original. Why are you reading all of this?  
          a.boton.color-acento-contenido.texto-blanco(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank" type="application/pdf")
            span Descargar
            i.fas.fa-file-download

    h3 #[i.fas.fa-angle-double-right.txt--green] Ejemplo: Llamado a la acción 2 Recursos externos
    .tarjeta.color-primario.p-3.mb-5(data-aos="fade-right")
      .row.justify-content-around.align-items-center
        .col-3.col-sm-2.col-lg-1
          img(src="@/assets/componentes/ej-02.svg")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-sm-0.mb-4
              h3.mb-1 Título del recurso
              p.text-small Consideraciones generales de tratamiento clínico del paciente con COVID-19 en el servicio de urgencias  
            .col-sm-auto
              a.boton.color-acento-contenido.texto-blanco(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank")
                span Descargar
                i.fas.fa-file-download

    h3 #[i.fas.fa-angle-double-right.txt--green] Ejemplo: Llamado a la acción 3 Recursos externos versión simplificada
    .row.justify-content-center.mb-5
      .col-lg-6
        a.anexo.mb-4(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank" data-aos="fade-right")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p.mb-0 Anexo. Consideraciones generales de tratamiento clínico del paciente con COVID-19 en el servicio de urgencias   
        a.anexo.mb-4(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank" data-aos="fade-right")
          .anexo__icono
            img(src="@/assets/template/icono-doc.svg")
          .anexo__texto
            p.mb-0 Anexo. Consideraciones generales de tratamiento clínico del paciente con COVID-19 en el servicio de urgencias
        a.anexo.mb-4(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank" data-aos="fade-right")
          .anexo__icono
            img(src="@/assets/template/icono-xls.svg")
          .anexo__texto
            p.mb-0 Anexo. Consideraciones generales de tratamiento clínico del paciente con COVID-19 en el servicio de urgencias
        a.anexo.mb-4(href="https://en.wikipedia.org/wiki/Main_Page" target="_blank" data-aos="fade-right")
          .anexo__icono
            img(src="@/assets/template/icono-video.svg")
          .anexo__texto
            p.mb-0 Anexo. Consideraciones generales de tratamiento clínico del paciente con COVID-19 en el servicio de urgencias
      .col-lg-6
        a.anexo.mb-4(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank" data-aos="fade-right")
          .anexo__icono
            img(src="@/assets/template/icono-zip.svg")
          .anexo__texto
            p.mb-0 Anexo. Consideraciones generales de tratamiento clínico del paciente con COVID-19 en el servicio de urgencias
        a.anexo.mb-4(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank" data-aos="fade-right")
          .anexo__icono
            img(src="@/assets/template/icono-ppt.svg")
          .anexo__texto
            p.mb-0 Anexo. Consideraciones generales de tratamiento clínico del paciente con COVID-19 en el servicio de urgencias
        a.anexo(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank" data-aos="fade-right")
          .anexo__icono
            img(src="@/assets/template/icono-xml.svg")
          .anexo__texto
            p.mb-0 Anexo. Consideraciones generales de tratamiento clínico del paciente con COVID-19 en el servicio de urgencias

    Separador
    .titulo-segundo.color-acento-botones(data-aos="fade-right")
      h2 Tarjetas

    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h3 Pasos tarjeta de deslizamiento arriba / abajo
    .row.justify-content-center.mb-5
      .col-xl-5.col-lg-6.col-sm-8.col-10.mb-4(data-aos="fade-right")
        .tarjetas-up(@mouseover="mostrarIndicador = false")
          .indicador--hover(v-if="mostrarIndicador")
          img(src='@/assets/template/img-placeholder.svg' alt="Imagen decorativa")
          .tarjetas-up__card.tarjeta.color-primario.p-lg-3.p-4
            .title.d-flex.align-items-center.justify-content-center.mb-4
              span
                i.fas.fa-caret-up.fa-2x.me-3
                i.fas.fa-caret-down.fa-2x.me-3
              h4.mb-0 Tarjeta_up
            p.text-center.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
      .col-xl-5.col-lg-6.col-sm-8.col-10.mb-4(data-aos="fade-left")
        .tarjetas-up(@mouseover="mostrarIndicador = false")
          .indicador--hover(v-if="mostrarIndicador")
          img(src='@/assets/template/img-placeholder.svg' alt="Imagen decorativa")
          .tarjetas-up__card.tarjeta.color-secundario.p-lg-3.p-4
            .title.d-flex.align-items-center.justify-content-center.mb-4
              span
                i.fas.fa-caret-up.fa-2x.me-3
                i.fas.fa-caret-down.fa-2x.me-3
              h4.mb-0 Tarjeta_up
            p.text-center.mb-0 This is another paragraph.

    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h3 Tarjetas botones
    .row.justify-content-center.mb-5
      .col-lg-3.col-sm-6.mb-4.mb-lg-0(data-aos="fade-right")
        .tarjeta--boton.color-primario.p-4
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/componentes/ej-03.svg', alt="Imagen decorativa")
          h3.text-center Tarjeta_botones
          p.text-small.mb-0 Sed ut perspiciatis unde omnis iste natus error sit vtatem accusa ntium dol.
      .col-lg-3.col-sm-6.mb-4.mb-lg-0(data-aos="fade-left")
        .tarjeta--boton.color-secundario.p-4
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/componentes/ej-03.svg', alt="Imagen decorativa")
          h3.text-center Tarjeta_botones
          p.text-small.mb-0 Sed ut perspiciatis unde omnis iste natus error sit vtatem accusa ntium dol.

    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h3 Tarjetas conectadas
    .tarjeta--container.row.mb-5
      .col-md.tarjeta.color-primario.p-5(data-aos="fade-right")
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/componentes/ej-05.svg', alt="Imagen decorativa")
        h2.text-center Tarjeta_container
        p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
      .col-md.tarjeta.color-acento-botones.p-5(data-aos="flip-up")
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/componentes/ej-05.svg', alt="Imagen decorativa")
        h2.text-center Tarjeta_container
        p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
      .col-md.tarjeta.color-acento-contenido.text-white.p-5(data-aos="fade-left")
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/componentes/ej-05.svg', alt="Imagen decorativa")
        h2.text-center Tarjeta_container
        p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.

    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h3 Tarjetas avatar A
    .row
      .col-lg-6.mb-4.mb-lg-0(data-aos="fade-right")
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/componentes/ej-05.svg' alt="Imagen decorativa")
          .tarjeta.tarjeta--azul
            .p-4
              h2 Tarjeta_avatar_a
              p This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
      .col-lg-6(data-aos="fade-left")
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/componentes/ej-05.svg' alt="Imagen decorativa")
          .tarjeta.color-acento-botones
            .p-4
              h2 Tarjeta_avatar_a
              p This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.

    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h3 Tarjetas avatar B
    .row.mb-5
      .col-lg.col-md-6.mb-lg-0.mb-4(data-aos="fade-right")
        .tarjeta-avatar
          img(src='@/assets/componentes/ej-05.svg' alt="Imagen decorativa")
          .tarjeta.color-primario
            .text-white.p-4
              h2.text-center Tarjeta_avatar_b
              p This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
      .col-lg.col-md-6.mb-lg-0.mb-4(data-aos="flip-up")
        .tarjeta-avatar
          img(src='@/assets/componentes/ej-05.svg' alt="Imagen decorativa")
          .tarjeta.color-acento-botones
            .p-4
              h2.text-center Tarjeta_avatar_b
              p This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
      .col-md-6.col-lg.mb-lg-0.mb-4(data-aos="fade-left")
        .tarjeta-avatar
          img(src='@/assets/componentes/ej-05.svg' alt="Imagen decorativa")
          .tarjeta.color-acento-contenido
            .p-4
              h2.text-center Tarjeta_avatar_b
              p This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.

    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h3 Tarjetas flip

    .row.justify-content-center.mb-5
      .col-lg-3.col-sm-6.mb-lg-0.mb-4(data-aos="fade-right")
        .tarjeta.tarjeta-flip.color-primario(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/avatar.svg')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5
              h1 Tarjeta_flip
              p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
      .col-lg-3.col-sm-6.mb-lg-0.mb-4(data-aos="fade-left")
        .tarjeta.tarjeta-flip.color-secundario(@mouseover="indicadorTarjetaFlip = false")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/avatar.svg')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5
              h1 Tarjeta_flip
              p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.

    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h3 Tarjetas slide

    .row.justify-content-center.mb-5
      .col-lg-3.col-sm-6.mb-lg-0.mb-4(data-aos="fade-right")
        .tarjeta.tarjeta-slide.arriba.color-primario(@mouseover="indicadorTarjetaSlide = false")
          .indicador--hover(v-if="indicadorTarjetaSlide")
          .tarjeta-slide__contenedor
            .tarjeta-slide__contenido.p-4.p-xl-5
              h1 Tarjeta_slide
              p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
            .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/avatar.svg')})`}")
      .col-lg-3.col-sm-6.mb-lg-0.mb-4(data-aos="fade-right")
        .tarjeta.tarjeta-slide.abajo.color-secundario(@mouseover="indicadorTarjetaSlide = false")
          .tarjeta-slide__contenedor
            .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/avatar.svg')})`}")
            .tarjeta-slide__contenido.p-4.p-xl-5
              h1 Tarjeta_slide
              p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
      .col-lg-3.col-sm-6.mb-lg-0.mb-4(data-aos="fade-right")
        .tarjeta.tarjeta-slide.derecha.color-acento-contenido(@mouseover="indicadorTarjetaSlide = false")
          .tarjeta-slide__contenedor
            .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/avatar.svg')})`}")
            .tarjeta-slide__contenido.p-4.p-xl-5
              h1 Tarjeta_slide
              p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
      .col-lg-3.col-sm-6.mb-lg-0.mb-4(data-aos="fade-right")
        .tarjeta.tarjeta-slide.izquierda.color-acento-botones(@mouseover="indicadorTarjetaSlide = false")
          .tarjeta-slide__contenedor
            .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/avatar.svg')})`}")
            .tarjeta-slide__contenido.p-4.p-xl-5
              h1 Tarjeta_slide
              p.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.

    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h3 Tarjetas Tabla
    .row.mb-5
      .col-lg.col-md-6.tarjeta--tabla.p-4(data-aos="fade-right")
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/componentes/ej-05.svg' alt="Imagen decorativa")
        h2.text-center Tarjeta_tabla
        p.text-center.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
      .col-lg.col-md-6.tarjeta--tabla.p-4(data-aos="flip-right")
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/componentes/ej-05.svg' alt="Imagen decorativa")
        h2.text-center Tarjeta_tabla
        p.text-center.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
      .col-lg.col-md-6.tarjeta--tabla.p-4(data-aos="flip-left")
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/componentes/ej-05.svg' alt="Imagen decorativa")
        h2.text-center Tarjeta_tabla
        p.text-center.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
      .col-lg.col-md-6.tarjeta--tabla.p-4(data-aos="fade-left")
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/componentes/ej-05.svg' alt="Imagen decorativa")
        h2.text-center Tarjeta_tabla
        p.text-center.mb-0 This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.

    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h3 Tarjetas con número
    .row.mb-5
      .col-lg.col-md-6.mb-lg-0.mb-4(data-aos="fade-right")
        .tarjeta-numerada.color-primario.p-5
          .tarjeta-numerada__numero
            .h2 1
          p.text-center 
            b Tarjeta_numerada
          p.text-center.mb-0 Acciones realizadas en los entornos donde transcurre la vida y se desarrollan las personas
      .col-lg.col-md-6.mb-lg-0.mb-4(data-aos="flip-right")
        .tarjeta-numerada.color-secundario.p-5
          .tarjeta-numerada__numero
            .h2 2
          p.text-center 
            b Tarjeta_numerada
          p.text-center.mb-0 Acciones realizadas en los entornos donde transcurre la vida y se desarrollan las personas
      .col-lg.col-md-6.mb-lg-0.mb-4(data-aos="flip-left")
        .tarjeta-numerada.color-acento-contenido.p-5
          .tarjeta-numerada__numero
            .h2 3
          p.text-center 
            b Tarjeta_numerada
          p.text-center.mb-0 Acciones realizadas en los entornos donde transcurre la vida y se desarrollan las personas
      .col-lg.col-md-6.mb-lg-0.mb-4(data-aos="fade-left")
        .tarjeta-numerada.color-acento-botones.p-5
          .tarjeta-numerada__numero
            .h2 4
          p.text-center 
            b Tarjeta_numerada
          p.text-center.mb-0 Acciones realizadas en los entornos donde transcurre la vida y se desarrollan las personas
    
    Separador
    .titulo-segundo.color-acento-botones
      h2 Modal

    .row
      .col-auto
        a.boton.color-acento-contenido.indicador__container(@click="modal1 = true")
          span Abrir modal
          .indicador--click(v-if="mostrarIndicador")
      .col
        p moment. Abandon the shelter of insecurity. Be bold. Greatness isn’t 
          a.lnk(@click="modal1 = true") Abrir modal 
          |the height of your stature, it’s the heft of your spirit.

    ModalA(:abrir-modal.sync="modal1")
      .row.align-items-center
        .col-lg-6.mb-4.mb-md-0
          h4 Modal 1
          p This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
        .col-lg-6
          figure
            img(src='@/assets/template/img-placeholder.svg', alt='Texto que describa la imagen')
            figcaption Leyenda de la imagen

    Separador
    .titulo-segundo.color-acento-botones
      h2 Animaciones

    h3.titulo-tercero Fade
    .row.mb-5
      .col-sm-6.col-md-4.col-lg-3.col-xxl-2.mb-3
        .tarjeta.color-acento-botones.text-center.p-3(data-aos="fade-left")
          h3.mb-0 fade-left
      .col-sm-6.col-md-4.col-lg-3.col-xxl-2.mb-3
        .tarjeta.color-primario.text-center.p-3(data-aos="fade-right")
          h3.mb-0 fade-right

    h3.titulo-tercero Flip
    .row.mb-5
      .col-sm-6.col-md-4.col-lg-3.col-xxl-2.mb-3
        .tarjeta.color-primario.text-center.p-3(data-aos="flip-up")
          h3.mb-0 flip-up
      .col-sm-6.col-md-4.col-lg-3.col-xxl-2.mb-3
        .tarjeta.color-secundario.text-center.p-3(data-aos="flip-down")
          h3.mb-0 flip-down
      .col-sm-6.col-md-4.col-lg-3.col-xxl-2.mb-3
        .tarjeta.color-acento-contenido.text-center.p-3(data-aos="flip-left")
          h3.mb-0 flip-left
      .col-sm-6.col-md-4.col-lg-3.col-xxl-2.mb-3
        .tarjeta.color-acento-botones.text-center.p-3(data-aos="flip-right")
          h3.mb-0 flip-right

    h3.titulo-tercero Zoom
    .row
      .col-sm-6.col-md-4.col-lg-3.col-xxl-2.mb-3
        .tarjeta.color-primario.text-center.p-3(data-aos="zoom-in")
          h3.mb-0 zoom-in
      .col-sm-6.col-md-4.col-lg-3.col-xxl-2.mb-3
        .tarjeta.color-secundario.text-center.p-3(data-aos="zoom-in-up")
          h3.mb-0 zoom-out

</template>

<script>
export default {
  name: 'Muestras',
  data: () => ({
    mostrarIndicador: true,
    indicadorTarjetaFlip: true,
    indicadorTarjetaSlide: true,
    modal1: false,
    datosSlyder: [
      {
        titulo: 'Titulo_Slyder',
        texto:
          'This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.',
        imagen: require('@/assets/template/img-placeholder.svg'),
        // leyendaImagen: 'Leyenda_de_la_imagen',
      },
      {
        titulo: 'Titulo_Slyder',
        texto:
          'This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.',
        imagen: require('@/assets/template/img-placeholder.svg'),
        // leyendaImagen: 'Leyenda_de_la_imagen',
      },
      {
        titulo: 'Titulo_Slyder',
        texto:
          'This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.',
        imagen: require('@/assets/template/img-placeholder.svg'),
        leyendaImagen: 'Leyenda_de_la_imagen',
      },
      {
        titulo: 'Titulo_Slyder',
        texto:
          'This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.',
        imagen: require('@/assets/template/img-placeholder.svg'),
        leyendaImagen: 'Leyenda_de_la_imagen',
      },
    ],
    datosLineaTiempoA: [
      {
        ano: '100.000 - 10.000 A.C.',
        titulo: 'Período Paleolítico',
        texto: 'Pieles, pelo de animales, hojas, huesos y conchas.',
      },
      {
        ano: '10.000 - 5.000 A.C.',
        titulo: 'Periodo Mesolítico',
        texto:
          'Broches hechos con hueso, abrigos, gorros, botas y zapatillas de cuero.',
      },
      {
        ano: '10.000 - 5.000 A.C.',
        titulo: 'Periodo Neolítico',
        texto: 'Vestimenta de fibras animales y vegetales, pulseras de marfil.',
      },
    ],
    datosLineaTiempoB: [
      {
        titulo: '01 de marzo',
        texto:
          'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam tellus augue, pulvinar ac auctor at, pellentesque id diam. Praesent maximus, felis sollicitudin pharetra vestibulum, turpis tortor tincidunt augue, in efficitur urna diam eleifend magna.',
        icono: require('@/assets/componentes/ej-05.svg'),
      },
      {
        titulo: '02 de marzo',
        texto:
          'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam tellus augue, pulvinar ac auctor at, pellentesque id diam. Praesent maximus, felis sollicitudin pharetra vestibulum, turpis tortor tincidunt augue, in efficitur urna diam eleifend magna.',
        icono: require('@/assets/componentes/ej-05.svg'),
      },
      {
        titulo: '03 de marzo',
        texto:
          'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam tellus augue, pulvinar ac auctor at, pellentesque id diam. Praesent maximus, felis sollicitudin pharetra vestibulum, turpis tortor tincidunt augue, in efficitur urna diam eleifend magna.',
        icono: require('@/assets/componentes/ej-05.svg'),
      },
    ],
  }),
}
</script>

<style lang="sass"></style>
