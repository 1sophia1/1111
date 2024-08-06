<!-- eslint-disable no-undef -->
<template>
  <div class="container">
  <div class="about">
    <div class="backimg1">
      <img src="@/assets/decoration/A4.png" alt="">
    </div>
    <div class="backimg2">
      <img src="@/assets/decoration/C4.png" alt="">
    </div>
    <img src="@/assets/other/bigmember.png" alt="" class="about-img">
    <ALotOfCard1></ALotOfCard1>
    <ALotOfCard2></ALotOfCard2>
  </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
@media (max-width: 576px) {
.about-img{
  width: 50%;
}
}
@media only screen and (max-width: 992px) and (min-width: 576px) {
.about-img{
  width: 25%;
}
}
@media (min-width: 992px) {
.about-img{
  width: 15%;
}
}
@media (max-width: 1399px) {
.backimg1{
  display: none;
}
.backimg2{
  display: none;
}
}
@media (min-width: 1400px) {
.about{
  width: 100% !important;
  position: relative;
}
.backimg1{
  position: absolute;
    z-index: -1;
    left: 10%;
}
.backimg1 img{
  width: 270px;
  height: 270px;
}
.backimg2{
  position: absolute;
  z-index: -1;
    right:1%;
    top: -70px;
}
.backimg2 img{
  width: 400px;
  height: 400px;
}
}

</style>
