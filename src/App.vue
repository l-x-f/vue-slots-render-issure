<template>
  <h3>examples1</h3>
  <Children0>
    <template v-if="false">100</template>
  </Children0>
  <br />

  <h3>examples2</h3>
  <Children0>
    <template v-if="false" #default>100</template>
  </Children0>
  <br />

  <h3>examples3</h3>
  <Children1>
    <template v-if="false">100</template>
  </Children1>
</template>

<script setup>
import Children0 from './components/Children0.vue'
import Children1 from './components/Children1.vue'
</script>
