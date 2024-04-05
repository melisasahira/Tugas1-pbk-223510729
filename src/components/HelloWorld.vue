<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h3>
      Melisa Sahira
      <a href="https://vitejs.dev/" target="_blank" rel="noopener"></a>
      <a href="https://vuejs.org/" target="_blank" rel="noopener"></a>
    </h3>
    <h4>
      Dumai, 30 Desember 2003
      <a href="https://vitejs.dev/" target="_blank" rel="noopener"></a>
      <a href="https://vuejs.org/" target="_blank" rel="noopener"></a>
    </h4>
  </div>
</template>
<style>
  body {
    font-family: Arial, sans-serif;
    background-color: rgb(155, 213, 236);
    margin: 0;
    padding: 0;
  }
</style>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;

}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
