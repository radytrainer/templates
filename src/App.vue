<template>
  <v-app>
    <Navbar/>
    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>
import Navbar from '@/components/navbar/Navbar';
export default {
  components: {
    Navbar
  },
  data: () => ({
    //
  }),
};
</script>
