<template>
  <v-navigation-drawer class="nav" absolute permanent right>
    <v-card class="mx-auto" max-width="300" tile>
      <v-list rounded>
        <v-subheader>截圖</v-subheader>
        <v-img
          src="https://cdn.vuetifyjs.com/images/lists/ali.png"
          height="300px"
          dark
        >
        </v-img>
        <v-img
          src="https://cdn.vuetifyjs.com/images/lists/ali.png"
          height="300px"
          dark
        >
        </v-img>
        <v-img
          src="https://cdn.vuetifyjs.com/images/lists/ali.png"
          height="300px"
          dark
        >
        </v-img>
        <v-img
          src="https://cdn.vuetifyjs.com/images/lists/ali.png"
          height="300px"
          dark
        >
        </v-img>
        <v-img
          src="https://cdn.vuetifyjs.com/images/lists/ali.png"
          height="300px"
          dark
        >
        </v-img>
      </v-list>
    </v-card>
  </v-navigation-drawer>
</template>
<script>
export default {
  data: () => ({
    selectedItem: 1,
    items: [
      { text: 'Real-Time', icon: 'mdi-clock' },
      { text: 'Audience', icon: 'mdi-account' },
      { text: 'Conversions', icon: 'mdi-flag' },
    ],
  }),
}
</script>

<style lang="scss" scoped>
.nav {
  max-height: 100vh;
  overflow: hidden;
}
</style>
