<template>
  <div class="business-card">
    <h2>{{ name }}</h2>
    <p><strong>Телефон:</strong> {{ phone }}</p>
    <p><strong>Email:</strong> {{ email }}</p>
  </div>
</template>

<script>
export default {
  name: 'BusinessCard',
  props: {
    name: {
      type: String,
      required: true
    },
    phone: {
      type: String,
      required: true
    },
    email: {
      type: String,
      required: true
    }
  }
}
</script>

<style scoped>
.business-card {
  background: linear-gradient(135deg, #1b2838, #2a475e);
  color: #fff;
  padding: 20px;
  margin: 20px auto;
  max-width: 350px;
  border-radius: 12px;
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
  font-family: sans-serif;
  text-align: left;
  border-left: 5px solid #66c0f4;
}

.business-card h2 {
  margin-top: 0;
  color: #66c0f4;
  font-size: 20px;
  border-bottom: 1px solid rgba(255, 255, 255, 0.2);
  padding-bottom: 8px;
}

.business-card p {
  margin: 8px 0;
  font-size: 15px;
  color: #c6d4df;
}
</style>