<template>
  <header>
    <div class="container">
      <div class="box-header">
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
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style lang="scss" scoped >
header {
  background-color: white;
  padding: 20px 0;
}

.box-header{
    display: flex;
    justify-content: center;
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