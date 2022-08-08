<template>
  <TheHeader v-if="headerIsTrue" />
  <main>
    <button @click="headerIsTrue = !headerIsTrue">change state of header</button>
  </main>
</template>

<script>
import TheHeader from "./TheHeader.vue";
export default {
  components: { TheHeader },
  data() {
    return {
        headerIsTrue: true
    }
  },
};
</script>

<style scoped>
main {
  width: 100%;
}
</style>
