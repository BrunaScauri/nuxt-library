<template>
  <div class='ibook-layout'>
    <HeaderPage />
    <PageContent>
      <Nuxt />
    </PageContent>
    <FooterMain />
  </div>
</template>

<style lang="scss" scoped>
.ibook-layout {
  margin-top: 4.313rem;
  display: grid;
  grid-gap: 6.75rem;
  .container {
    padding-bottom: 6.75rem;
  }
}
</style>
