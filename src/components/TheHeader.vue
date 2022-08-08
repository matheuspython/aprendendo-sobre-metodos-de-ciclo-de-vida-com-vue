<template>
  <header>header</header>
</template>

<script>
export default {
  beforeMount() {
    console.log("componente antes de ser montado");
    console.log(this.$el)
  },
  mounted() {
    console.log("componente montado");
    console.log(this.$el)
  },
  beforeUnmount() {
    console.log("componente antes de ser desmontado");
    console.log(this.$el)
  },
  unmounted() {
    console.log("componente desmontado");
    console.log(this.$el)
  },
};
</script>

<style scoped>
header {
  width: 100%;
  height: 45px;
  background: #8c11bd;
  color: #fff;
  display: flex;
  align-items: center;
  justify-content: center;
  text-transform: uppercase;
}
</style>
