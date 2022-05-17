<template>
  <div>
      <h1>{{ titleText }}</h1>
  </div>
</template>

<script>
export default {
    name: "AppTitle",
    data: function() {
      return {
        titleText: 'La mia prima app con Vue CLI!'
      }
    }
}
</script>

<style>

</style>