
<template>
  <div class="main">
    <h1>
      {{name}}
    </h1>
  </div>
</template>

<script lang="ts">
  import { defineComponent } from 'vue';

  export default defineComponent({
    data: function() {
      return {
        name: 'Hello Vue 3!',
      }
    },
  });
</script>

<style scoped lang="scss">
.main {
  h1 {
    color: #fff;
    background-color: #000;
  }
}
</style>
