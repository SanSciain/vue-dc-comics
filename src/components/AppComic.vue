<template>
  <section>
    <div class="img-container">
      <img :src="comicObj.thumb" alt="comicObj.type" />
    </div>
    <h5>{{ comicObj.series }}</h5>
  </section>
</template>

<script>
export default {
  name: "AppComic",
  props: {
    comicObj: Object,
  },
};
</script>

<style lang="scss" scoped>
section {
  width: calc((100% / 6) - 1rem);
  margin: 2rem 0.5rem;

  .img-container {
    width: 100%;
  }

  h5 {
    font-size: 0.8rem;
  }
}
</style>
