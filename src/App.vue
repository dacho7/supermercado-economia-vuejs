<template>
  <v-app>
    <router-link to="/">
      <v-btn color="primary" depressed>
        <v-icon color="white"> mdi-home </v-icon>
      </v-btn>
    </router-link>
    <router-view></router-view>
  </v-app>
</template>

<script>
export default {
  name: 'App',
  data: () => ({
    //
  }),
};
</script>
