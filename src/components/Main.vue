<template>
  <main>
    <section id="jumbotron">
      <h3>CURRENT SERIES</h3>
    </section>
    <section class="container book-container">
      <BookCard v-for="(book, index) in books" :key="index" :book="book" />
      <h5>LOAD MORE</h5>
    </section>
  </main>
</template>

<script>
import BookCard from "./BookCard.vue";
export default {
  name: "Main",

  components: {
    BookCard,
  },

  data() {
    return {
      books: [
        {
          thumb:
            require('@/assets/img/comics/locandina.jpg'),
          price: "$19.99",
          series: "Action Comics",
          type: "comic book",
        },
        {
          thumb: require('@/assets/img/comics/american_vampire.jpg'),
          price: "$3.99",
          series: "American Vampire 1976",
          type: "comic book",
        },
        {
          thumb: require('@/assets/img/comics/Aquaman.jpg'),
          price: "$16.99",
          series: "Aquaman",
          type: "graphic novel",
        },
        {
          thumb: require('@/assets/img/comics/batgirl.jpg'),
          price: "$2.99",
          series: "Batgirl",
          type: "comic book",
        },
        {
          thumb: require('@/assets/img/comics/batman.jpg'),
          price: "$3.99",
          series: "Batman",
          type: "comic book",
        },
        {
          thumb: require('@/assets/img/comics/Batman_beyond.jpg'),
          price: "$2.99",
          series: "Batman Beyond",
          type: "comic book",
        },
        {
          thumb: require('@/assets/img/comics/Superman-Batman.png'),
          price: "$3.99",
          series: "Batman/Superman",
          type: "comic book",
        },
        {
          thumb: require('@/assets/img/comics/batman_superman_annual.jpg'),
          price: "$4.99",
          series: "Batman/Superman Annual",
          type: "comic book",
        },
        {
          thumb: require('@/assets/img/comics/batman_joker.jpg'),
          price: "$5.99",
          series: "Batman: The Joker War Zone",
          type: "comic book",
        },
        {
          thumb: require('@/assets/img/comics/Batman_Three_Jokers.jpg'),
          price: "$6.99",
          series: "Batman: Three Jokers",
          type: "comic book",
        },
        {
          thumb: require('@/assets/img/comics/Batman_Harley.jpg'),
          price: "$4.99",
          series: "Batman: White Knight Presents: Harley Quinn",
          type: "comic book",
        },
        {
          thumb: require('@/assets/img/comics/Catwoman.jpg'),
          price: "$16.99",
          series: "Catwoman",
          type: "graphic novel",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
main {
  background-color: #1c1c1c;
  color: white;
}

#jumbotron {
  height: 370px;
  background-image: url("../assets/img/jumbotron.jpg");
  position: relative;

  h3 {
    background-color: #0282f9;
    color: white;
    position: absolute;
    bottom: -30px;
    left: 200px;
    padding: 20px;
  }
}

.book-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  height: 600px;
  margin-top: 100px;

  h5 {
    background-color: #0282f9;
    padding: 15px 60px;
    margin: 50px;
    cursor: pointer;
  }
}
</style>