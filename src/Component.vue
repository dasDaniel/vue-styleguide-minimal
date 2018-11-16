<template>
  <div>{{msg}}</div>
</template>

<script>
export default {
  name: "Component",
  props: {
    msg: {
      type: String,
      default: "Hello"
    },
  },
}
</script>

<style>

</style>
