<template>
  <div class="code-area">
    <span style="color: #777; font-style: italic">
      // 404 page not found.
    </span>
    <span>
      <span style="color: #d65562">if</span>
      (<span style="color: #4ca8ef">!</span
      ><span style="font-style: italic; color: #db9538">found</span>) {
    </span>
    <span>
      <span style="padding-left: 15px; color: #2796ec">
        <i style="width: 10px; display: inline-block"></i>throw
      </span>
      <span> (<span style="color: #a6a61f">"(╯°□°)╯︵ ┻━┻"</span>); </span>
      <span style="display: block">}</span>
      <span style="color: #777; font-style: italic">
        // <a href="/"><span style="color: #3fa531">Go home!</span></a>
      </span>
    </span>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style scoped>
body {
  background: linear-gradient(315deg, #ffffff, #d7e1ec);
  color: #c4c4c4;
  font-family: "Courier new", serif;
  font-size: 18px;
  line-height: 1.5em;
  cursor: default;
}

a {
  text-decoration: none;
}

.code-area {
  position: absolute;
  width: 320px;
  min-width: 320px;
  top: 50%;
  left: 50%;
  -webkit-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
}

.code-area > span {
  display: block;
}

@media screen and (max-width: 320px) {
  .code-area {
    font-size: 5vw;
    min-width: auto;
    width: 95%;
    margin: auto;
    padding: 5px;
    padding-left: 10px;
    line-height: 6.5vw;
  }
}
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}
</style>
