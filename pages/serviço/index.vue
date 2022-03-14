<template>
  <div>
    <div class="bg-gray-100">
      <div class="container mx-auto flex items-center h-10 space-x-4">
        <!-- duas formas de navegação -->
        <!-- primeira por objeto o que facilita a passagem de parametros -->
         <nuxt-link to="/sobre">Sobre</nuxt-link>
         <nuxt-link to="/serviço">serviço</nuxt-link>
         <nuxt-link :to="{name: 'projetos', params: {soundfig} }">Projetos</nuxt-link>
      </div>
    </div>
    <div class="container mx-auto"> 
       <h1 class="text-lg font-bold">SERVIÇOS</h1>
       <p>Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old. Richard McClintock, a Latin professor at Hampden-Sydney College in Virginia, looked up one of the more obscure Latin words, consectetur, from a Lorem Ipsum passage, and going through the cites of the word in classical literature, discovered the undoubtable source. Lorem Ipsum comes from sections 1.10.32 and 1.10.33 of "de Finibus Bonorum et Malorum" (The Extremes of Good and Evil) by Cicero, written in 45 BC. This book is a treatise on the theory of ethics, very popular during the Renaissance. The first line of Lorem Ipsum, "Lorem ipsum dolor sit amet..", comes from a line in section 1.10.32.</p>
       
       <nuxt-link to="serviço/luisaodograu">LUISAO DO GRAU</nuxt-link>
       a
       <nuxt-link to="serviço/luisaoobrabo">LUISAO o brabo</nuxt-link>


    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>