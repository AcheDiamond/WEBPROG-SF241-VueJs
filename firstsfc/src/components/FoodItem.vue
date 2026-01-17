<template>
  <div class="mango">
    <h2>{{ name }}</h2>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: 'Boorgir/ Sandwitch',
      message: 'I like Habit, In-N-Out, Chic-fil-A'
    }
  }
};
</script>

<style>
  .Boorgir {
    border: dashed rgba(244, 178, 178, 0.84) 1px;
    display: inline-block;
    margin: 10px;
    padding: 10px;
    background-color: rgb(203, 0, 0);
  }
</style>