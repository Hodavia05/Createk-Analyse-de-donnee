<template>
  <div id="app">
    <h1>Bienvenue sur mon projet Vue.js !</h1>
    <p>{{ message }}</p>
    <button @click="changerMessage">Changer le message</button>
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      message: 'Bonjour, Vue.js !',
    };
  },
  methods: {
    changerMessage() {
      this.message = 'Le message a été changé !';
    },
  },
};
</script>
