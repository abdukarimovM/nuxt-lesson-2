<template>

    <div class="container mx-auto">
           <div class="wrapper p-6 border border-dashed border-grenn-400">
               <div class="p-4 shadow bg-white flex justify-between items-center"></div>
               <h2 class="font-bold uppercase">Products</h2>
               <button @click="back.go(-1)" class="bg-red-500 text-white px-2 py-2 focus:ring-2 focus:ring-red-400 rounded-xl">Go back</button>
           </div>
       </div>

       <div class="wrapper">
            <div class="card shadow-">
                <img src="https://picsum.photos/id/1/200/300" alt="rasm" class="card-img">
                <div>
                    <h2 class="text-green-600">Product name</h2>
                    <strong class="text-2xl text-orange-500">345$</strong>

                    <button class="bg-cyan-600 block">Details</button>
                </div>
            </div>
       </div>

</template>

<script setup>

const { data, pending, error, refresh}=useFetch('https://fakestoreapi.com/products');

console.log(data, pending, error );

</script>

<style lang="scss" scoped>

.wrapper{
    display: grid;
}

</style>