<template>
  <div>
    <footer class="footer-1">
        <p>
            <span>UI设计：高铮</span>
            |
            <span>前端：梁婧宁
                <a href="https://zzzheng.com/" target="_blank">郑赫</a>
                闫正心
                彭思齐
            </span>
            |
            <span>后端：<a href='https://zzzheng.com/' target="_blank">郑赫</a></span>
        </p>
        <p>
            <span>网站贡献者：skyLab 全体成员</span>
        </p>
        <p>
            本网站由
            <a href="https://www.upyun.com/?utm_source=lianmeng&utm_medium=referral" target="_blank">
                <img class="upy-logo" src="@/assets/upyun-logo.svg" /> 又拍云
            </a>
            提供 CDN加速 / 云存储服务
        </p>
        <p>
            <span>©{{ new Date().getFullYear() }}</span> | <span>辽宁省沈阳市沈阳师范大学软件学院 skyLab</span> |
            <span><a href="https://beian.miit.gov.cn/">辽ICP备2021011233号-3</a></span>
        </p>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'SkyFooter'
}
</script>

<style>
.footer-1 p a{
    text-decoration: none;
}
.footer-1 {
    padding: 30px 0 0 0;
    font-size: 14px;
    text-align: center;
    margin-top: 50px;
}
.footer-1 p{
   margin-bottom: 5px !important;
}
.footer p {
    color: #212121;
    height: 20px;
    margin: 5px 0;
}

.footer p span {
    padding: 0 2px;
}

.upy-logo {
    width: 1.1em;
    margin-bottom: 2px;

}

.footer p a {
    transition: color 0.3s;
    text-decoration: none;
    color: #212121;
}
.footer p a:hover{
    color: #00a1d6;
}
</style>
