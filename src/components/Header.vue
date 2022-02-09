<template>
  <header>
    <div class="container">
      <div class="box-header">
        <figure>
          <img src="../assets/img/dc-logo.png" alt="DC Logo" />
        </figure>
        <nav>
          <ul>
            <li v-for="(item, index) in menuItems" :key="index"><a :href="item.url" :class="{active: item.active}" >{{ item.text }}</a></li>
          </ul>
        </nav>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
  data(){
    return{
      menuItems: [
        { text: 'CHARACTERS', url:'#', active: false },
        { text: 'COMICS', url:'#', active: true },
        { text: 'MOVIES', url:'#', active: false },
        { text: 'TV', url:'#', active: false },
        { text: 'GAMES', url:'#', active: false },
        { text: 'COLLECTIBLES', url:'#', active: false },
        { text: 'VIDEOS', url:'#', active: false },
        { text: 'FANS', url:'#', active: false },
        { text: 'NEWS', url:'#', active: false },
        { text: 'SHOP', url:'#', active: false },
      ]
    }
  }
};
</script>

<style lang="scss" scoped >
header {
  background-color: white;
  padding: 20px 0;
}

.box-header{
    display: flex;
    justify-content: space-around;
    align-items: center;
}

ul {
  display: flex;
  li {
    list-style-type: none;
    margin-left: 20px;
    a {
      font-weight: bold;
      padding-bottom: 54px;
      &:hover,
      &.active {
        color: #0282f9;
        border-bottom: 10px solid #0282f9;
      }
    }
  }
}
</style>