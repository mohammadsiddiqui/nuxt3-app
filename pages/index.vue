<template>
  <div class="content">
    <h1>Home page</h1>

    <div class="image" v-for="x in 50" :key="x">
      <img :src="`https://picsum.photos/900/450?random=${x}`" loading="lazy" />
    </div>
  </div>
</template>

<style scoped>
.image {
  min-height: 450px;
}
</style>
