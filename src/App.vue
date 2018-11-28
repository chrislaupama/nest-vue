<template>
  <v-app>
    <v-toolbar app flat>
      <v-toolbar-title class="headline text-uppercase grey--text text--darken-2">
        <span>NEST</span>
        <span class="font-weight-light">APP</span>
      </v-toolbar-title>
      <v-spacer />
      <v-btn
        flat
        class="grey--text text--darken-2"
      >
        <span class="mr-2">Login</span>
        <v-icon right>exit_to_app</v-icon>
      </v-btn>
    </v-toolbar>

    <v-content>
      <HelloWorld/>
    </v-content>
  </v-app>
</template>

<script>

export default {
  name: 'App',
  components: {
    //
  },
  data () {
    return {
      //
    }
  }
}
</script>
