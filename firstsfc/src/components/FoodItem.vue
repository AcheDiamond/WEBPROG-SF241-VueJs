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