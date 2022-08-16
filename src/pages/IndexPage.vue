<template>
  <q-page
    padding
  >
  <q-form class="row justify-center">
      <p class="col-12 text-h5 text-center">Problema Directo</p>

      <div class="col-md-4 col-sm-6 col-xs-10 q-gutter-y-md">
        <!-- Start Latitude Area-->
        <div class="row">
          <p
            class="col-12 text-h6 q-pb-none"
            style="font-size: 11pt">
              Latitude [G M S]
          </p>
          <q-input
            class="col-3 q-mr-md"
            label="Graus"
            type="number"
            max="90"
            min="-90"
          />
          <q-input
            class="col-3 q-mr-md"
            label="Minutos"
            type="number"
            max="59"
            min="-59"
          />
          <q-input
            class="col-3"
            label="Segundos"
            type="number"
            max="59"
            min="-59"
          />
        </div>
        <!-- End Latitude Area-->

        <!--Start Longitude Area-->
        <div class="row">
          <p
            class="col-12 text-h6 q-pt-lg"
            style="font-size: 11pt">
              Longitude [G M S]
          </p>
          <q-input
            class="col-3 q-mr-md"
            label="Graus"
            type="number"
            max="90"
            min="-90"
          />
          <q-input
            class="col-3 q-mr-md"
            label="Minutos"
            type="number"
            max="59"
            min="-59"
          />
          <q-input
            class="col-3"
            label="Segundos"
            type="number"
            max="59"
            min="-59"
          />
        </div>
        <!--End Longitude Area-->

        <!--Start Azimute Area-->
        <div class="row">
          <p
            class="col-12 text-h6 q-pt-lg"
            style="font-size: 11pt">
              Azimute [G M S]
          </p>
          <q-input
            class="col-3 q-mr-md"
            label="Graus"
            type="number"
            max="90"
            min="-90"
          />
          <q-input
            class="col-3 q-mr-md"
            label="Minutos"
            type="number"
            max="59"
            min="-59"
          />
          <q-input
            class="col-3"
            label="Segundos"
            type="number"
            max="59"
            min="-59"
          />
        </div>
        <!--End Azimute Area-->

        <!--Start Distancia Area-->
        <div class="row">
          <p
            class="col-12 text-h6 q-pt-lg"
            style="font-size: 11pt">
              Distancia (km)
          </p>

          <q-input
            label="Distancia"
            type="number"
            class="full-width"
          />
        </div>
        <!--End Distancia Area-->

        <!--Start Semi-eixo maior Area -->
        <div class="row">
          <p
            class="col-12 text-h6 q-pt-lg"
            style="font-size: 11pt">
              Semi-eixo maior
          </p>

          <q-input
            label="Semi-eixo maior"
            type="number"
            class="full-width"
          />
        </div>
        <!--End Semi-eixo maior Area -->

        <!--Start Achatemento Area -->
        <div class="row">
          <p
            class="col-12 text-h6 q-pt-lg"
            style="font-size: 11pt">
              Achatamento
          </p>

          <q-input
            label="Achatamento"
            type="number"
            class="full-width"
          />
        </div>
        <!--End Achatemento Area -->



        <div class="full-width q-pt-md">
          <q-btn
          label="Calcular"
          color="primary"
          class="full-width"
          rounded
          type="submit"
          />
        </div>
      </div>
    </q-form>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue'
export default defineComponent({
  name: 'IndexPage'
})
</script>
