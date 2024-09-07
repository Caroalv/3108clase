<template>
  <header>
    <h1 className="text-3xl font-bold underline">
      Hello world!
    </h1>

    <MiComponente /> <!--:value="5"-->
    <MiComponente2 :value="5" /> 

  </header>
</template>

<script lang="ts" setup>
import MiComponente from './components/MiComponente.vue'
import MiComponente2 from './components/MiComponente2.vue'

</script>


<style scoped></style>
