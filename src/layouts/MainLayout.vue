<template>
  <q-layout view="lHh Lpr lFf">
    <HeaderComponent />
    <FooterComponent />

    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
import { defineComponent, ref } from 'vue'
import HeaderComponent from 'src/components/base/HeaderComponent.vue';
import FooterComponent from 'src/components/base/FooterComponent.vue';



export default defineComponent({
  name: 'MainLayout',

  components: {
    HeaderComponent,
    FooterComponent
},

  setup () {


    return {

    }
  }
})
</script>
