<template>
  <div class="book-card">
    <figure>
      <img :src="book.thumb" :alt="book.series" />
    </figure>
    <h4>{{ book.series }}</h4>
  </div>
</template>

<script>
export default {
  name: "BookCard",
  props: ["book"],
};
</script>

<style lang="scss" scoped>
.book-card {
  flex-basis: calc(100% / 6);

  figure {
    overflow: hidden;
    width: 180px;
    height: 180px;

    img {
      width: 100%;
    }
  }

  h4 {
    margin-top: 20px;
  }
}
</style>