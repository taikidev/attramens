<template>
  <div>
    <h1>id</h1>
    <p>{{ $route.params.id }}</p>
  </div>
</template>

<script>
export default {
  validate({ params }) {
    return /^\d+$/.test(params.id);
  },
};
</script>
