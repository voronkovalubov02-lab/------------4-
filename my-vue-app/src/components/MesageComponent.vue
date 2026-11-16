<template>
  <div class="mesag-bloc">
    <h2>{{ title }}</h2>
    <p>{{ mesag }}</p>
  </div>
</template>

<script>
export default {
  name: 'MesagComponent',
  props: {
    title: {
      type: String,
      required: true
    },
    mesag: {
      type: String,
      required: true
    }
  }
}
</script>

<style scoped>
.mesag-bloc {
  background-color: #1b2838;
  padding: 20px;
  margin: 20px auto;
  max-width: 500px;
  border-radius: 10px;
  font-family: sans-serif;
}

.mesag-bloc h2 {
  color: #66c0f4;
  margin-top: 0;
  margin-bottom: 10px;
  font-size: 22px;
}

.mesag-bloc p {
  color: #ffffff;
  margin: 0;
  font-size: 16px;
}
</style>