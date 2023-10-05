<template>
    <div>
        <div v-if="slide" class="slide">
            <Slide/>
        </div>
        <div v-else>
            home    
        </div>

    </div>
</template>

<script setup>
import { ref , onMounted} from 'vue';
import Slide from '~/components/Slide.vue';
  
const slide = ref(true)


onMounted(() => {
    setInterval(() => {

slide.value =false

}, 4000)


})

</script>

<style scoped>

</style>