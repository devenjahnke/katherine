<template>
  <layout title="Welcome">
    <h1 class="text-5xl">Welcome</h1>
    <p>Hello, welcome to your first Inertia app!</p>
  </layout>
</template>

<script>
  import Layout from '../Layouts/Layout'

  export default {
    components: {
      Layout,
    },
    props: {
      user: Object,
    },
  }
</script>