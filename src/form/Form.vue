<template>
  <form >
    <slot></slot>
  </form>
</template>

<script>
export default {
  name: 'LgForm',
  props: {
    model: {
      type: Object,
    },
    rules: {
      type: Object,
    }
  }
}
</script>

<style>

</style>