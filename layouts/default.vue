<template>
  <div>
    <div>
      <!--for some reason my vue app didnt generate a 'layouts' folder and i had some problems generating one myself, even more so adding a second template file and linking it to the app.
      for now, both my templates will work on one file. -->
      <h1>Meu dashboard</h1>
    </div>
    <ul>
      <NuxtLink to="/">Home</NuxtLink>
      <NuxtLink to="/about">About</NuxtLink>
    </ul>
    <Nuxt />
    <footer>Rodapé</footer>
  </div>
</template>
