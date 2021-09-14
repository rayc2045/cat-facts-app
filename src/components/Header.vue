<script lang="ts">
import { defineComponent } from 'vue'
import HeaderLink from './HeaderLink.vue'

export default defineComponent({
  components: { HeaderLink }
})
</script>

<template>
  <div class="my-4 text-center">
    <h4>🐱 Cat Facts</h4>
    <div class="d-flex justify-content-center">
      <HeaderLink to="/" exact>Home</HeaderLink>
      <HeaderLink to="/facts">List</HeaderLink>
    </div>
  </div>
</template>