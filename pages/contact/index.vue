<template>
  <div class="container mx-auto">
    <div class="wrapper p-6 border border-dashed border-green-400">
      <div class="p-4 shadow bg-white">
        <h2>Contact</h2>
        <button>go back</button>
      </div>
    </div>
  </div>
</template>

<script setup>
const { name } = useRoute();
useHead({
  title: `${name} page of Fakestore App`,
  meta: [
    { name: "description", content: `${name} page of Fakestore App` },
    { name: "author", content: "Nuxt3 app" },
  ],
});
</script>

<style lang="scss" scoped></style>
