<script>
export default {
  created() {
    this.$options.test = 'test'
    console.log(this.$options)
  }
}
</script>

<template>
  <h1>Open Console log and test property is available on $options</h1>
</template>

