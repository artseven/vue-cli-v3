<template>
  <div>
    <p>{{ url }}</p>
  </div>
</template>

<script>
export default {
  data () {
    return {
      url: process.env.VUE_APP_URL
    }
  }
}
</script>

<style>

</style>
