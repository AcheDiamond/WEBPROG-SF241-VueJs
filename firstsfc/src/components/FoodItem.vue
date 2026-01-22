<template>
  <div class="Burger">
    <h2>{{ name }}</h2>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: 'Burger,Sandwich',
      message: 'The burgers/sandwiches from Habit, In-N-Out, Chic-fil-A are stupidly delicioso'
    }
  }
};
</script>

<style>
.Burger {
    border: dashed rgba(244, 178, 178, 0.84) 1px;
    display: inline-block;
    margin: 10px;
    padding: 10px;
    background-color: rgb(203, 0, 0);
  }

</style>