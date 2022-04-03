<template>
  <v-app>
    <v-main>
      <!-- <NavbarTool /> -->
      <ImageList />
      <ModelView />
    </v-main>
    <FloatBtn />
  </v-app>
</template>

<script>
import ModelView from './components/ModelView'
// import NavbarTool from './components/NavbarTool'
import ImageList from './components/ImageList'
import FloatBtn from './components/FloatBtn'

export default {
  name: 'App',

  components: {
    ModelView,
    // NavbarTool,
    ImageList,
    FloatBtn,
  },

  data: () => ({
    //
  }),
}
</script>
