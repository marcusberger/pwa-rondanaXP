<template>
  <div>
    <h1>{{ titulo }}</h1>
    <img :src="logo.url" v-bind:alt="logo.titulo">
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      titulo: 'Quiz Engajamento',
      logo: {
        url:'http://hondana.com.br/wp-content/uploads/2017/09/logo-hondana.png',
        titulo: 'logo-hondana'
      }
    }
  }
}
</script>

<style>
</style>
