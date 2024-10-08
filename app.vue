<template>
  <div>
    <NuxtLayout>

      <template #header>
      </template>

      <NuxtPage/>

      <template #footer>
      </template>

    </NuxtLayout>
  </div>
</template>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto+Slab:wght@400;700&display=swap');

body {
  font-family: 'Roboto Slab', serif;
  height: 100vh;
  background-color: rgb(231, 230, 230);
  color: rgb(11, 55, 116);
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>