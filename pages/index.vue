<template>
  <div>


    <h1>Home</h1>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  layout: 'dashboard',
  head(this: any) {
    return {
      title: this.title
    }
  },
  mounted() {
    const posts = this.$axios.$get('/posts')
    return posts
  }
})
</script>
