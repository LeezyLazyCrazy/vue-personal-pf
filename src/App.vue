<template>
  <v-app>
    <div class="wrap">
      <v-main>
        <router-view/>
      </v-main>
    </div>
    
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
<style lang="scss" scoped>
.wrap{
  background: linear-gradient(
    to bottom,
    #ffd54f,
    #ffd54f 10%,
    #fdd550 30%,
    #fac042 50%
  );
  }
</style>
