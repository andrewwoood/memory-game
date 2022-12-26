<template>
  <div id="app">
    <main font-sans p="x-4 y-10" text="center gray-700 dark:gray-200">
      <h1>Memory Game</h1>
      <div class="card-container">
        <div @click="print(n)" class="card" v-for="n in 3*3">hello {{n}}</div>
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: 'App',
  methods: {
    print(n) {
      console.log(`hello from ${n}`);
    }
  }
}
</script>