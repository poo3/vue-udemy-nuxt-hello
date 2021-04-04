<template>
  <div class="container">
    <p>{{ message }}</p>
    <hr />
    <router-link to="/price">Price page</router-link>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: 'Hello World!',
    }
  },
}
</script>
