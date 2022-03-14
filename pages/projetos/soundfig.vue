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
    <div class="container mx-auto"> 
       <h1 class="text-lg font-bold">SoundFig</h1>
       <div class="webview">
            <h2>Layout Fixo</h2>
            <iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FLBDfh4baU7BLTOFSy2SEGG%2FSoundFig" allowfullscreen></iframe>
        </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>