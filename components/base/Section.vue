<template>
  <div class="relative grid max-w-screen-xl grid-cols-12 px-4 mx-auto overflow-hidden sm:px-8 gap-x-6" v-bind="$attrs">
    <slot></slot>
  </div>
</template>


<script lang="ts">
  export default{
    name: 'BaseSection'
  }

</script>

<style>

</style>