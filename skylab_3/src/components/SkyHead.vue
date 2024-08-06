<template>
  <div class="fixed-top a1">
    <nav class="navbar navbar-expand-md navbar-dark con">
      <div class="container">
      <!-- Brand -->
      <p class="text1">
        <span class="orange">Sk</span>
        <span class="blue">y</span>
        <span class="blue">L</span>
        <span>ab</span>
        <span class="long-box1"></span>
      </p>
      <!-- Toggler/collapsibe Button -->
      <button class="navbar-toggler magin2" type="button" data-bs-toggle="collapse" data-bs-target="#collapsibleNavbar">
        <span class="navbar-toggler-icon magin1"></span>
      </button>
      <!-- Navbar links -->
      <div class="collapse navbar-collapse" id="collapsibleNavbar">
        <ul class="navbar-nav">
          <li class="nav-item">
            <router-link to="/home">主页</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/about">成员</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/honor">荣誉</router-link>
          </li>
        </ul>
      </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'SkyHead'
}
</script>

<style>

.magin1{
  margin-top: 0px !important;
}
.magin2{
  margin-right: 10px;
}
.text1{
    font-family: 'Microsoft YaHei';
    font-size: 48px;
    font-weight: 700;
  }
</style>
