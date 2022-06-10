<script lang="ts">
import Vue from 'vue';
// Uncomment import and local "components" registration if library is not registered globally.
// import { VueDragAndDropBuilderSample } from '@/entry.esm';

export default Vue.extend({
  name: 'ServeDev',
  // components: {
  //  VueDragAndDropBuilderSample,
  // }
});
</script>

<template>
  <div id="app">
    <vue-drag-and-drop-builder-sample />
  </div>
</template>
