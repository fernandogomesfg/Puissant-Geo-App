<template>
  <q-footer class="bg-transparent">
    <div class="q-pa-sm" >
      <q-tabs
        style="border-radius: 50px"
        v-model="tab"
        class="bg-white text-grey shadow-2"
        indicator-color="transparent"
        active-color="primary"
      >

        <q-tab>
          <q-route-tab
            to="/"
            exact
            name="public"
            icon="public"
          />
        </q-tab>

        <q-tab>
          <q-route-tab
            to="/inverso"
            exact
            name="public_off"
            icon="public_off"
          />
        </q-tab>
      </q-tabs>


    </div>
  </q-footer>
</template>

<script>
import { defineComponent, ref } from 'vue'

export default defineComponent({
  name: 'FooterComponent',

  setup(){
    const tab = ref('mail')


    return{
      tab
    }
  }
})

</script>
