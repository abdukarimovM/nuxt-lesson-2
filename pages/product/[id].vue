<template>

    <div class="container mx-auto">
           <div class="wrapper p-6 border border-dashed border-grenn-400">
               <div class="p-4 shadow bg-white"></div>
               <h2>Product item 1   </h2>
               <button>Go back</button>
           </div>
       </div>

</template>

<script setup>

const {id} = useRoute().params;

</script>

<style lang="scss" scoped>

</style>