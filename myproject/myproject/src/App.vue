<template>
  <div class="container">
    <h1>Welcome to my first website!</h1>
    <p>This is made with Vue 3 + Vite 🎉</p>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style>
body {
  margin: 0;
  font-family: system-ui, sans-serif;
  background: linear-gradient(135deg, #dbeafe, #fef9c3);
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
}

.container {
  text-align: center;
  background: white;
  padding: 2rem;
  border-radius: 1rem;
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
}

h1 {
  color: #1d4ed8;
  font-size: 2.5rem;
}

p {
  color: #334155;
  font-size: 1.2rem;
  margin-top: 1rem;
}
</style>