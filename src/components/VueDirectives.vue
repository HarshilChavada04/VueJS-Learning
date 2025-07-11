<template>
  <div v-bind="objBinding">Hello</div>
</template>

<script setup>
const objBinding = {
  id: 'bind-directive',
  class: 'bindClass',
  style: 'background-color: red',
}
</script>
