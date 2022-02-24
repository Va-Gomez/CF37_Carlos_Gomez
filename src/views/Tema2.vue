<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span.text-white 2
      h1 Blockchain

    p En la siguiente figura se explica en qué consiste esta tecnología.

    .titulo-sexto.color-acento-contenido
      h5 Figura 2
      br
      span Blockchain

    figure
      img(src='@/assets/template/imgtm02.svg')

    br
    br

    h4 El problema que quiere solucionar esta tecnología se puede explicar en el siguiente ejemplo: 

    br

    .row
      .col-md-6.mb-4.mb-md-0
        p Cuando una persona llamada Pepito quiere realizar un envío de un millón de pesos a otra persona llamada Mario normalmente se hace por medio de un banco, donde el banco actúa como intermediario de esta transacción haciendo una centralización efectiva para hacer el movimiento de un lado al otro. En este proceso, ni Pepito ni Mario intervienen, son totalmente dependientes del banco y a las condiciones de este como comisiones, por ejemplo, es aquí donde el blockchain o cadena de bloques interviene, porque su principal objetivo es eliminar los intermediarios haciendo una gestión totalmente descentralizada, donde el control ya no va a hacer de los bancos si no de los usuarios convirtiéndose estos en una conexión de muchos nodos del banco. 
    
      .col-md-6
        figure
          img(src='@/assets/template/imgtm03.svg')

    br

    .row
      .bloque-texto-e.color-acento-botones
        .col-7
          p En resumen, se puede decir que el blockchain o cadena de bloques es un gran libro digital de cuentas en donde sus bloques (registros) se encuentran conectados y cifrados con el objetivo de proteger la privacidad y la seguridad de cualquier tipo de transacciones.
        .col-3
          img(src='@/assets/curso/imgtm01.jpg')

    br

    p En la siguiente figura se muestra gráficamente la comparación entre un sistema tradicional y un sistema blockchain.

    .titulo-sexto.color-acento-contenido
      h5 Figura 2
      br
      span Sistema tradicional vs Sistema blockchain

    .row
      .col-6
        img(src='@/assets/template/imgtm001.svg')
      .col-6
        img(src='@/assets/template/imgtm002.svg')

    br

    .titulo-segundo.color-acento-contenido
      h2 2.1 Historia

    p El blockchain tuvo su inicio en los años de 1991-2008, en un primer trabajo Stuart Haber y Scott realizaron tareas en una cadena de bloques que era protegida criptográficamente, esto quería decir que no se podía realizar ningún tipo de manipulación en las marcas de tiempo de los documentos. En el año 1991 se añadieron árboles de Merkle que lograron una mejor eficiencia, permitiendo que en un solo bloque se recopilara más de un documento. Pero es en el año 2008 que el blockchain inicia su crecimiento cuando Satoshi Nakamoto y un grupo de personas lanzan su trabajo con bitcoin, creando la primera aplicación de registro digital que permitía administrar la red del bitcoin, permitiendo la interacción por medio de foros entre los interesados. 
    br
    p Desde los años 2008 al 2013 emerge el bitcoin y las transacciones, es importante aclarar que no hay que confundir el concepto de blockchain y bitcoin, ya que muchas personas piensan que es lo mismo, y no es así debido a que blockchain es la tecnología en que se fundamentan las aplicaciones y una de ellas es la criptomoneda. El nacimiento del bitcoin fue en 2008 y fue la primera aplicación que incluía la tecnología blockchain, la definición dada por Satoshi Nakamoto en su artículo fue que se trataba de un sistema eléctrico peer to peer (punto a punto) (Nakamoto, 2008). 
    br
    p Satoshi estableció el bloque origen de donde salieron otros bloques, los cuales se interconectaban obteniendo como resultado una gran cadena de bloques que enviaban varios fragmentos de información y transacciones. Desde el momento en que el bitcoin que es una aplicación de blockchain se puso en conocimiento han surgido una gran variedad de aplicaciones que tienen como objetivo el aprovechamiento de la tecnología digital.
    img.col-6(src='@/assets/curso/imgtm02.jpg')
    p Ya para los años 20013-2015 blockchain evolucionó a su versión 2.0 y trajo con esta versión los llamados contratos inteligentes (smart contracts) desarrollo realizado por Vitalik Butterin y al que llamaron Ethereum, que incorporaba una función que ofrece a los individuos registrar otro tipo de activos como lo son los contratos, ampliando a una plataforma que también desarrolla aplicaciones descentralizadas. Un contrato inteligente es un conjunto de instrucciones que se almacenan en un blockchain, las cuales se ejecutan automáticamente dependiendo de los parámetros programados, esta ejecución se realiza de forma segura e inmutable. 
    br
    p A partir del 2018 surgen una serie de proyectos explotando la gran capacidad de la tecnología blockchain, estos proyectos buscaban tratar las fallas de Ethereum y Bitcoin, incluyendo también nuevas características. Una de las aplicaciones más representativas fueron IOTA y NEO enfocadas en proporcionar más seguridad y escalabilidad que las aplicaciones iniciales de blockchain.

    br
    h3 Revise la siguiente línea de tiempo que resume la historia del blockchain. 
    br

    .tarjeta.tarjeta--gris.p-4.mb-5
      LineaTiempoC.color-secundario(text-small)
        .row(titulo="1991 - 2008")
          .col-md-6.mb-4.mb-md-0
            p Stuar Haber y Scott Stornetta trabajan en el primer blockchain
        
          .col-md-6
            figure
              img(src='@/assets/template/his01.svg')


        .row(titulo="2009")
          .col-md-6.mb-4.mb-md-0
            p Satoshi Nakamoto lanza el whitepaper de bitcoin
        
          .col-md-3
            figure
              img(src='@/assets/template/his02.svg', alt='Texto que describa la imagen')


        .row(titulo="2010")
          .col-md-6.mb-4.mb-md-0
            p La primera compra de bitcoin tiene lugar 10.000 BTC
        
          .col-md-3
            figure
              img(src='@/assets/template/his03.svg', alt='Texto que describa la imagen')


        .row(titulo="2013")
          .col-md-6.mb-4.mb-md-0
            p El mercado de bitcoin supera los $1 mil millones Vitalik Buterín lanza el whitepaper de Ethereum
        
          .col-md-3
            figure
              img(src='@/assets/template/his04.svg', alt='Texto que describa la imagen')


        .row(titulo="2014")
          .col-md-6.mb-4.mb-md-0
            p Ethereum blockchain es financiado por crowdsale La tecnología blockchain R3 se forma e inicia un consorcio de más de 40 compañías financieras legadas para implementar la tecnología blockchain 
        
          .col-md-3
            figure
              img(src='@/assets/template/his05.svg', alt='Texto que describa la imagen')

        .row(titulo="2015")
          .col-md-6.mb-4.mb-md-0
            p El bloque Génesis de Ethereum es creado Linux foundation presenta hyperledger para mejorar

          .col-md-3
            figure
              img(src='@/assets/template/his06.svg', alt='Texto que describa la imagen')

        .row(titulo="2016")
          .col-md-6.mb-4.mb-md-0
            p Error en el código de Ethereum DAO explotado y atacado

          .col-md-3
            figure
              img(src='@/assets/template/his07.svg', alt='Texto que describa la imagen')

        .row(titulo="2017")
          .col-md-6.mb-4.mb-md-0
            p EOS es presentado por Blockone como un nuevo protocolo de blockchain para el despliegue de aplicaciones descentralizadas
    br
    p Es así como podemos concluir que el blockchain se define como un tipo de comercio donde interactúan criptomonedas y transacciones, aunque la realidad es que es más que un seguro sistema bancario en línea, porque permite además, el fácil intercambio de objetos e ideas.
    br

    h3 Las características principales son:
    br
    
        
    .tarjeta.color-primario.p-4.p-md-5.mb-5.col-6
      .row.align-items-center
        .col-4.col-sm-6.col-md-4.mb-4.mb-md-0
          img(src="@/assets/componentes/car01.svg")

        .col-md.col-lg-6
          h3 Inmutabilidad: 
          p.mb-4  los datos grabados en las cadenas son irreversibles.
          
    .tarjeta.color-primario.p-4.p-md-5.mb-5.col-6
      .row.align-items-center
        .col-4.col-sm-6.col-md-4.mb-4.mb-md-0
          img(src="@/assets/componentes/car01.svg")

        .col-md.col-lg-6
          h3 Inmutabilidad: 
          p.mb-4  los datos grabados en las cadenas son irreversibles.
         


</template>

<script>
export default {
  name: 'Tema2',
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
