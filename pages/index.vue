<template>
  <v-sheet class="d-flex flex-column w-100 w-md-50 mx-auto justify-center align-center pt-4 ga-4">
    <div class="text-h3 font-weight-bold text-blue my-10">CSTAR</div>
    <v-text-field v-model="knowledge" label="Knowledge" outlined clearable class="w-100" />
    <v-btn text="SEARCH" size="large" block />
  </v-sheet>
</template>

<script setup lang="ts">
const knowledge = ref('')
</script>
