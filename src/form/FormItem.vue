<template>
  <div>
    <label>{{label}}</label>
    <div>
      <slot></slot>
      <p v-if="errorMessage">{{errorMessage}}</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'LgFormItem',
  props: {
    label: {
      type: String,
    },
    prop: {
      type: String,
    }
  },
  data() {
    return {
      errorMessage: ''
    }
  }
}
</script>

<style>

</style>