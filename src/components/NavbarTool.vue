<template>
  <v-navigation-drawer absolute permanent left>
    <v-card class="mx-auto" tile>
      <v-list dense>
        <!-- <v-subheader>REPORTS</v-subheader> -->
        <v-list-item-group v-model="selectedItem" color="primary">
          <v-list-item v-for="(item, i) in items" :key="i">
            <v-list-item-icon>
              <v-icon v-text="item.icon"></v-icon>
            </v-list-item-icon>
            <v-list-item-content>
              <v-list-item-title v-text="item.text"></v-list-item-title>
            </v-list-item-content>
          </v-list-item>
        </v-list-item-group>
      </v-list>
    </v-card>
  </v-navigation-drawer>
</template>

<script>
export default {
  data: () => ({
    selectedItem: 1,
    items: [{ text: '', icon: 'mdi-camera' }],
  }),
}
</script>

<style lang="scss" scoped>
.v-navigation-drawer {
  max-width: 4rem;
  // padding-top: 5rem;
}
</style>
