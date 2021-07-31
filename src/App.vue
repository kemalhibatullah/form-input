<template>
  <v-app>
    <v-main>
      <Form/>
    </v-main>
  </v-app>
</template>

<script>
// import HelloWorld from './components/HelloWorld';
import Form from './components/Form.vue'

export default {
  name: 'App',

  components: {
    Form
  },

  data: () => ({
    //
  }),
};
</script>

<style scoped>
#app {
   background-color : #02044A;
}
</style>
