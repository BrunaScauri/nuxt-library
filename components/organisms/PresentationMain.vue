<template>
  <div class="presentation">
    <p>iBook é uma plataforma de biblioteca de livros online fictícia, criada por <b>Bruna Scauri</b> com base nas aulas do Bootcamp Cataline, utilizando Vue, Nuxt, Typescript, HTML, SCSS e a biblioteca Axios.</p>

    <img src='@/assets/img/presentation.svg' alt="apresentação do ibook">
  </div>
</template>


<style lang="scss" scoped>
.presentation {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-gap: 2rem;
  align-items: center;
  @include screen('small', 'medium') {
    grid-template-columns: 1fr;
  }
  p {
    line-height: 26px;
  }
  img {
    max-width: 100%;
  }
}
</style>
