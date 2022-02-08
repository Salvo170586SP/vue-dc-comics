<template>
  <header class="container">
    <figure>
      <img src="../assets/img/dc-logo.png" alt="DC Logo" />
    </figure>
    <nav>
      <ul>
        <li><a href="#">Charter</a></li>
        <li><a href="#" class="active">Charter</a></li>
        <li><a href="#">Charter</a></li>
        <li><a href="#">Charter</a></li>
        <li><a href="#">Charter</a></li>
        <li><a href="#">Charter</a></li>
        <li><a href="#">Charter</a></li>
        <li><a href="#">Charter</a></li>
        <li><a href="#">Charter</a></li>
        <li><a href="#">Charter</a></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style lang="scss" scoped >
header {
  padding: 20px 0;
  display: flex;
  align-items: center;
  justify-content: space-between;
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