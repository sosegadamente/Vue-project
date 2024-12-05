<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <p>This page is {{ $route.params.id }}'s page</p>
</template>
<style>
p {
  text-transform: initial;
}
</style>
<style scoped>
p {
  text-transform: capitalize;
}
</style>
