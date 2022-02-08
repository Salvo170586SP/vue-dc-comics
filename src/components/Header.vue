<template>
  <header class="container">
      <figure>
          <img src="../assets/img/dc-logo.png" alt="DC Logo">
      </figure>
      <nav>
          <ul>
              <li><a href="#">Charter</a></li>
              <li><a href="#">Charter</a></li>
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

<style>
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
 }


</style>