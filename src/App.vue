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
    // #home{
    //   width:100%;
    //   overflow-x:hidden;
    // }
  </style>
