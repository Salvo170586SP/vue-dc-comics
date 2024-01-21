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
    height: 190px;
    border-radius: 10px;
    margin-bottom: 7px;

    img {
      width: 100%;
      &:hover{
        transform: scale(1.2);
        transition: 0.2s;
      }
    }

  }

  h4 {
    margin-bottom: 20px;
  }
}
</style>