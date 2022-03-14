<template>
  <div>
    <div class="bg-gray-100">
      <div class="container mx-auto flex items-center h-10 space-x-4">
        <!-- duas formas de navegação -->
        <!-- primeira por objeto o que facilita a passagem de parametros -->
         <nuxt-link :to="{name: 'sobre', params: {} }">Sobre</nuxt-link>
         <nuxt-link to="/serviço">serviço</nuxt-link>
         <nuxt-link to="/projetos">Projetos</nuxt-link>
      </div>
    </div>
    <div> 
        <nuxt-link to="/projetos/soundfig"> SoundFig </nuxt-link>
        a
        a
        <nuxt-link :to="{name: 'projetos', params: '' }"> SoundFig </nuxt-link>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>