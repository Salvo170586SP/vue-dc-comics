<template>
  <header class="container">
      <figure>
          <img src="../assets/img/dc-logo.png" alt="DC Logo">
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
}
</script>

<style scoped>
 header{
     padding: 20px 0;
     display: flex;
     align-items: center;
     justify-content: space-between;
 }

 ul{
     display: flex;
 }

 ul li{
     list-style-type: none;
     margin-left: 20px;
 }

 ul li a{
     font-weight: bold;
     padding-bottom: 54px;
 }

 ul li a:hover,
 ul li a.active
 {
    color: #0282F9;
    border-bottom: 10px solid #0282F9;
 }


</style>