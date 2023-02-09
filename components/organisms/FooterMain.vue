<template>
  <footer class="footer">
    <PageContent>
      <Logo />
      <p>Copyright &copy; {{ currentYear }} ibook</p>
    </PageContent>
  </footer>
</template>

<script lang="ts">
  import Vue from 'vue'

  export default Vue.extend({
    computed: {
      currentYear() {
        return new Date().getFullYear()
      }
    }
  })
</script>

<style lang="scss" scoped>
.footer {
  position: absolute;
  bottom: 0;
  width: 100%;
  height: 110px;
  background: color(dark, darkest);
  //min-height: 100vh;
  display: flex;
  .container {
    display: grid;
    height: 100%;
    grid-auto-flow: column;
    justify-content: space-between;
    align-items: center;
    p {
      color: color('light', 'darkest');
    }
  }
}
</style>
