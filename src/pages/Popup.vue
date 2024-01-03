<script lang="ts" setup>
console.log("Hello from the popup!");
</script>

<template>
  <div class="content">
    <img src="/icon-with-shadow.svg" />
    <h1>vite-plugin-web-extension</h1>
    <p>
      Template: <code>vue-ts</code>
    </p>
  </div>
</template>

<style>
html,
body {
  padding: 0;
  margin: 0;
}

.content {
  width: 300px;
  height: 400px;
  border-radius: 10px;
  display: flex;
  flex-direction: column;
  gap: 16px;
  align-items: center;
  justify-content: center;
  border-radius: 10px;
}


img {
  width: 200px;
  height: 200px;
}

h1 {
  font-size: 18px;
  color: white;
  font-weight: bold;
  margin: 0;
}

p {
  color: white;
  opacity: 0.7;
  margin: 0;
}

code {
  font-size: 12px;
  padding: 2px 4px;
  background-color: #ffffff24;
  border-radius: 2px;
}
</style>
