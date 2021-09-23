<template>
  <!--导航和banner图-->
  <div class="nav">
    <div class="nav-main">
      <!--导航-->
      <div class="logo">
        <img src="@/assets/images/logo.png" />
      </div>
      <div class="nav-item">
        <div class="toggle"></div>
        <ul>
          <li>
            <a href="index.html" class="active">首页</a>
          </li>
          <li>
            <a href="worksphoto.html">作品</a>
          </li>
          <li>
            <a href="me.html">关于</a>
          </li>
          <li>
            <a href="contact.html">联系</a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      msg: "Welcome to Your Vue.js App",
    };
  },
};
</script>

<style scoped>
/*导航*/
.nav {
  position: fixed;
  width: 100%;
  height: 100px;
  background: #ffffff;
  overflow: hidden;
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1);
  z-index: 999;
}

.nav-main {
  display: flex;
  width: 90%;
  height: 100%;
  margin: 30px auto;
  justify-content: space-between;
}

.logo img {
  width: 197px;
  height: 59px;
}

.nav-item ul {
  display: flex;
  min-width: 400px;
  margin-top: 20px;
}

.nav-item li {
  width: 100px;
  font: 15px/50px "微软雅黑";
  text-align: center;
  list-style: none;
  transition: all 500ms;
}

.nav-item li a {
  text-decoration: none;
  color: #999999;
  line-height: 50px;
  padding-bottom: 4px;
}

.nav-item li a:hover {
  color: #222222;
  font-weight: 900;
}

.nav-item li a.active {
  color: hsl(0, 0%, 13%);
  font-weight: 900;
  border-bottom: 2px solid rgb(149, 5, 5);
}

/* @media (min-width: 790px) and (max-width: 1200px) {
}

@media screen and (max-width: 710px) {
  .nav-item ul {
    flex-direction: column;
  }
} */
</style>