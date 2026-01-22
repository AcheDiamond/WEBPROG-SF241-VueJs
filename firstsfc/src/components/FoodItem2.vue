<template>
  <div class="Anime">
    <h2>{{ name }}</h2>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: 'My Top 3 Dark Fantasy Animes',
      message: 'Tokyo Ghoul (only season 1), Made in Abyss, Attack on Titan'
    }
  }
};
</script>

<style>
.Anime {
    border: dashed rgb(243, 242, 242) 1px;
    display: inline-block;
    margin: 10px;
    padding: 10px;
    background-color: rgba(0, 0, 0, 0.16);
  }

</style>