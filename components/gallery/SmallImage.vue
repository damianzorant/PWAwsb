<template>
  <div>
    <img :src="image" class="image" />
    <img :src="image" class="image" />
    <img :src="image" class="image" />
    <img :src="image" class="image" />
  </div>
</template>
<script>
export default {
  name: "SmallImage",
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
  width: 19%;
}
</style>
