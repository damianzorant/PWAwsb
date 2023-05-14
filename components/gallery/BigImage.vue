<template>
  <div class="bigImage">
    <img :src="image" class="image" />
  </div>
</template>
<script>
export default {
  name: "BigImage",
  props: {
    image: {
      type: String,
      default: () => "Pusty string",
    },
  },
};
</script>
<style scoped>
.image {
  width: 80%;
}
</style>
