<template>
  <div>
    <TopNav />
    <div class="gallery">
      <bigImage
        image="https://images.unsplash.com/photo-1502920917128-1aa500764cbd?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80"
      />
      <smallImage
        image="https://images.unsplash.com/photo-1502920917128-1aa500764cbd?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80"
      />
    </div>
  </div>
</template>

<script>
import TopNav from "../components/nav/TopNav.vue";
import bigImage from "../components/gallery/bigImage.vue";
import smallImage from "../components/gallery/SmallImage.vue";
export default {
  name: "IndexPage",
  components: { TopNav, bigImage, smallImage },
};
</script>
