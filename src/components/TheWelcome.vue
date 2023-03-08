<script setup lang="ts">
import { useCounterStore } from '../stores/counter';
</script>

<template>
  <div>
    <p>teste {{ useCounterStore().count }}</p>
    <button style="width: 200px; height: 30px; border-radius: 5px;" @click="useCounterStore().increment">Incrementar</button>
  </div>
</template>
