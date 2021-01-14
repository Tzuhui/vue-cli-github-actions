<template>
  <div class="about">
    <h1>This is an about page</h1>
    {{ title }}
  </div>
</template>

<script>
  export default {
    data() {
      return {
        title: process.env.VUE_APP_TITLE,
      }
    }
  }
</script>