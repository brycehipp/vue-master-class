<template>
  <div class="col-full">
    <h1>Not Found</h1>
    <p>
      Oops, we couldn't find what you are looking for.<br>
      Why don't you
      <router-link :to="{ name: 'Home' }">
        go home instead?
      </router-link>
    </p>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
h1 {
  font-size: 4rem;
}
p {
  font-size: 2rem;
  font-weight: 100;
}
div {
  padding: 2rem 5rem;
  text-align: center;
}
</style>
