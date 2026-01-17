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
      name: 'Boorgir/ Sandwitch',
      message: 'I like Habit, In-N-Out, Chic-fil-A'
    }
  }
};
</script>