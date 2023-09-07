<template>
  <q-page class="flex flex-center">
    <q-card flat bordered class="my-card">
      <q-card-section>
        <div class="text-h6">September 3, 2023</div>
      </q-card-section>

      <q-card-section class="q-pt-none"> 9:36 AM - 10:55 AM </q-card-section>

      <q-separator inset />

      <q-card-section> Push Day </q-card-section>
    </q-card>

    <q-card flat bordered class="my-card">
      <q-card-section>
        <div class="text-h6">September 2, 2023</div>
      </q-card-section>

      <q-card-section class="q-pt-none"> 9:36 AM - 10:55 AM </q-card-section>

      <q-separator inset />

      <q-card-section> Leg Day </q-card-section>
    </q-card>

    <q-card flat bordered class="my-card">
      <q-card-section>
        <div class="text-h6">September 1, 2023</div>
      </q-card-section>

      <q-card-section class="q-pt-none"> 9:36 AM - 10:55 AM </q-card-section>

      <q-separator inset />

      <q-card-section> Pull Day </q-card-section>
    </q-card>
  </q-page>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "IndexPage",
});
</script>
