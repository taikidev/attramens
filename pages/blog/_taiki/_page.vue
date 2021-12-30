<template>
  <div>
    {{ $route.params.taiki }}
  </div>
</template>

<script>
export default {
  created() {
    console.log(this.$route);
  },
};
</script>
