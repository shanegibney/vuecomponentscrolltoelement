<template>
<div class="about">
  <div>
    I am the <strong>{{name}}</strong> component...
  </div>
</div>
</template>

<script>
export default {
  name: 'About',
  data() {
    return {
      name: "About"
    }
  }
}
</script>

<style scoped>
div.about {
  margin-top: 160px;
  /* border: 1px solid black; */
}
</style>
