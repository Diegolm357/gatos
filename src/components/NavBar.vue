<template>
  <v-app-bar
    app
    color="primary"
    dark
  >
    <h1>Vuecator 2000</h1>
    <v-spacer></v-spacer>
    <router-link to="/">
      <div>
        <v-icon>mdi-plus-box-multiple</v-icon>
        <span>Agregar gato</span>
      </div>
    </router-link>  
      <router-link to="/michis">
        <div>      
          <v-icon>mdi-format-list-bulleted</v-icon>
          <span>Todos los gatitos</span>
        </div>
    </router-link>

  </v-app-bar>
</template>

<script>

export default {
  name: 'NavBar',

  components: {

  },

  props: {
  },

  data: () => ({
  }),

};

</script>

<style lang="sass" scoped>
  
  h1
    font-size: 1.5rem

  a
    display: inline-block
    color: white!important
    text-decoration: none

    span
      margin-left: 5px
    
    &:first-of-type
      margin-right: 20px

</style>
