<template>
  <img class="imagem-responsiva" :src="url" :alt="titulo" />
</template>

<script>
export default {
  props: ["url", "titulo"]
};
</script>

<style lang="scss" scoped>
.imagem-responsiva {
  width: 90%;
}
</style>
