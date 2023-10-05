<template>
    <div>
  <header class="shadow-sm bg-white">
    <nav class="container mx-auto p-4 flex justify-between ">
        <nuxt-link class="font-bold" to="/">hundred</nuxt-link>
        <ul class="flex gap-4">
            <nuxt-link to="/about">about</nuxt-link>
            <nuxt-link to="/products">products</nuxt-link>
        </ul>
        
    </nav >
  </header>
    </div>

    <div class="container mx-auto p-4">
        <slot/>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

</style>