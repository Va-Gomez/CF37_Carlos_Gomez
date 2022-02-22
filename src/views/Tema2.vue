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
      .bloque-texto-e.color-acento-botones.justify-content-center
        .col-9.mb-4
        .col-3.mb-4
        p En resumen, se puede decir que el blockchain o cadena de bloques es un gran libro digital de cuentas en donde sus bloques (registros) se encuentran conectados y cifrados con el objetivo de proteger la privacidad y la seguridad de cualquier tipo de transacciones. 
        .col-md-2
          figure
            img(src='@/assets/curso/imgtm01.jpg')

    br

    p En la siguiente figura se muestra gráficamente la comparación entre un sistema tradicional y un sistema blockchain.

    .titulo-sexto.color-acento-contenido
      h5 Figura 2
      br
      span Sistema tradicional vs Sistema blockchain

    .row
      .col-md-6.mb-4.mb-md-0
      img(src='@/assets/template/imgtm001.svg')
      .col-md-6
      img(src='@/assets/template/imgtm002.svg')

    br

    .titulo-segundo.color-acento-contenido
      h2 2.1 Historia

    p El blockchain tuvo su inicio en los años de 1991-2008, en un primer trabajo Stuart Haber y Scott realizaron tareas en una cadena de bloques que era protegida criptográficamente, esto quería decir que no se podía realizar ningún tipo de manipulación en las marcas de tiempo de los documentos. En el año 1991 se añadieron árboles de Merkle que lograron una mejor eficiencia, permitiendo que en un solo bloque se recopilara más de un documento. Pero es en el año 2008 que el blockchain inicia su crecimiento cuando Satoshi Nakamoto y un grupo de personas lanzan su trabajo con bitcoin, creando la primera aplicación de registro digital que permitía administrar la red del bitcoin, permitiendo la interacción por medio de foros entre los interesados. 
    br
    p Desde los años 2008 al 2013 emerge el bitcoin y las transacciones, es importante aclarar que no hay que confundir el concepto de blockchain y bitcoin, ya que muchas personas piensan que es lo mismo, y no es así debido a que blockchain es la tecnología en que se fundamentan las aplicaciones y una de ellas es la criptomoneda. El nacimiento del bitcoin fue en 2008 y fue la primera aplicación que incluía la tecnología blockchain, la definición dada por Satoshi Nakamoto en su artículo fue que se trataba de un sistema eléctrico peer to peer (punto a punto) (Nakamoto, 2008). 
    br
    p Satoshi estableció el bloque origen de donde salieron otros bloques, los cuales se interconectaban obteniendo como resultado una gran cadena de bloques que enviaban varios fragmentos de información y transacciones. Desde el momento en que el bitcoin que es una aplicación de blockchain se puso en conocimiento han surgido una gran variedad de aplicaciones que tienen como objetivo el aprovechamiento de la tecnología digital.
    img.p-6(src='@/assets/curso/imgtm02.jpg')


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
