<template>
  <div>
    <h1>{{ titulo }}</h1>
    <ul>
      <li v-for="foto in fotos">
        <img :src="foto.url" :alt="foto.titulo">
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      titulo: 'AluraPic',
      fotos: [
        {
          url: 'https://www.petz.com.br/blog/wp-content/uploads/2019/04/como-saber-se-o-cachorro-esta-com-febre-doencas.jpg',
          titulo: 'cachorro'
        },
        {
          url: 'https://www.petz.com.br/blog/wp-content/uploads/2019/04/como-saber-se-o-cachorro-esta-com-febre-doencas.jpg',
          titulo: 'cachorro'
        }
      ]
    }
  }
}
</script>

<style>
</style>
