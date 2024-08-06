<template>
<div class="container">
    <div class="about">
      <div class="backimg1">
        <img src="@/assets/decoration/A4.png" alt="">
      </div>
      <div class="backimg2">
        <img src="@/assets/decoration/C4.png" alt="">
      </div>
      <img src="@/assets/other/bighonor.png" alt="" class="about-img">
      <div class="ceshi5"></div>
      <div class="container">
          <span>
            学科竞赛
          </span>
        </div>
      <div class="Totop container">
      <div class="row">
        <div class="p-4">
          <div class="row">
            <div class="col-md-4 col-6 padding-1">
              <div class="img4">
                <img src="@/assets/honor/a2.jpg" alt="" class="img6"/>
              </div>
            </div>
            <div class="col-md-4 col-6 padding-1">
              <div class="img4">
                <img src="@/assets/honor/a5.jpg" alt="" class="img6"/>
              </div>
            </div>
            <div class="col-md-4 col-6 padding-1">
              <div class="img4">
                <img src="@/assets/honor/a4.jpg" alt="" class="img6"/>
              </div>
            </div>
            <div class="col-md-4 col-6 padding-1">
              <div class="img4">
                <img src="@/assets/honor/a6.png" alt="" class="img6"/>
              </div>
            </div>
            <div class="col-md-4 col-6 padding-1">
              <div class="img4">
                <img src="@/assets/honor/a1.jpg" alt="" class="img6"/>
              </div>
            </div>
            <div class="col-md-4 col-6 padding-1">
              <div class="img4">
                <img src="@/assets/honor/a3.jpg" class="img6" alt=""/>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
    <div class="ceshi5"></div>
      <div class="container">
          <span>
            创新创业
          </span>
        </div>
      <div class="Totop container">
      <div class="row">
        <div class="p-4">
          <div class="row">
            <div class="col-md-4 col-6 padding-1">
              <div class="img4">
                <img src="@/assets/honor/b5.jpg" alt="" class="img6"/>
              </div>
            </div>
            <div class="col-md-4 col-6 padding-1">
              <div class="img4">
                <img src="@/assets/honor/b4.jpg" alt="" class="img6"/>
              </div>
            </div>
            <div class="col-md-4 col-6 padding-1">
              <div class="img4">
                <img src="@/assets/honor/b3.jpg" alt="" class="img6"/>
              </div>
            </div>
            <div class="col-md-4 col-6 padding-1">
              <div class="img4">
                <img src="@/assets/honor/b6.jpg" alt="" class="img6"/>
              </div>
            </div>
            <div class="col-md-4 col-6 padding-1">
              <div class="img4">
                <img src="@/assets/honor/b1.jpg" alt="" class="img6"/>
              </div>
            </div>
            <div class="col-md-4 col-6 padding-1">
              <div class="img4">
                <img src="@/assets/honor/b2.jpg" alt="" class="img6"/>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="ceshi5"></div>
      <div class="container">
          <span>
            实习
          </span>
        </div>
      <div class="Totop container">
      <div class="row">
        <div class="p-4">
          <div class="row">
            <div class="col-md-4 col-6 padding-1">
              <div class="img5">
                <img src="@/assets/honor/c1.png" alt="" class="img6"/>
              </div>
            </div>
            <div class="col-md-4 col-6 padding-1">
              <div class="img5">
                <img src="@/assets/honor/c2.png" alt="" class="img6"/>
              </div>
            </div>
            <div class="col-md-4 col-6 padding-1">
              <div class="img5">
                <img src="@/assets/honor/c3.png" alt="" class="img6"/>
              </div>
            </div>
            <div class="col-md-4 col-6 padding-1">
              <div class="img5">
                <img src="@/assets/honor/c5.png" alt="" class="img6"/>
              </div>
            </div>
            <div class="col-md-4 col-6 padding-1">
              <div class="img5">
                <img src="@/assets/honor/c4.png" alt="" class="img6"/>
              </div>
            </div>
            <div class="col-md-4 col-6 padding-1">
              <div class="img5">
                <img src="@/assets/honor/c6.jpg" alt="" class="img6"/>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    </div>
</template>

<script>

</script>

<style>
.container span{
  font-size: 28px;
  font-weight:700 ;
}
.img4{
  transition: transform 0.5s;
}
.img4 img{
  width: 100%;
  aspect-ratio: 1 / 1.4;
}
.img4:hover {
  transform: scale(1.2); /* 鼠标悬停时放大20% */
}
.img5 img{
  width: 100%;
  aspect-ratio: 1 / 1;
}
.img5{
  transition: transform 0.5s;
}
.img5:hover{
  transform: scale(1.2);
}
.img6{
    display: inline;
    border-radius:20px ;
    box-shadow: 1px 1px 10px #bababa;
    transition: transform 0.5s;
}
.img6:hover{
  box-shadow: 1px 1px 10px black;
}
.padding-1{
  padding: 1vw 1vw !important;
}
@media (max-width: 576px) {
.about-img{
  width: 50%;
}
.ceshi5{
  width: 100%;
  height: 20px;
}
}
@media only screen and (max-width: 992px) and (min-width: 576px) {
.about-img{
  width: 25%;
}
.ceshi5{
  width: 100%;
  height: 20px;
}
}
@media (min-width: 992px) {
.about-img{
  width: 15%;
}
.ceshi5{
  width: 100%;
  height: 5vh;
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
